


RESTful,Rails,Conventions,ResourceBase,DomainDriven,Basecamp,Tickets as Resource,and Routes.
---------------

dependency: RESTful, modern software frameworks's convention patterns. 
our teaming, report lines, push and specs information is all using "RESTful" concepts. 

APIの概念、ソースコード、関連情報の見つけ方、作業の仕方、人の見つけ方　について書かれています。

## 概念
For example. go ( following the Routes ) Our Basecamp To-do lists holds everything for the resource. if you are going to work for "User" resource, then you will find specs in Todo list found under your project -> todo lists with "User" [POST] todo list. 
everything is named and set so. 

 該当するようなものや Basecampのアクションに該当するようなものがあります。 その配下に、それを達成するた めのテストケースやチケットが割り当てられています。 

## ソースコード
基本的にはモジュールかリソースで、この下にアクション、コントローラーが居る事で、AngularもRuby On Railsも全部持っていると思うので、はい。

## 関連情報の見つけ方(Routes)
remember RESTful. naming convention. you have to be able to find the todo lists for this. 

## ワークフロー
- プロジェクトのフロントエンドとかワークフローになっていますが、 "箱に入れて次の工程にタスクを運んでいく"

- 一般的な開発、要件定義から外部仕様、 いわゆるどの画面でどのデータを埋めるのか、どのデータを出すのかという要素等の仕様と、 ワイヤフレーム（wireframe）：全体的にはこの画面ではこういう風な配分のボタンを置こう、など、 DRIに近いチームとして、デザイン、その後にデザインのレスポンスを。もうRESTセーブな、インテグレーションセーブなデザインと修正とがあります。 

## 修正・テストフロー的な全ての作業
- 修正、テスト係数のチケットと、またその修正とで、画面すら存在しない場合には、アクセスしてみると画面がないというテスト係数が別途になっているみたいな状態になると思います。
-  テスト係数と言っても実際にはテストコードを、テストコードではなくDYなので、ここでは人間が行うテスト係数という事になっています。なっておりますという基準があると思います。 それは画面、RESTベースなアクションなど（そのモデルを埋める為のもの）、の配下に配置されているはずです。
-  既にモジュールベースでバッファーに今あると思います。

## ブランチングルールに関して
インフラの箇所に記載されている通りです。

## 作業の仕方
### フロントエンドに関して
- リリーサーはディレクターのVitaliy Kirpelさん 
- コミットしてBasecampにそのチケットの完了を報告してください（URLを貼ること）
### サーバサイドの場合
- ディベロップメント関係：2個のブランチがいて、Gateway関係とユーザー、それ以外となっています。そいつから、ディベロップメントでチェックシートとかに自動的に配置されています。 
- 全部のURL叩いて試験もしてみてください。
- Basecampに報告してください
## 人の見つけ方
### 開発
開発の直接的な([Vertical]な)指示についてはその同じチームに居る人に聞いて頂ければOKです
### 開発以外
例えば、事務的な事、契約関係、タイムカードについて、権限を与えてもらう、翻訳してください　など 全て1回このメールアドレスに依頼をかけてみてください。ここには沢山の事務スタッフの人たちが作業を待っていてくださっている状態です。 


   [Vertical]:https://github.com/toukubo/new_os/blob/1d420f4bec611b0fcf914904890e597809d7…
