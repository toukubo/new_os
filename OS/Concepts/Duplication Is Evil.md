# Duplication Is Evil 
dependency: [Duplication Is Evil principle](https://www.google.co.jp/search?client=safari&rls=en&q=DUPLICATION+i%E2%80%A6&gws_rd=ssl#newwindow=1&q=DUPLICATION+is+evil)
dependencies: Everything in Its right principle,Stock and Flow concepts, Levels and Granularity,

Code duplication is evil, as known in the programmers community, but not only this, all the Workflow Objects should never be duplicated. 

if you follow Everything in Its right principle, it makes easy to avoid duplications. 

You should keep all the Stock information to suitable place. we call it sometimes Repository. 




重複は悪の原則
=================================================================

ソフトウエアの管理における概念ですが、プログラムのコードの重複があるということは邪悪なことである、ひいては、情報が重複することは邪悪なことである、という原理に基づいています。ウェブ、という概念の発明にいたった、ITにおいて最も重要な概念です。全ての情報の重複を無くしていくことによって、管理の効率およびものを情報を探索する効率が劇的に高まり、最大で万倍になると言われています。例えば図書館にある本に書かれた内容は、99.9999%が重複で、無駄であり、これを「一番短い回数読めば済む」ようにするとwebが発明できる。というものです。

情報管理のコスト削減
-----------------------------------------------------------------

-  人が作業をするのに、必要な情報を探索する時間は、全作業における50％ぐらいを占めている。

情報管理が企業管理の最重要課題です。情報管理が一定以上徹底されると、不要になる業務自体も出てきます。

重複を防ぐには
-----------------------------------------------------------------
### 原則
[Everything In Its Right Place 原則](Everything In Its Right Place Principle.md)（ERP原則）->すべてのものをあるべきところに配置すると、おのずと重複はなくなります。
### CoC
今回New OSで参照しているRuby On Rails ではCoC（Convention Over Configuration）「規約をみんなで覚え、それに従うことで、コードを書かなくてよくする」という仕組みを使っています。
### 命名の規約
1. [NamingConventions](../Conventions/NamingConventions.md)
2. [Path記法](../Conventions/RightPlaces/PathNotation.md)
### 配置の規約
1. [Levelのマッピング](../Conventions/Levels.md)
2. [Flow and Stock](../Conventions/Flow and Stock.md)
3. [chat opts](../Conventions/flowdock and chat opts.md) ( ticket -> chat linking )
4. [permalink driven](/OS/Concepts/PermalinkDriven.md)
5. Teamsにマップ（TeamとLevleで絞り込むことで場所はほぼ特定できる）
 


