# TCYL

Google日本語入力のローマ字入力を拡張し、Tの代わりにCを、Yの代わりにLを使えるようにします。

## 導入方法

[tcyl.tsv](tcyl.tsv) をダウンロードし、Google日本語入力の「プロパティ」の「ローマ字テーブル」の「編集」から、このファイルを「インポート」してください。

## 注意点

### C

以下の規則は使えなくなります。

|入力|出力|
|---|---|
|ca|か|
|ci|し|
|cu|く|
|ce|せ|
|co|こ|

代わりに、以下の規則で代替できます。

|入力|出力|
|---|---|
|ka|か|
|si|し|
|ku|く|
|se|せ|
|ko|こ|

### L

以下の規則は使えなくなります。

|入力|出力|
|---|---|
|la|ぁ|
|lu|ぅ|
|le|ぇ|
|lo|ぉ|

代わりに、以下の規則で代替できます。

|入力|出力|
|---|---|
|xa|ぁ|
|xu|ぅ|
|xe|ぇ|
|xo|ぉ|

### T

以下の規則は、Cで代替できません。

|入力|出力|
|---|---|
|tha|てゃ|
|thi|てぃ|
|thu|てゅ|
|the|てぇ|
|tho|てょ|
