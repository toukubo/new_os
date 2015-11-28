# Duplication Is Evil 
dependency: [Duplication Is Evil principle](https://www.google.co.jp/search?client=safari&rls=en&q=DUPLICATION+i%E2%80%A6&gws_rd=ssl#newwindow=1&q=DUPLICATION+is+evil)
dependencies: Everything in Its right principle,Stock and Flow concepts, Levels and Granularity,

Code duplication is evil, as known in the programmers community, but not only this, all the Workflow Objects should never be duplicated. 

if you follow Everything in Its right principle, it makes easy to avoid duplications. 

You should keep all the Stock information to suitable place. we call it sometimes Repository. 


重複は悪の原則
==============

概念
----
文字通りファイルの管理において、ソフトウエアの管理における概念ですが、プログラム行動の重複等があるということは邪悪なことであるという原理に基づいています。全ての情報の重複を無くしていくことによって、管理の効率およびものを情報を探索する効率が劇的に高まり、最大で100倍になると言われています。

情報管理のコスト削減
--------------------
100倍というのは非常に意識されにくいコストであるのですが、以下のような数値があります。

- 探索する時間は全ての作業における50％ぐらいを占めているという統計がある
- 50％の費用が削減されるということは、会社の費用が50％削減される

つまり情報管理というのは致命的に企業の管理において最も重要と言えます。情報管理が徹底されている場合には、人員やあるいは作業そのものが不要になるという傾向があります。

我々の目的
----------
今回我々が参照しているルビーオンレールスという技術は、これはある概念を利用することによって COC（Convention Over Configuration）規約を設定よりも優先させるというルールで、次の仕組みを使っています

- 規約を全体的に提供させる
- それを知っている人であれば情報がどこにあるのか、どのような(行動？)が書かれるべきなのかが明らかになる

それにより非常に高度な情報管理ができるようになるであろうというのが、我々が行おうとしているものです。

重複を防ぐには
--------------
ここでは全てのファイルがあるべきところにあるという原則に徹底すると、全てのファイルの重複を防ぐことができるという(タイド？)に至っています。

### フローとストック
以下の手順に従い、フローとストックに分類することによっても重複を防ぐことができます。

1. 情報の流動や参照回数によって、フロー情報とストック情報に分類する
2. ストック的な情報とフロー的な情報をそうした箇所に分ける

### 多数参照される情報に関して
- 再びタイピングして情報書くことはしない
- パーマリンクに必ずなっていて、それを検索し見つけそのリンクを提示するということだけで済むようにするべきである 


