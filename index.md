---
layout: page
title: つくったものりすと
#tagline: Supporting tagline
---
{% include JB/setup %}
Jekyllをまじめに運用してないからアレ

適当に作ったスクリプトとかをのせていくページ

自動login系
----------------------------------------

### [login_eccs.rb](https://gist.github.com/MasWag/4315659)
eccsのLanのログインを自動で行なうtool.rubyのmechanizeがあれば多分動く.文字列操作とかやってないから1.8でも1.9でも動いて幸せ.

### [login_utroam.rb](https://gist.github.com/MasWag/7699888)
utroam版.

git系
----------------------------------------

### [.gitconfig](https://gist.github.com/MasWag/4451236)
.gitconfigの雛形,ssl認証の無視とかあるよ.

### [git-submodule-rm](https://gist.github.com/MasWag/4255594)
gitのsubmoduleを消すスクリプト,gitのsubmoduleを消すのはちょっとめんどくさいからね.

ほどほど便利な子
----------------------------------------

### [send_sms.rb](https://gist.github.com/MasWag/4664969)
AndroidのSL4AでRubyを使って定型smsを送るスクリプト.

### [mkembedpdf](https://gist.github.com/MasWag/5063181)
フォントが埋め込まれてなくて残念なpdfからフォントが埋め込まれたpdfを生成するscript.
TeXが生成したpdf以外で動くかはしらない

### [cancel.sh](https://github.com/MasWag/cancel.sh)
東大前期教養の休講情報のページと検索文字列を比較して,matchしたらgoogle calendarに追加するscript.passwordべたがきよくない.

### [calcgen](https://github.com/MasWag/calcgen)
中1位の計算問題を自動で生成する.たしか出力はLaTeX.

### [Voting-Classes](https://github.com/MasWag/Voting-Classes)
履修状況とかを集めたいときのフォーム.SQLとか使ってない(eccsで使えなかったから)から適切なphpが動けば多分すぐ動く.サーバー内部にcsvで保存している. .htaccessとかちゃんとしないとまずい

なんかバグがあった気がするけどもう覚えてない

おもちゃ
----------------------------------------

### [rand.tcl](https://gist.github.com/MasWag/5434425)
tcl/tkで乱数を生成させてみただけ

### [jpegModifier](https://github.com/MasWag/jpegModifier)
SOIとかEOIとかが破損したけどデータは残ってそうなjpegファイルを復活させる.ぶっちゃけ普通使う機会がない
