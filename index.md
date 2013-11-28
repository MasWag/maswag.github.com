---
layout: page
title: つくったものりすと
<!-- tagline: Supporting tagline -->
---
{% include JB/setup %}
Jekyllをまじめに運用してないからアレ

適当に作ったスクリプトとかをのせていくページ

自動login系
====================

[login_eccs.rb](https://gist.github.com/MasWag/4315659)
----------------------------------------
* eccsのLanのログインを自動で行なうtool 
    * rubyのmechanizeがあれば多分動く
    * 文字列操作とかやってないから1.8でも1.9でも動いて幸せ

git系
========================================

[.gitconfig](https://gist.github.com/MasWag/4451236)
----------------------------------------
* .gitconfigの雛形
    * ssl認証の無視とかあるよ

[git-submodule-rm](https://gist.github.com/MasWag/4255594)
----------------------------------------
* gitのsubmoduleを消すスクリプト
    * gitのsubmoduleを消すのはちょっとめんどくさいからね

ほどほど便利な子
========================================

[send_sms.rb](https://gist.github.com/MasWag/4664969)
----------------------------------------
* AndroidのSL4AでRubyを使って定型smsを送るスクリプト

[mkembedpdf](https://gist.github.com/MasWag/5063181)
----------------------------------------
* フォントが埋め込まれてなくて残念なpdfからフォントが埋め込まれたpdfを生成するscript
* TeXが生成したpdf以外で動くかはしらない

[cancel.sh](https://github.com/MasWag/cancel.sh)
----------------------------------------
* 東大前期教養の休講情報のページと検索文字列を比較して,matchしたらgoogle calendarに追加するscript
    * passwordべたがきよくない

[calcgen](https://github.com/MasWag/calcgen)
----------------------------------------
* 中1位の計算問題を自動で生成する
    * たしか出力はLaTeX

[Voting-Classes](https://github.com/MasWag/Voting-Classes)
----------------------------------------
* 履修状況とかを集めたいときのフォーム
    * SQLとか使ってない(eccsで使えなかったから)から適切なphpが動けば多分すぐ動く
    * サーバー内部にcsvで保存している
        * .htaccessとかちゃんとしないとまずい
* なんかバグがあった気がするけどもう覚えてない

おもちゃ
========================================

[rand.tcl](https://gist.github.com/MasWag/5434425)
----------------------------------------
* tcl/tkで乱数を生成させてみただけ

[jpegModifier](https://github.com/MasWag/jpegModifier)
----------------------------------------
* SOIとかEOIとかが破損したけどデータは残ってそうなjpegファイルを復活させる
    * 普通使う機会がない

<!--
Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.

-->
