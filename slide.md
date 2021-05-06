## Omotesando.rb #62

- - -

## るりまに対する貢献活動記録

---

#### 自己紹介
- - -

* 名前：osyo
* Twitter : [@pink_bangbi](https://twitter.com/pink_bangbi)
* github  : [osyo-manga](https://github.com/osyo-manga)
* ブログ  : [Secret Garden(Instrumental)](http://secret-garden.hatenablog.com)
* [趣味で気になった bugs.ruby のチケットをブログにまとめてる](https://secret-garden.hatenablog.com/archive/category/bugs.ruby)               <!-- .element: class="fragment" -->
* 最近はるりまにめっちゃ PR 投げてる                   <!-- .element: class="fragment" -->
    * [ここ1ヶ月で20個ぐらい PR 投げてる](https://github.com/rurema/doctree/pulls?q=is%3Apr+author%3Aosyo-manga)
* Kaigi on Rails                 <!-- .element: class="fragment" -->
    * [ActiveRecord の歩み方](https://speakerdeck.com/osyo/activerecord-falsebu-mifang)
* 銀座Rails                   <!-- .element: class="fragment" -->
    * [これからの Ruby と今の Ruby について](https://speakerdeck.com/osyo/korekarafalse-ruby-tojin-false-ruby-nituite)
    * [12月25日にリリースされる Ruby 3.0 に備えよう！](https://speakerdeck.com/osyo/12yue-25ri-niririsusareru-ruby-3-dot-0-nibei-eyou)
* BuriKaigi2021                 <!-- .element: class="fragment" -->
    * [Ruby 2.0 から Ruby 3.0 を駆け足で振り返る](https://speakerdeck.com/osyo/ruby-2-dot-0-kara-ruby-3-dot-0-woqu-kezu-dezhen-rifan-ru)

---

## るりまに対する貢献活動記録

---

#### るりまとは
- - -

- 日本語の Ruby のリファレンスサイト
    - [Ruby リファレンスマニュアル](https://docs.ruby-lang.org/ja/latest/doc/index.html) という
- Ruby の組み込みライブラリや標準ライブラリのリファレンスが記述されている
    - [class String](https://docs.ruby-lang.org/ja/latest/class/String.html)
    - [class Array](https://docs.ruby-lang.org/ja/latest/class/Array.html)
- Ruby 書いている人はだいたいお世話になっているはず

---

#### るりまの中身
- - -

- リポジトリ：[rurema/doctree](https://github.com/rurema/doctree)
- チュートリアル：[Tutorial](https://github.com/rurema/doctree/wiki/Tutorial)
- ファイル形式：rd ファイル
    - [ReferenceManualFormatDigest](https://github.com/rurema/doctree/wiki/ReferenceManualFormatDigest)
    - [RD でも書いてみようか 【第 1 回】 ブロックレベル](https://magazine.rubyist.net/articles/0006/0006-RDIntro.html)
- ビルドツール：[BitClust](https://github.com/rurema/doctree/wiki/BitClust)
    - これを使って rd ファイルを HTML 形式に変換したりローカルでるりまを立ち上げたりする

---

#### どういう活動をしているのか
- - -

* るりまに載ってるサンプルコードはハイライトされてたりされていなかったりする
* これのサンプルコードにハイライトを付ける作業をしている
* 基本的には以下のように書き換えるだけ
    * 例：https://github.com/rurema/doctree/pull/2551

```diff
-   dog = Struct.new("Dog", :name, :age)
-   fred = dog.new("fred", 5)
-   fred.age = 6
-   printf "name:%s age:%d", fred.name, fred.age
-   #=> "name:fred age:6" を出力します
+ #@samplecode 例
+ dog = Struct.new("Dog", :name, :age)
+ fred = dog.new("fred", 5)
+ fred.age = 6
+ printf "name:%s age:%d", fred.name, fred.age
+ #=> "name:fred age:6" を出力します
+ #@end
```

---

## デモ

---


#### まとめ
- - -

- こんな感じでるりまに貢献している
- チュートリアルなどかなり詳しく書いてあるので慣れると修正自体はそこまで大変ではない
- コミットや PR のコミュニケーションは日本語なので最初に触る OSS としては比較的ハードルが低い
- ドキュメントサイトは間違えても世界が終わるわけではないのでどんどん PR を投げていこう


---

#### 参照

* [Rubyリファレンスマニュアルを修正する方法 - いまブログ](https://imaizumimr.hatenablog.com/entry/2020/12/02/235121)

---

### ご清聴
### ありがとうございました

