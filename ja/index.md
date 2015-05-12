---
layout: page
title: つくったものりすと
lang: ja
#tagline: Supporting tagline
---
{% include JB/setup %}
Jekyllをまじめに運用してないからアレ

適当に作ったスクリプトとかをのせていくページ

日常的に使っている子
--------------------

### [cancel.gs](https://gist.github.com/MasWag/4eadd5aa7c414dd415ad)
ISの休講補講情報を取得してGoogle Calendarに格納するGoogle Apps Script.自前でサーバがなくても動く.

git系
----------------------------------------

### [.gitconfig](https://gist.github.com/MasWag/4451236)
.gitconfigの雛形,ssl認証の無視とかあるよ.

### [git-submodule-rm](https://gist.github.com/MasWag/4255594)
gitのsubmoduleを消すスクリプト,gitのsubmoduleを消すのはちょっとめんどくさいからね.

VHDL周り
--------

### [flycheck-vhdl-ghdl.el](https://gist.github.com/MasWag/4b74f9ac8f1014a73246)
ghdlを用いてVHDLの構文解析をするflycheckのルール。

ほどほど便利な子
----------------------------------------

### [send_sms.rb](https://gist.github.com/MasWag/4664969)
AndroidのSL4AでRubyを使って定型smsを送るスクリプト.

### [mkembedpdf](https://gist.github.com/MasWag/5063181)
フォントが埋め込まれてなくて残念なpdfからフォントが埋め込まれたpdfを生成するscript.
TeXが生成したpdf以外で動くかはしらない

### [calcgen](https://github.com/MasWag/calcgen)
中1位の計算問題を自動で生成する.たしか出力はLaTeX.

### [Voting-Classes](https://github.com/MasWag/Voting-Classes)
履修状況とかを集めたいときのフォーム.SQLとか使ってない(eccsで使えなかったから)から適切なphpが動けば多分すぐ動く.サーバー内部にcsvで保存している. .htaccessとかちゃんとしないとまずい

なんかバグがあった気がするけどもう覚えてない

自動login系
----------------------------------------

### [login_utroam.rb](https://gist.github.com/MasWag/7699888)
utroamのログインを自動で行うtool.ぶっちゃけutroam-1xを使えば良い。

### [login_eccs.rb](https://gist.github.com/MasWag/4315659)
駒場の情報教育棟とかにあるeccsの有線LANのログインを自動で行なうtool.rubyのmechanizeがあれば多分動く.

おもちゃ
----------------------------------------

### [rand.tcl](https://gist.github.com/MasWag/5434425)
tcl/tkで乱数を生成させてみただけ

### [jpegModifier](https://github.com/MasWag/jpegModifier)
SOIとかEOIとかが破損したけどデータは残ってそうなjpegファイルを復活させる.ぶっちゃけ普通使う機会がない

Obsolete
--------

### [cancel.sh](https://github.com/MasWag/cancel.sh)
東大前期教養の休講情報のページと検索文字列を比較して,matchしたらgoogle calendarに追加するscript.pit使ってuser情報を隔離している.
ISブランチは理学部情報科学科の休講情報のページに対応した版

だったのだがrubyのgcalapiがgoogleのAPI変更に対応していないらしく動かないと思う。代わりに[cancel.gs](https://gist.github.com/MasWag/4eadd5aa7c414dd415ad)を作りました。
