# misskey-note-raw-viewer-plugin

MisskeyノートのRAWデータを整形されたJSON形式で表示するMisskeyプラグインです。
[AiScript](https://github.com/syuilo/aiscript/tree/master)によって記述されています。

## 使い方

- ノートの`･･･`メニューからプラグインボタン`</>Raw`を選択すると、ノートのRAWデータを整形されたJSON形式で表示します。
- Rawデータは右上のボタンからクリップボードにコピーが可能です。

![image](images/image_001.gif)

## 必要な権限

このプラグインを使用するには、以下の権限が必要です。

- **read:reactions**: ノートのリアクションデータを読み取るために必要です。

## インストール方法

1. [リリースページ](https://github.com/hatopopvr/misskey-note-raw-viewer-plugin/releases)から`MisskeyNoteRawViewer.is`ファイルをダウンロードします。
2. Misskeyの`設定 > プラグインのインストール`に移動します。
3. ダウンロードした`MisskeyNoteRawViewer.is`ファイルの内容をコピーし、テキストエリアに貼り付けます。
4. `インストール`ボタンを押します。

## 設定

プラグインの設定では、以下の項目を指定できます。

- **インデント**: JSONのインデントを設定します。（デフォルト: 2）

##  カスタムCSSでのダイアログの表示調整
以下のCSSは、ダイアログのテキスト表示を左詰めにし、ウインドウサイズを拡大するためのものです。デフォルトではテキストは中央揃えで、ウインドウサイズが小さいため、カスタムCSSで調整することをお勧めします。
```css
.xa5A4 {
    min-width: 320px;
    max-width: 2000px;  /* original 480px; */
    box-sizing: border-box;
    text-align: left; /* original center; */
}
```

## 作者
[hatopop_vr](https://misskey.io/@hatopop_vr)
