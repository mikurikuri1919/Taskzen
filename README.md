# Todo-For-7Habits

## サービス概要
達成した目標に集中できない人々を支援するために、
自分にとって今最も重要なことだけを管理するToDoアプリです。
このアプリは、自分にとって最も重要なことだけを効果的に管理し、目標に向けて集中力を高める手助けをします。

## 想定されるユーザー層
日々の忙しさの中で、本当にやりたいことをできていない人

## サービスコンセプト
私は社会人2年目でSler業界で働いています。まだ2年目とはいえ、業務は基本的に忙しいです。そんな中で、自分のやりたいこととのギャップを感じ、転職を考えています。そのため、RUNTEQというプログラミングスクールに通い、Web系企業への転職を目指し、仕事の合間を縫って学習しています。しかし、仕事をしながらの学習は中々ハードで、時には疲れ果てて、Youtubeやテレビを見たりなど、ダラダラしてしまうことがあります。もちろん、本当に疲れたときは心身を休めることも大切だと思います。しかし、そればかりでは自分の目標から遠ざかるだけです。自分にとって今最も重要なことに時間を充てることが、目標達成への近道だと感じています。今の私にとって、それはWeb系企業へ転職するための学習です。現代のような様々な誘惑が身近にある中で意思の力だけで、それをしっかりと認識し、注力し続けるのは困難だと思います。そのため、自分にとって今最も重要なことが何かを認識し、それに集中できるアプリを作りたいと思いました。
<br>
<br>
※この考え方は、スティーブン・R・コヴィーの「7つの習慣」の第3の習慣、「最優先事項を優先する」にインスパイアされています。

## 実装を予定している機能
### MVP
* トップページ
* アンケートページ
* 会員登録・ログイン
* アンケート結果ページ
* ドキュメントページ
* ToDo一覧
* それぞれのToDoの位置がわかる機能
* ToDo投稿
* ToDo詳細
* デフォルトToDo機能（事前に登録しておく）
* プロフィール設定ページ
* 管理者ページ
* LINE通知機能（1週間に一度）

### その後の機能
* ToDo達成率の算出機能
* ToDo達成率のグラフ、レポート化
* 算出した達成率でランキングを表示
* ToDo達成後のボーナス機能
* 共有機能（OGP）
* レコメンド機能
* 利用規約
* プライバシーポリシー

## 主な使用技術
### フロントエンド
* Next.js 13.4.19
* React 18.2.0
* TypeScript 5.2.2
* TailwindCSS 3.3.3

### バックエンド
* Rails（APIモード） 7.0.8
* ruby 3.1.2
* PostgreSQL

### インフラ
* Vercel
* Heroku

### その他
* Firebase Authentication