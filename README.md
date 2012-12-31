S-PkPG
====

S-PkPGはペアカーニング情報を持った全角約物フォントです。  
WEBフォントとして使用することで、WEBブラウザでの連続約物の処理が可能です。

#### S-PkPG
仮想ボディ全角の約物フォント。  
ペアカーニングが有効な環境（text-rendering: optimizeLegibility;）では、連続した約物やemdashの詰めが可能です。

#### S-PkPG-HP
括弧等の仮想ボディを550〜650に設定した約物フォント。  
ペアカーニングが有効ではない環境でも、狭く設定された仮想ボディにより、連続した括弧類が詰め、行頭括弧の頭揃が可能です。  
emdashを仮想ボディと同じに設定してあるため、詰めることなく2倍ダーシが可能です。


## 収録字形

「」『』（）｛｝［］〈〉《》〔〕【】、，。．・：；― —


## 使用例

```css
@font-face {
  font-family: "S-PkPG-R";
  src: url("S-PkPG-R.ttf") format('truetype');
}
body{
  text-rendering: optimizeLegibility;
  font-family: S-PkPG-R, 'ヒラギノ角ゴ Pro W3','メイリオ','ＭＳ ゴシック', sans-serif;
}
```

## 更新履歴

#### 2013-1-1 ver.1.002
##### 共通  
horizontalbar, emdash, semicolon.fullwidth, colon.fullwidth, dot-katakanaを追加。  
字形の変更。  
A-Za-zに空白のglyphが設定されていた不具合を修正。  

##### S-PkPG-R
ペアカーニングを修正。

##### S-PkPG-HP-R
文字幅を修正。  
ペアカーニングを修正。