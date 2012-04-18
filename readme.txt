[アドオン名]
io_import_vmd

[概要]
blender 2.6x用のvmdファイルのimport addonです。

[注意]
ボーン名のマッピングをblender2pmx addonの名前変換規則に従って行っています。
blender2pmx以外のaddonでインポートしたモデルは正常にモーションが適用できない可能性があります。

[動作確認環境]
Windows 7 64bit
Blender 2.62 64bit

[使用方法]
(1) io_import_cmd.pyをblenderのaddonディレクトリにコピーしてください。
(2) User PreferenceのAddonsから"Import-Export: Import Vocaloid Motion Data file (.vmd)"を探してチェックを入れてください。
(3) あらかじめ"blender2pmx"addonで読み込んでおいたモデルのMeshとArmatureを選択してください。
(4) MenuのFileから「Import -> Vocaloid Motion Data file (.vmd)」を選択してください。
(5) ファイル選択画面でvmdファイルを選択すると選択中のオブジェクトにモーションがインポートされます。

[その他・制限など]
・ボーン名のマッピングルールは次の通りです。
「左○○」→「○○_L」
「右○○」→「○○_R」

・補間情報は未対応
・カメラモーション未対応
・ライトモーション未対応
・その他もろもろ未対応
