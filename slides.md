---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/4MxD-wt9cas
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  XP祭り2022 での発表資料
# persist drawings in exports and build
drawings:
  persist: false
fonts:
  sans: 'M PLUS 1'
  serif: 'Zen Antique Soft'
  mono: 'Source Code Pro'
---

# これが私のXP
## 〜 eXtreme Punning 〜 変化をウケろ

Tatsuya Sato (satoryu)

2022-10-01 XP祭り2022

<BottomRightCaption>

  Photo by [Гоар Авдалян](https://unsplash.com/@avdalyan?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/humor?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

</BottomRightCaption>

---
layout: section
---

# 「で、お前誰よ？」

自己紹介

---
layout: image-left
image: /satoryu.jpeg
---

# さとうたつや

プログラマー。

- GitHub: [@satoryu](https://github.com/satoryu)
- Twitter: [@sato_ryu](https://twitter.com/sato_ryu)

## 趣味

- [BABYMETAL](https://babymetal.com/)
- [武藤彩未](http://ayamimuto.com/)
- アリの飼育
- 駄洒落

---
layout: iframe-right
url: https://www.satoryu.com/business/
---

# 個人事業主をしています。

- Webアプリケーションの開発
- プログラミング学習の支援

具体的でなくてもいいので、何か話をしてみたいと思ったらお気軽にご連絡ください！

---

# Silver Bullet Club所属

Silver Bullet Clubというエンジニアチームに所属しています。

![Silver Bullet Clubロゴ](/silverbulletclub_banner.png)

---
layout: iframe
url: https://hololab.co.jp/
---

[![](https://hololab.co.jp/assets/img/common/logo.svg)](https://hololab.co.jp/)

---
layout: image-right
image: /ants.jpeg
---

# アリの飼育

女王アリを捕まえて、育てています。

- クロヤマアリ
- トビイロシワアリ
- キイロシリアゲアリ

クロオオアリを捕まえたい。

---
layout: image-right
image: /dajare-bot.png
---

# 駄洒落

- 趣味で駄洒落をつぶやいたり
- 駄洒落を生成するボットを作ったり


---
layout: section
---

# 本日伝えたいこと

---
layout: image-right
image: https://source.unsplash.com/P5MXtYfgmmw
---

# もっとチームに笑いを

<BottomRightCaption>

Photo by <a href="https://unsplash.com/@nate_dumlao?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Nathan Dumlao</a> on <a href="https://unsplash.com/s/photos/laughing-people?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

</BottomRightCaption>

---
layout: section
---

# 「笑い」とは

---

## 笑いを生み出す理論

- 優越理論
- 緊張緩和理論
- 不調和理論

---

# 優越理論

- 笑う人が笑われる人よりも何かで優位であることがわかった時に発生する笑い
- 例えば
  - 誰かが思い切り転んだ
  - テストの成績が圧倒的に良かった

---

# 緊張緩和理論

- 緊張状態から開放されたときに発生する笑い
- いわゆるホッとしたときの笑み
- ドッキリ番組で驚かされている側が笑う

---

# 不調和理論

- 現在の状況から期待される事態とは異なる事態が起きた場合に発生する笑い
- ズレによる笑い
- ジョークやお笑いが意図して引き起こそうとする際に主に利用される

---
layout: section
---
# なぜヒトは笑うのか
### 何かしらヒトの生存に寄与してきたはず

---
layout: section
---

# 類人猿も笑う

---
layout: two-cols
---

## ラフ [^1]

くすぐりなど遊びで発生する笑い

<v-click>

***快の笑い***

</v-click>

<img src="/play-face.png" class="h-xs" />

::right::

## グリマス [^1]

ボスを相手にするときなどの降伏を表す笑い

<v-click>

***社交的笑い***

</v-click>

<img src="/grimace.png" class="h-xs" />

[^1]: [ヒトはなぜ笑うのか? : 行動学の視点から](https://www.jstage.jst.go.jp/article/warai/21/0/21_KJ00009468506/_article/-char/ja/)

---

# なぜヒトは笑うのか

- 快を伴う笑いには何らかの効果があるはず
- 医学、人間行動学、進化心理学などの様々な説があり、大きく以下の2つに分類
  - 健康増進効果
  - 社会的効果

---
layout: image-right
image: https://images-na.ssl-images-amazon.com/images/I/41n-AIcZH7L._SX355_BO1,204,203,200_.jpg
---

# 健康増進効果

- 健康増進や治療に何らかの効果があるという研究、報告がある
- 例
  - 短期記憶の改善
  - 免疫におけるNK細胞の増加
  - 上記いずれも、大きな声を伴う笑いにより見られる

---

# 社会的効果

- 「ユーモアは受け手に取って有益な情報を持っている」[^2]
  - ユーモアは**予想外の驚き**を受け手に与える
    - 新規性のある情報を含んでおり、学びが得られる可能性がある
  - 笑うことで、さらにユーモアを促進する効果
    - 笑わせた相手への敬意や謝意を示している
- 一緒に笑うことによって仲間同士の結束を強める [^3]

[^2]: Weisfeld，G ．E．1993 The adaptive value of humor and laughter．Ethologyand So（riobiology 14（2） : 141・169．
[^3]: 松阪 崇久 2008 笑いの起源と進化，心理学評論 51（3） : 431・446．

---
layout: statement
---

# 笑うことの問題

---

# 笑ってはいけないことがある

- 差別行為となる笑い
  - ステレオタイプでの優越理論に基づく笑い

---
layout: image-right
image: https://source.unsplash.com/bik_lIl9Nco
---

# 笑いに現れる3者

- 笑わせる人
- 笑う人
- 笑われる人

<BottomRightCaption>

Photo by <a href="https://unsplash.com/@shidzuu?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Sithamshu Manoj</a> on <a href="https://unsplash.com/s/photos/laugh?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

</BottomRightCaption>

---

# 何を笑っているのか

- ユーモアは主に不調和理論によって生み出される
- 笑わせる人、笑う人との間で共通の概念があり、そこからのズレを用いている
- その概念に該当する人が、笑われる人となりえる。

---
layout: image-right
image: https://corobuzz.com/wp-content/uploads/2018/10/nmmk1.jpg
---

# 例

> 波平がドライヤーで頭頂部の髪を解かしている

この状況に面白みを感じるのはなぜか。

1. 髪を解かすという行為は、もつれた髪の毛を櫛などでほぐし、整える行為。
2. 波平の頭頂部の頭髪は一本しかない。

- 1の共有される概念から
- 2の事実と合わせることで、ズレが発生

---

# 概念の対象を笑ってしまっている

- 笑われる人固有のことを笑っているだけでなく、その概念に該当する人を笑っている
  - 先の例だと、頭髪が薄い人という概念
- その笑いを許容することで、差別を促してしまっていないか

---
layout: image-right
image: https://source.unsplash.com/Ns96HhR-b-c
---

# 笑われたい場合もある

- 自虐の笑い
  - 笑わせる人が笑われる人でもある場合
- 笑われることで救われる
  - 誰かにとっての快になる
- 笑われないと、辛い現実による恐怖が残る

<BottomRightCaption>

Photo by <a href="https://unsplash.com/@profwicks?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ben Wicks</a> on <a href="https://unsplash.com/s/photos/clown?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

</BottomRightCaption>

---
layout: quote
---

# 例: 締め切り

> 発表スライドがなかなか作れなくて、徹夜して直前に出来たんだよ〜
> あははー

<v-clicks>

私です。

笑ってください。

</v-clicks>

---
layout: section
---

# 個人的な想い

---
layout: statement
---

# いいチームを作るために、
# 笑いが大切では。

---

# 笑いがあると

- 失敗が共有しやすくなる
- メンバー間の結束を高める

---

# 失敗が共有しやすくなる

- 自虐のように、失敗を笑い話としてチーム内で共有できないか
- 優越の笑いにならないような配慮が必要
- 心理的安全性

---
layout: image-right
image: https://source.unsplash.com/l_ExpFwwOEg
---

# メンバー間の結束を高める

- 不調和理論の笑いを通じて、一緒に笑う。
- 共通の概念を育む活動

<BottomRightCaption>

Photo by <a href="https://unsplash.com/@heftiba?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Toa Heftiba</a> on <a href="https://unsplash.com/s/photos/laughing-people?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

</BottomRightCaption>

---
layout: section
---


# 笑いを作るにはどうしたらいいだろうか

---
layout: statement
---

# そこで、駄洒落ですよ！

---

# 駄洒落

- 文章中のある言葉を、音韻が類似しているというだけで置き換えることで面白みのある文章を生成するユーモア
- 意味的に遠い言葉を用いることで、不調和を作り出す

---
layout: section
---

# 自分の駄洒落のつくり方

---

# 前提

- オンラインカンファレンスなどのテキストチャット
- 参加者が発表で気になった言葉や思ったことがたくさん書き込まれている

---

# 手順

1. キーワードを見つける
2. そのキーワードの音韻を抜き出す
3. 音韻の全体、または部分から連想する言葉を見つける
4. 元のキーワードを含む文章に連想した言葉を置き換える

---

# 気をつけること
