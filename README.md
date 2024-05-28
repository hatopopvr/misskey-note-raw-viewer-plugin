# misskey-note-raw-viewer-plugin

MisskeyノートのRAWデータを表示するMisskeyプラグインです。[AiScript](https://github.com/syuilo/aiscript/tree/master)によって記述されています。

## 機能

- ノートのRAWデータをYAML形式、JSON形式、整形されたJSON形式で表示

## 必要な権限

このプラグインを使用するには、以下の権限が必要です。

- **read:reactions**: ノートのリアクションデータを読み取るために必要です。

## インストール方法

1. [リリースページ](https://github.com/hatopopvr/misskey-note-raw-viewer-plugin/releases)から`MisskeyNoteRawViewer.is`ファイルをダウンロードします。
2. Misskeyの`設定 > プラグインのインストール`に移動します。
3. ダウンロードした`MisskeyNoteRawViewer.is`ファイルの内容をコピーし、テキストエリアに貼り付けます。
4. `インストール`ボタンを押します。

## 使い方

1. ノートの詳細ビューで、`</>Raw`ボタンをクリックします。
2. 設定に基づいて、選択された表示形式でノートのRAWデータが表示されます。

## 設定

プラグインの設定では、以下の項目を指定できます。

- **インデント**: YAMLやJSONのインデントを設定します。（デフォルト: 2）
- **YAML表示を有効にする**: YAML表示を有効にするかどうかを設定します。（デフォルト: false）
- **JSON表示を有効にする**: JSON表示を有効にするかどうかを設定します。（デフォルト: false）
- **Formatted JSON表示を有効にする**: Formatted JSON表示を有効にするかどうかを設定します。（デフォルト: true）

## 注意事項

- 表示形式によっては、データの大きさや構造に応じて表示が崩れる可能性があります。

## 作者
[hatopop_vr](https://misskey.io/@hatopop_vr)
