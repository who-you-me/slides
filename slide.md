# 負債を解消する
## アジャイル編

by Hisao Soyama ([@who_you_me](https://twitter.com/who_you_me))

---

# お前誰よ

- 祖山 寿雄(Hisao Soyama)
 - [Twitter](https://twitter.com/who_you_me)
 - [GitHub](https://github.com/who-you-me)
 - [Qiita](http://qiita.com/who_you_me)
- 株式会社ハウテレビジョン所属
- スタートアップなので必然的にフルスタックにならざるを得ないエンジニア

---

# はじめに

---

# お陰様で急成長を迎えた外資就活ドットコム

- 2人→10人以上のエンジニアチームに
- 営業、事務などエンジニア以外のメンバーも増加

---

# なにがおこるか

---

# 暗黙知の山

- チームが拡大すると、阿吽の呼吸が通用しなくなる

「ここってどういう仕様になってるんだっけ？」  
「◯◯さんに聞かないとわからない。。。」
<!-- .element: class="fragment" data-fragment-index="1" -->

「ここってどうなってるんですか？」  
「あれ、どうだったかな。。。」
<!-- .element: class="fragment" data-fragment-index="2" -->

## 本人も覚えてない！！！
<!-- .element: class="fragment" data-fragment-index="3" -->

---

# 炎上するプロジェクト

- 開発のボリュームが急拡大し、見通しが建てられなくなる

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

---

# なにがいけなかったのか

- 皆さん、考えてみましょう

---

# 答え

---

# なにもいけなくない！

- 当たり前のこと
- 2人で、しかも対面での開発
 - 仕様書書きますか？ <!-- .element: class="fragment" data-fragment-index="1" -->
 - Redmineでプロジェクト管理しますか管理しますか？ <!-- .element: class="fragment" data-fragment-index="2" -->
 - わざわざMTGセッティングしますか？ <!-- .element: class="fragment" data-fragment-index="3" -->

---

- こんなんあったらよくね？ <!-- .element: class="fragment" data-fragment-index="1" -->
- いいねつくろう！ <!-- .element: class="fragment" data-fragment-index="2" -->
- うおーーーテンション上がってきた <!-- .element: class="fragment" data-fragment-index="3" -->
- 完成！ <!-- .element: class="fragment" data-fragment-index="4" -->
  - この繰り返し <!-- .element: class="fragment" data-fragment-index="5" -->
- ウォータフォールもアジャイルもない <!-- .element: class="fragment" data-fragment-index="6" -->
- 四の五の考えてる暇があったら早く作るべき <!-- .element: class="fragment" data-fragment-index="7" -->

---

# だけど、ずっとそれじゃいけない

- シードステージ、アーリーステージからミドルステージに移行する時に、壁にぶつかる
- それが祖山がジョインした時だった

---

# なにをやったのか

- スクラムの導入による開発プロセスの改善

![スクラム](http://upload.wikimedia.org/wikipedia/commons/1/1a/ST_vs_Gloucester_-_Match_-_23.JPG)

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

- 「次のプロジェクトからスクラムでやろう」なんて余裕はないことが多い <!-- .element: class="fragment" data-fragment-index="1" -->
 - 問題山積みで、早く何とかしないとﾀﾋぬ <!-- .element: class="fragment" data-fragment-index="2" -->

---

# 必要なこと、すぐにできそうなことからやろう

- 幸い、プロセス面に関することでは技術面と違い、Yakの毛を延ばさくてもいい（ことが多い）
 - 中途半端に「chefやろう」「Vagrantやろう」とすると後に負債になり得る
 - 中途半端にスクラムやっても負債にはならない
  - 駄目ならすぐやめればいい
- 「うまくいかなかったね。。」で終わってしまい、以後スクラムを取り入れにくくなるリスクはある

---

# 具体的になにをやったか

- 取り入れた順番にご紹介

---

# デイリースクラム

- チームが大きくなり、notフルタイムやインターンも増えたため、各自の進捗が把握しづらくなっていた
- 「昨日やったこと」「今日やること」「困っていること」を報告するオーソドックスなやり方

---

画像1

---

画像2

---

# スプリント計画

- 2週間に一度のタイミングで、このスプリントに実装するフィーチャを洗い出し、見積もる
- あまりうまくいかなかった
 - 1つのプロジェクトにチーム全員で挑む、という形にはなっていない
  - サービスの開発をする人がいれば、開発環境の整備をする人がいたり、コーポレートサイトを作る人がいたり
   - 誰がどれを開発するかは事前にほぼ決まっている
  - そのため、全員揃っての見積もりなどをやる意味があまりない
- 今は、ある機能を開発するメンバー＋リーダーだけで、案件ごとに見積もりを行っている

---

# アジャイルなタスク管理

- PivotalTracker

---

画像

---

- ストーリー名を統一する
 - 「＜誰＞として、＜何＞を＜どう＞できる」
- レビュータイミングを予め決めておく
- PivotalTracker以外では管理しない
 - QiitaとかGoogle Docsに「FB書いといたから直しといて」だと情報が分散して混乱する

---

# ふりかえり（レトロスペクティブ）

- KPTT
- 2週間に1回

---

写真

---

# アジャイルな見積もり

- プランニングポーカー

---

# どうなったか

---

# まとめ

---

# Wanted!!
