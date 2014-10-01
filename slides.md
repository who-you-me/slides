# 負債を解消する<br />（アジャイル編）

by Hisao Soyama ([@who_you_me](https://twitter.com/who_you_me))

---

## お前誰よ

- 祖山 寿雄(Hisao Soyama)
    - [Twitter](https://twitter.com/who_you_me)
    - [GitHub](https://github.com/who-you-me)
    - [Qiita](http://qiita.com/who_you_me)
        - ぜんぶ@who_you_me
- 株式会社ハウテレビジョン所属
- スタートアップなので必然的にフルスタックにならざるを得ない系エンジニア

---

## お前誰よ

- 何故か社会学の修士号を所持
    - テキストマイニングやネットワーク分析をやってた
- 新卒で某ISPに入社（2012年）
    - 全く未経験のネットワークエンジニアになる
    - インフラエンジニアのつらみを味わう
- コードが書きたいのでハウテレビジョンに入社
    - 2014年4月

---

# はじめに

---

## 急成長を遂げた外資就活ドットコム

- 2人→8人以上のエンジニアチームに
- 営業、事務などエンジニア以外のメンバーも増加

---

# なにがおこったか

---

## 暗黙知の山

- チームが拡大し、阿吽の呼吸では回らなくなる

「ここってどういう仕様になってるんだっけ？」  
「◯◯さんに聞かないとわからない…」
<!-- .element: class="fragment" data-fragment-index="1" -->

本人登場
<!-- .element: class="fragment" data-fragment-index="2" -->

「ここってどうなってるんですか？」  
「あれ、どうだったかな…」
<!-- .element: class="fragment" data-fragment-index="3" -->

# 本人も覚えてない！！！
<!-- .element: class="fragment" data-fragment-index="4" style="background-color:white;"-->

---

## 炎上するプロジェクト

- 開発のボリュームが急拡大し、パンクする

「これいつまでに終わるの？」  
「うーん、これぐらいかな（適当」
<!-- .element: class="fragment" data-fragment-index="1" -->

どう見ても間に合わなそう
<!-- .element: class="fragment" data-fragment-index="2" -->

「これ終わるの？　進捗何％ぐらい？」
<!-- .element: class="fragment" data-fragment-index="3" -->

「……」
<!-- .element: class="fragment" data-fragment-index="4" -->

「し、死んでる！？」
<!-- .element: class="fragment" data-fragment-index="5" -->

# ＿人人 人人＿<br />＞ 突然の死 ＜<br />￣Y^Y^Y^Y￣
<!-- .element: class="fragment" data-fragment-index="6" style="background-color:white;" -->

---

# 死んでません

念のため…

---

## なにがいけなかったのか

- 皆さん、考えてみましょう

---

# 答

---

# なにもいけなくない！

---

## なにもいけなくない！

- 当たり前のこと
- 2人で、しかも対面での開発
    - 仕様書書きますか？ <!-- .element: class="fragment" data-fragment-index="1" -->
    - Redmineとかツール使ってプロジェクト管理しますか？ <!-- .element: class="fragment" data-fragment-index="2" -->
    - わざわざMTGセッティングしますか？ <!-- .element: class="fragment" data-fragment-index="3" -->

---

- こんなんあったらよくね？
- いいねつくろう！ <!-- .element: class="fragment" data-fragment-index="1" -->
- うおーーーテンション上がってきた <!-- .element: class="fragment" data-fragment-index="2" -->
- 完成！ <!-- .element: class="fragment" data-fragment-index="3" -->
    - この繰り返し <!-- .element: class="fragment" data-fragment-index="4" -->
- ウォーターフォールもアジャイルもない。四の五の考えてる暇があったら早く作るべき <!-- .element: class="fragment" data-fragment-index="5" -->

---

## だけど、ずっとそれじゃいけない

- スターアップが成功して、ビジネス的に1つステップを超えた時、壁にぶつかる
- それが私がジョインした時でした

---

# 当時の私のスペック

---

- もともとPythonista
- ネットワークエンジニアを1年ほど
    - 1行もコードを書かない
    - Ciscoのコマンドならアホほど叩いた
- チーム開発？　あーそれ研修でやったわ
    - 5人チームで1ヶ月
    - スクラムでやった
- その後、先輩に誘われて「スクラムを広めよう」みたいなワークグループに入ってた
    - スクラムの何たるかはそこで知った

---

仕事でコードを書きまくれる！　と胸を踊らせて入社したら、現場は絶賛炎上中！！！！

- 5/1に大規模なリニューアルがあるらしい
- 終わりそうにない
- ヤバい、どのくらいヤバいのかっていうと、「どのくらいヤバいのか」すら把握できないほどヤバい

---

# これはどこかで聞いた話だぞ…

---

# ということで

---

# Let's Scrum <!-- .element: style="background-color:white;" -->

![スクラム](http://upload.wikimedia.org/wikipedia/commons/1/1a/ST_vs_Gloucester_-_Match_-_23.JPG)
<!-- .element: style="width:2000px; height:800px; " -->

---

# 本題に入る前に

---

# 大事な前提

---

- リリース計画
- スプリント計画
- デイリースクラム
- スプリントレビュー
- レトロスペクティブ
- アジャイルな見積もり
- ベロシティの計測
- かんばん
- etc...

---

# 全部やらなくていい

---

## 全部やらなくていい

- 「次のプロジェクトからスクラムでやろう」なんて余裕はない
    - 問題山積みで、早く何とかしないとﾀﾋぬ
- 必要なこと、すぐにできそうなことからやろう

---

- 幸い、プロセス面に関しては技術面と違い、Yakの毛を延ばさくてもいい（ことが多い）
    - 中途半端に「chefやろう」「Vagrantやろう」とすると後に負債になり得る
    - 中途半端にスクラムやっても負債にはならない
        - 駄目ならすぐやめればいい
    - 「うまくいかなかったね…」で終わってしまい、以後スクラムを取り入れにくくなるリスクはある

---

## 具体的になにをやったか

- 取り入れた順番にご紹介

---

## デイリースクラム

- これはCTOが始めた
- チームが大きくなり、フリーランスやインターンも増えたため、各自の進捗が把握しづらくなっていた
- 「昨日やったこと」「今日やること」「困っていること」を報告するオーソドックスなやり方

---

画像1

---

![デイリースクラム](img/daily.jpg)

---

## スプリント計画

- 「どの順番で、いつ、何ができるのか」が把握できなくなっていた
- 2週間に一度のタイミングで、このスプリントに実装するフィーチャを洗い出し、見積もる

---

## スプリント計画

- 教科書的なやり方はフィットしなかった
    - アジャイルなチームは機能横断的
    - とはいえ、エンジニア数人のスタートアップでは、どうしても各自やることがバラバラになる
        - サービス開発する人、バグ直す人、開発環境整備する人、など
    - そのため、全員揃って見積もりをする意味があまりない

---

## スプリント計画

- 1機能ごとに1〜2人のミニチームのような形になり、そのメンバーで見積もり
- 「スプリント」も特に設けていない
    - 「自社サービスだと延々と切れ目なく開発続くから、2週間毎にがっつり計画し続けるのはしんどいよね」的なことを@naoya_itoがどこかで言ってた（気がする）
- 「優先順位をつけ、上から順に開発する」という原則は生きている

---

## アジャイルなタスク管理

- アジャイルな開発にはアジャイルなツールが必要
- PivotalTrackerを採用
    - 決め手はシンプルさ
    - Redmineは入れるのが面倒なのと、機能が豊富すぎる

---

![PivotalTracker](img/PivotalTracker.png)

---

## アジャイルなタスク管理

- 「開発フローに合わせてツールをカスタマイズする」のではなく、「開発フローをツールに合わせる」ことが大事
- PivotalTrackerはシンプルで、カスタマイズはあまりできない
- 裏を返せば「PivotalTrackerに開発フローを合わせることで、自然とスクラムになる」ということ
    - 管理ツールも「レールに乗る」という発想

---

## ふりかえり（レトロスペクティブ）

- KPTT
- 2週間に1回
- Keep, Problem, Tryを出していき、次のサイクルで行うこと（ToDo）を決める

---

![KPTT](img/KPTT.jpg)

---

## ふりかえり（レトロスペクティブ）

- 課題が可視化される
- 定期的に開催されることで、課題が放置されない

![進捗どうですか](https://d3j5vwomefv46c.cloudfront.net/photos/large/811266413.png?1380205345)
<!-- .element: class="fragment" data-fragment-index="1" -->

---

## アジャイルな見積もり

- プランニングポーカー
- PivotalTrackerの個々のストーリーよりも大きな単位で見積もる
    - 「○○機能の実装」とか
- フィボナッチ数で相対見積もり

~~~haskell
fib = 0 : 1 : zipWith (+) fib (tail fib)
~~~

---

## アジャイルな見積もり

- 見積もりは大変
- いつの間にか実装の詳細に踏み込んでしまい、長引くことが多い
- 消耗する
- 終わったら飲みに行く空気になることが多い

---

## どうなったか

---

## まとめ
