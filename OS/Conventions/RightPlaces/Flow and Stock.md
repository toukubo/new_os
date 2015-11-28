# Flow and Stock 

## Stock
The information that is reerences many times, but not heavily changed. it’s master ( to transactional data ) in our Workflow Objects. 

It is a general background information about the specific project for reading purposes. Stock concept doesn’t have a time reference.

### granularity
bigger. higher level information. 
### examples
 like project level, meta-project level, conventional level, etc.

## Flow
refers to the to dos information.Information about a single task to clarify and bring to execution. 
- It has a time reference e.g. gives the values over a period of time.
### granularity
smaller. lower level information
### examples
1. Conversations in chat tools,
2. comments
3. Todos
4. Todo-lists

Should store the Objects on right place following this principle.











フローとストック
=========

ストック
--------

### ストックと参照回数
- ストックは何度も参照される情報です。
- 少なくても5回以上は参照されるような情報は全てストックとみなされます。2回以上参照される情報は基本的にストック情報と見なしてください。
- 10回、20回、30回と参照される可能性のある情報は、よりストック性の高い情報として見なしてください。

このストック性参照回数という概念によって、流動が変わってきます。流動と一致している概念ということになります。

### プロジェクトディスクリプション
別途、basecamp上の情報流動に関しては
- プロジェクト
- to do list
- to do

という別があり、それぞれに対して適切な記述があり、次のよう決められています。
- プロジェクトデスクリプションはプロジェクトに関しての記述
- to do list レベルの情報はto do list のコメントに記述
- to doに関しての情報はto doのコメントやto doのオプショナルの(xxx)に記述

### フローとストックの分類
そちら参照することになっていますが、その様に
 1. 参照回数
 2. 情報の流動
 
の2つの観点で情報をフローとストックに分けて保存していく必要があります。
コメントの中で何度も、コメントつまりフローとなる情報の中から何度も参照されることになるような情報というのが発生した時に、主にこのストック情報としてこれをキャプチャーしておいてくださいといったやり取りがなされます。

### 例
プロジェクトレベルのプロジェクトデスクリプション。
メタプロジェクトレベル。つまり会社の一般的な情報及び規約的な情報等はストック情報とされています。
このストックアンドフロー等のコンベンション規約の情報もこうした形で抜粋され、こちら(xxx)ハブのほうに移動されているということになります。

フロー（流れる情報）
-------------------

### フローの定義
これは一つ一つのタスクやチャット等でやり取りされるような流動の情報になります。

#### difference
- ほぼタスクの実行が終わったら、捨て去られる情報なので1回から3回程度
- 情報のサイズとしても比較的小さいものとなります。

ストックとフローと例
--------------------

### 対話、会話的なる情報およびチャットの中に入っている情報
- 基本的に参照回数は低いのでフロー性のある情報
- その中でも参照回数の多いものに関して、あるいは長期的に有効な決め事等はストック情報とみなされる

### コメントやto do、及びto do list
- 比較的フロー性が高い情報とみなされます。
- これはeverything全てのもの、あるべきところにあるべきという原則に基づいて、適切な箇所に移動される必要があり、to do コメント等でそうした情報があった場合にはこれは重要な情報なのでといって、そこから移動してください。 
