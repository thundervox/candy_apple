# Chapter 0 - はじめに
2022年09月18日(執筆開始) - 魔神台風14号が通り過ぎる三連休の日本列島にて


TODO: 過去の没原稿を流用しているため、焦点が定まっていません。あとで書き直すこと。

## Ring について

難しいことを省いてしまうと「汎用プログラミング言語」です。主な特徴として、

 * とにかくすごい。
 * 明瞭である
 * 習得しやすい
 * 理解しやすい
 * 書きやすい
 * 使いやすい
 * すぐに使える
 * 万人向け - 基本的なことは数日～数週間で学び終えることができます。違和感なく理解しやすい文法です。
 * 利便性 - コンパイラの導入、オペレーティングシステムの各種設定(パス)、コマンドプロンプトなど初心者には難しい設定は不要です。
 * 利便性 - コンパイラやパスの設定、コマンドプロンプトなど初心者には難しい設定やツールの使用は不要であり、覚えることも少ないため手軽で扱いやすいです。中級者はインストール直後から本格的なアプリケーションの開発が始められます。
 * 柔軟性 - 好きな書き方やパラダイムを選んでプログラムを組めるようになります。そればかりか言語機能ですら拡張可能です。

上級者は開発したアプリケーションで使うスクリプト言語として組み込んだり、
改造して自分好みの独自言語に仕上げることができます。

それを習得すると一週間後にプログラムが組めるようになるかもしれません。
プログラミングを諦めた人も今度こそ Ring で夢を叶えてみませんか？  私はそのお手伝いをさせていただきます。

初心者向けと侮られがちですが、プログラミング言語を使うのは初心者に限りません。

混沌としすぎた自然言語プログラミングの世界の業界標準となるかもしれません。


## 裏テーマです。
簡単を謳うものに騙され続けてきた皆さんには使いこなすのが難しいかもしれません。
情報弱者を無くすことが日本社会の閉塞感を打ち倒し、あらゆるビジネスの次元を昇化するものだと考えています。

Ring を存じないのは日本国民の99%は存じないものです。簡単を謳うものに騙され続けてきた皆さんには使いこなすのが難しいかもしれません。
スマートフォンもそうですが、簡単にすればするほどスペックが下がって余計にわかりづらく難しくなるんですよね。
加えて安くすればいいと勘違いしているのもどうかと思います。

こんなことを書くと何様のつもりなのか笑うだけのひとがいますけど、笑いたければ笑えばいいだけです。
そんなこんなで書き進めればいいだけです。


## Ring で実現できること

Ringは一風変わったプログラミング言語です。それでいてサクッと開発できます。

手間暇をかければ、実現したいことは、だいたいRingできると思います。

 * 一般的なアプリケーション (業務用、ゲーム、一般)
 * 自然言語プログラミング

## Ring で実現できないこと

## システムプログラミング

オペレーティングシステムやドライバの開発、 GPIO や割り込みなど低水準ハードウェアの操作などはできませんし想定されていません。不可能ではありませんが適材適所です。

## 執筆・解説方針

皆さんがふだんの生活でRingを活用したソフトウェアの開発が流れるようにできることです。
本書はプログラミング言語の入門書です。とは言いましても、他の入門書のようなものとは一味違うものです。
いわゆる詰め込み教育型のダメ理論ではなく、基礎・応用・実践を重きに置いています。

よくあるシギル(おまじない)は徹底的に排除しています。また、図表の多様、文字の大きさをできる限り大きくしています。
さらに物語形式を採用しており、なるべく読み飽きないようにしています。

 * Ring を理解できない人を全員理解できるようにすることです (「わからない」は「みんなわからない」ものです)。
 * 苦さゼロ％のできる限りわかりやすく甘々におねえちゃん並の解説をします。
 * 難しい用語や概念は使わず、和製造語や日常的なできごとに置き換えています。
 * ルビがなをふんだんに使っています。また、漢字の使用率もかなり下げています。
 * 失礼ながら読者は、ものすごく頭が悪かったり勘が鈍いことを自覚している人を想定しています。
 * フォントサイズをかなり大きめにしています。
 * 論拠、参考書、注釈やコラムを多めに記しています。
 * プログラミング教育は人格育成であると考えています。プログラマとして一流であっても人間としては三流ではいつか大きな失敗をしてしまいます。本初でもそのことについて触れる予定です。
 * 厳しいことを言うのは筆者にとって至らないということであるので恥であり、読者さんをがっかりさせることは一生の恥です。
 * 誤字脱字、不明瞭、表現として不快なところがありましたらご遠慮なく Issue までお寄せくださいませ。
 * 本書は筆者を含め人間修養書にしたかったのですが。
 * 各章の冒頭に「理解や読み終えるための所要時間の目安」や「求められる読者の技術水準」を書くとします。例えば「初級、中級、上級」や「一度だけ読む、必要になってから読む、必要不可欠、必携」と大別して、その後に求められる技術のリストや詳細を詳しく書いていきます。 
 * ほかのプログラミング言語の入門書籍にはない極上の体験を提供する。
 * 説明書の読み方はあまり扱われていません。第０章の範囲です。
 * 機能の特徴や実例は紹介には書かず目次欄でしめしてあります。これは、重複を減らすことで利便性を上げるだけではなく紙面の節約や資材費の抑制もかねています。

説明書の改良を目的としています。リングの公式説明書は、必要なことが書いてなかったり、書いてあっても違和感や逃げ出した書き方をしています。これをなんとかしてRingの普及活動への足がかりとするのが今回の目的です。

初学者でも不安や恐怖を感じないよう執筆しました。中級者や上級者にとってもくどくならないよう配慮しています。

Cコンパイラも導入します。そうすることで、いろいろついていてよくわからない感をなくせたらいいと思います。

なにが起きているのかわからなくて怖い人向けです。

概念や機能を目的、構造、用途に分類して評価・解説することで、できる限りの過不足を防ぐことに努めました。

ありきたりな言語解説書では単純に文法の説明や簡単な手本で済ませてしまいます。このせいで用途がわからなかったり、読者が求めているものと異なったり置いてきぼりになったりします。本書では筆者が書きたいことよりも読者が求めることに重きを置いています。必要とあらば歴史や低水準概念についても詳述するようつとめました。

ですから、開発者の性能至上主義の視点ではなく、開発者には絶対に至ることができないエンドユーザの視点から本書を書くことにしました。

また、伝えたいこと、言いたいこと、理解して欲しいことを読者がはっきりわかるよう書くことを心がけました。
さらに、読者にとって「どうでもいいこと」「知りたくもないこと」「無駄なこと」「難しそうなこと」「怖いこと」「危ないこと」を無くすようつとめました。

ちゃんと目標を設定してありますので、挫折しなくていいです。とはいえ、できれば自分でカリキュラムを考えていただきたい。

とはいえ、なんでも聞けば良いと、聞いただけでわかる、聞いただけで自分も同じ事ができると考えている人は相手にはできません。
わからないから聞いているというのはやめてください。つまり、教えて貰って当然だとか態度ばかり大きい残念な人を指します。

とはいえ、中級者にとって本書は地味で退屈かもしれません。
すでにプログラミング経験が十分あると自負している (つまり、公式説明書を一通り読んで理解できる) のでしたら、続刊以降をお読みくださるようお願いいたします。
オブジェクト指向については設計手法の解説は他紙、または続刊以降に譲るものとします。

もちろん、批判や指摘だけではなく、複数の指標を用いてドキュメントの品質をはかることが大事です。


## これまでの Ring
これまで書いてきたとおり、Ringには普及に至る要素や可能性あっても、些細なことが障壁となって普及に至っていません。
今年で Ring は n 年目にさしかかります。しかし、いまだにコミュニティは小規模であり、それに比例して年間で開発されるユーザベースの熱量不足であるため知る人ぞ知るプログラミング言語のままです。

普及していない要因のひとつ。つぎにアラビア語のリスニングができなければ真っ当な資料を探すことができません。入門書は高すぎ問題です。平均的な五大言語のプログラマよくわからないプログラミング言語の入門書にわざわざ学ぼうとはしません。六千円あったら Steam で何本もレトロゲームが買えます。これではホビイストプログラマからも相手にされません。

Ringの魅力を定義できていないこともあったと思いますし、もう少し使いやすさが欲しいウェブサイトや使いづらい分厚いドキュメント、サンプルコードブラウザなど本当に欲しいモノが足りていなかった気がします。

その間、あまり質のよろしくないものをだましだまし使ってきました。それに伴い下積み芸人時代を長く過ごしてきたことを反省するところがあります。

でも、これからは本書がありますので大幅に違います。もはやブレイク寸前の噴火前です。


## Ring のある暮らし (あるいは Ringを学び終えると)
筆者は翻訳者であり、思想家や夢想家ではありません。また、原作者どのは研究者でありプログラマであるため、Ringをどの方向に進めるのか具体的なものを提示していません。
そんなわけで大風呂敷を広げて書いてみますけど。Ringが普及すると社会はどのように進化弥栄していくのでしょうか？

まず考えられるのが、様々なアプリケーションを開発できるようになります。
原理上はオペレーティングシステムを作ることも可能なはずです。


## 本書の構成

 * 初級編
 * 中級編
 * 上級編
 * 人参編
 * 鉄人編
 * 超人編

## Ring の現状
2016年の公開以来、知る人ぞ知るプログラミング言語のままです。

すでに必要とされるものは揃ってはいますが、公式ドキュメントから先へ進めなかったり、サンプルソースの意味を理解できない人もいるかと思います。

Ring を使うことで何ができるのか、本書で解説します。


## その他雑記

家は三度建てないと満足しない。と言います。ならば三回書き直してみるのでドラフト（草稿）は評価用に公開してもいいと考えたからです。

インストール方法とか統合開発環境の使い方だけで済ませてしまう著者の多さには呆れます。
そこからは万年初心者の地獄が待っています。粗製濫造。服部半蔵も吃驚です。

とかく技術書はつまらないものです。実際、書いている方も「わかっていることをいちいち他人にわかるかもしれない書き方で、それっぽくなるようわざとらしく書いている」わけです。そんなわけで「中身のない自称入門書　住所不定本棚」ができてしまうわけです。

初心者ってのは自分で考えられないのではなく、考えるための引き出しがないんです。

コマンドプロンプトの使い方がわからない。インストールでコケる。環境構築で余計なことをしてシステムを破壊するなど、ありえないことをしやがる生き物です。

いきなりGUIプログラミングでは挫折します。
どうして文字列は切り出せるのか？　ファイルとファイルシステムはどうやって動作しているのか？

そういうものが全く理解できない

初心者と中上級者の間にある溝を理解せずに書くからダメなんです。

ＣＭとして筋トレやスクワットを取り入れています。
ただのクエストですが、なぜこういうものを取り入れないのか
プログラマ上がりの技術書書きは自分が初心者であった頃を完全に忘れてしまいがちです。


## 製本版のご案内

現時点では予定していませんが、本邦初の入門書籍（地球では三冊目）となる予定です。

バインダー製本や電子書籍版で増補改訂版を出版するかもしれません。

先行プレビューやドラフト版として本書を公開していますのであまり意味はないと思いますが、
フリーウェア化については絶版から三～五年後とします。

## 執筆機材
大部分の執筆作業は、検証結果をまとめた口述筆記によるものです。

 * Dictadroid Pro
 * CUSTOM TRY (キョーリツコーポレーション) CM-5000U
 * 本書の執筆には KHCoder を使いました。

## 使用許諾条件
Copyright(C)2021-, isVowel All Rights Resreved.

Creative Commons 表示 - 非営利 - 改変禁止 4.0 国際 (CC BY-NC-ND 4.0)
 https://creativecommons.org/licenses/by-nc-nd/4.0/deed.jp

