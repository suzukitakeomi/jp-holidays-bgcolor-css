# jp-holidays-bgcolor-css
日本の祝日に背景色を付けるCSS

```html
<link media="all" rel="stylesheet" href="//suzukitakeomi.github.io/jp-holidays-bgcolor-css/holidays_bgcolor01.css" />
```
```html
<h3>2025年1月</h3>
<table>
<tr id="d20250101"><td>1</td><td>水</td><td>元旦</td></tr>
<tr id="d20250102"><td>2</td><td>木</td><td>その他</td></tr>
<tr id="d20250103"><td>3</td><td>金</td><td>その他</td></tr>
...
</table>
```

背景色は#fff0f5を指定しています。

idに「d」+「yyyymmdd形式の日付」を指定して使用します。
指定された日が祝日であれば、背景色が付きます。

2026年までのデータを登録しています。
年毎の分離も予定しています。

データ取得元は以下のデジタル庁公開データ(e-Govデータポータルのデータセット)です。  
[「国民の祝日」について | 昭和30年（1955年）から令和2年（2020年）国民の祝日等（いわゆる振替休日等を含む）（csv形式：19KB） | e-Govデータポータル](https://data.e-gov.go.jp/data/dataset/cao_20190522_0002)
