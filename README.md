S-PkPG
====

S-PkPGはペアカーニング情報を持った全角約物フォントです。  
WEBフォントとして使用することで、WEBブラウザでの連続約物の処理が可能です。

- S-PkPG：文字幅全角
- S-PkPG-HP：句読点の文字幅は全角の8割、括弧類は約半角


### 収録字形

「」『』（）｛｝［］〈〉《》〔〕【】、，。．


### 使用例

```css
@font-face {
  font-family: "S-PkPG-R";
  src: url("S-PkPG-R.ttf") format('truetype');
}
body{
  text-rendering: optimizeLegibility;
  font-family: Verdana, Arial, S-PkPG-R, 'ヒラギノ角ゴ Pro W3','メイリオ','ＭＳ ゴシック', sans-serif;
}
```
