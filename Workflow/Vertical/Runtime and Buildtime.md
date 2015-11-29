Runtime / Buildtime
=================================================================
- Runtime（実行時）はビルトタイム（設計）と対になっている概念。
  - Runtime：工場
  - Build：ランタイム==工場を設計し、建築すること。
- [Line and Staff](Line and Staff.md)も参照


関連する命名規則とRightPlaces
-----------------------------------------------------------------
例：Manualization プロジェクト
Manualizationにこれに対応し、頭にとBuildとつけた Build Manualization というプロジェクトが存在する場合、前者はRuntimeで、後者はBuildtimeです。

Manualization は manualを作ることをゴールとしたプロジェクトで、後者は「manualを作る工程自体を作る」をゴールとしたプロジェクトです。メタである、ということです。

Todo やファイル連絡などの正しい場所が、Runtime である Manualization に入るのか、BuildTime である Build Manualization に入るのかの識別をしてください。

ランタイムの Workflow を通り抜けていけるTodo以外はRuntime Workflow には入れないようにしましょう。

関連する言葉として「[Kaizen](/Workflow/Vertical/Kaizen.md)」という用語があります。
1. Runtimeに対し、Build は、「メタ」な関係性にあります。Kaizenもまた、Runtimeに対し、メタな関係性にあります。
2. Build と Kaizenの差はビルドタイムは一番最初にワークフローを構築する。Kaizenは一度走り始めているランタイムを改良する（問題を見つけたり、見つかった問題を格納して、それにタスクを実行していく）という別です。

manualizationの例であれば、時系列的には、 Build Manualizationが作られ、Manualizationの工程がその成果として作られ、が生み出されるようになると Build Manualizationは完了し、閉じられます。その後でManualizationの工程に問題がある場合は、Kaizen Manualizationが作られ、そこで議論sだれます。


ハッシュタグで #Runtime とつけておくことも有用です。
