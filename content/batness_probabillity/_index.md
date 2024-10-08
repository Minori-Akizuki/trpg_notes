---
date: "2024-09-11"
description: 確率を正しく扱おう
title: ダイス目が悪い人間はいる
weight: 1
---


ご意見ご感想や追記してほしい事などありましたら<a href="https://twitter.com/real_analysis">リプ</a>なり<a href="https://github.com/Minori-Akizuki/trpg_notes/issues">Issue</a>なり頂ければ参考にいたします。

----

[逆正弦法則](https://manabitimes.jp/math/2716)

**本来このリンク一つだけでこの議論の 9 割ぐらいは終了する** のだが、多分「ダイスの目は均等に出るんだから『出目が悪い人間』なんてありえない」と息巻いている人間はこれを読んでも何の事かわからないし、残りの 1 割は理論の話というより認知の話なので結構な長文を書く事になる。

結論から書くなら、「出目が悪い人間」は **いる** 。 **数学的にいる** 。

……訂正する。もう少し厳密さを増やす。 **「出目のみに起因して不幸な結果に陥った人間がいて、そいつに挽回の機会は期待できず、それは間違いなく『出目の悪い人間』である。」** 多分これが私が考えられる最も厳密な表現である。

とはいえこの話は確かに難しい。確率というのは目の前にあるようでその実態は非常に捉えづらく、本質を扱おうとするとそれらは純粋数学と言えるぐらいには素朴であり、かつ複雑である。

にもかかわらわず確率の基礎の基礎は小学生でもやるし、数学が苦手な人はそれすらもできないので、翻って「サイコロの目は 1 から 6 までが均等に出る」ぐらいの **誤った認知を持つ程度の理解度の人間** が **「俺確率できるんだぜ」** みたいな顔をして「出目が悪い人間なんていない！！！」などと世迷い言を言い続けているのが現状である。

正直私だって確率は素人だ。だがそれでもあまりにも目に余る学級会が日夜くりかえされているのを見兼ねてこの記事を書くに至った。

## マインドセットがまちがっている

これは「残りの 1 割」のうちの、さらに半分ぐらいの話なのだが、そもそも TRPG でこの話をするのは **大変に愚か** である。
特にダイスを用いる TRPG は根本として「 **分散に一喜一憂するもの** 」であるからである。そうじゃなかったらいちいち判定にダイスなんて振らせないという事に早く気付いてほしいし、なんなら「判定が面倒であれば 2D6 のかわりに 7 を用いてもいい」みたいな処理を採用しているシステムは既に複数存在する。

それなのになぜ我々はあんな素朴な乱数発生器を振り続けるのか、それは一重に **クリティカルに歓喜し、ファンブルにキレるため** である。当然その営みの中には「 **自身の出目が悪い事を自虐的に自慢する事** 」も含まれる。

まぁ、おそらく「ダイスの目は均等に出るんだから『出目が悪い人間』なんてありえない」という事を言うような、確率と真摯に向き合った事の無い人間はきっとそうではないのだろう。偏見が入るが、それはダイスを振るのに向いていないのではと思ってしまう。乱数発生器を用いないシステムはいくらでもあるので、自分に合ったシステムを探した方が健康的とすら思う。

## 「確率」と「統計」を混同している

これは「残りの 1 割」のうちのもう半分の話である。

例えば「サイコロなんていっぱい振るんだから、振った結果の平均値は収束するはずだ」という主張がある。
確かにこの一点だけ見ればこれは正しい。例えばこれが「麻雀の収支」とかだったらもうちょっと正しい。つまり **これは「統計」の話であり、「確率」の話ではない** 。
あなたが今セッション中のダイスロールでクリティカルを出したとして、それで昨日やったセッションのファンブルをなかった事にできる訳ではない。逆も当然できない。

少し具体的な例を出そう。例えばある同一のセッションで 5 回ファンブルを出したとする。システムにもよるが、 1 回のセッションで 5 回もファンブルを出したら、そのセッションは惨憺たる結果になったであろう事は想像に容易い。
ではその後のセッションで 5 回にかけて 1 回ずつクリティカルを出したとしよう。ファンブルとクリティカルの確率が同一だとすれば、これは彼らの主張と何ら矛盾していない。
回数を重ねてめでたくファンブルの回数とクリティカルの回数が収束した。

では、この人物は不幸であるか？ **これは恐らく「不幸」に分類していい** 。セッションに 1 回きりのクリティカルがそのセッションの過程を劇的に変化させる事はあまり多くないし、
この 5 回のセッションが並以上の結果になったところで「 **じゃあ慣らしてファンブルが 5 回出たセッションがチャラになったね** 」とか思う人間は多分 [^maybe] いない。

[^maybe]: いや、こういう主張をしている人間が本当にそう思っているなら、彼らの主張は正しくなる。もしかしたら本当にそう思っているのかもしれない。

ここで「 5 回ファンブルが出たセッションがあるならそのうち 5 回クリティカルが出るセッションもあるだろ！」という主張が出てくるだろう。それは **少しだけ正しい** が、
そう思う人は記事の先頭に載せた [逆正弦法則](https://manabitimes.jp/math/2716) のページを改めて読むか、この記事をもう少し先まで読み進めてほしい。

## 確率に関する代表的な誤りのうち、特に TRPG プレイヤーにとって身近なもの

この話に限らず、ダイスその他の乱数発生装置を使う TRPG は確率の話がついて回る。
確率について間違った認知をしやすい物のうち、特に TRPG プレイヤーにとって身近な物をいくつか挙げる。

### サイコロの目は 1 から 6 までが均等に出る

**出ない** 。

「一様」と「均等」を履き違えている。
あるいはソシャゲのガチャ [^gacha] とかのコンプリートパックみたいなのを天井まで回すのが日常になっていて頭がおかしくなっているのかもしれない。

[^gacha]: 「ガチャ」はタカラトミーアーツの商標だが、うまく総称できるものがないのでこう表記する

均等なのはあくまでも確率だ。 **結果が均等である事は誰も保証していない** し、それは確率を扱う上で最もやってはいけない勘違いである。

例えば今あなたが適当にサイコロを取って 100 回ぐらい振ったとしよう。全部 1 が出たとする。そのサイコロがグラサイ [^grasai] かと言われると **多分** そうとしか言えない。
本当は「有意水準何%の確率でこのサイコロが離散一様分布に従っているという帰無仮説は棄却された」とか言うのだが、平易な言いかたをするのならば「そうはならんやろ」というのを数学的に言っているだけである。

[^grasai]: 重心が操作されているなどして、特定の目が出やすくなっているサイコロの事である。語源が気になって調べようとしたが信憑性のある情報が出てこなかった。

しかしあなたがたは人生の中で「 **なっとるやろがい！！** 」という現場の一つや二つ、多分遭遇していると思う。別にサイコロの話ではなく、「卵を 2 個割ったら 2 個とも双子だった」でも何でもいい。
「このぐらいの確率でしか起こらない」という推論や計算は「だから起こりえない」という事には **ならない** 事に注意されたい。サイコロを振って 100 回とも 1 が出るというのは結構言いすぎだが、例えば「 2D6 を 3 回振って 3 回ともピンゾロが出る」ぐらいなら 1/46656 なので、これは割と現実的に出る。年末ジャンボ宝くじで 3 等を当てるより遥かに簡単だ。これはサイコロを 6 回振っているのと同義なので 1 〜 6 の目が 1 回ずつ出ていなければおかしいはずだ。彼らの主張が正しく、出目が **均等** であるならば。だ。もっと言うと、ある乱数があったとしてその乱数が本当に乱数か調べる方法の一つに「想定されている分布で説明できすぎないか」というものまであるぐらいだ。本当に、 **本当に「均等」という言葉は確率を論ずる上では使ってはいけない** 事を肝に命じてほしい。

「6 回しか振ってないから、偏るのは当然だ。たくさん振れば出目が均等に近づく。」という主張をされるかもしれない。実際これは **ほとんど** 正しい。
「ほとんど」と言ったのはその「たくさん」が「 **無限** 」であるからだ。
我々は人間であり、その寿命は高々有限なので当然サイコロも有限回しか振れない。もしかしたら神ならできるかもしれないが、 [神はサイコロを振らないらしい](https://de.wikipedia.org/wiki/Gott_w%C3%BCrfelt_nicht) 。

これは「確率」が抽象概念なのに対して「サイコロを振る」という行為が具体事象であるからだ。「サイコロを振ったら 100 回連続で 1 が出た」という事象は「サイコロの出目が一様である」という事を「疑う」事はできても **否定する事はできない** 。
お望み通りたくさんサイコロを振ったらなおさらである。地球の寿命が尽きるぐらいまで連続してサイコロを振れば、高々 100 回連続で 1 が出た事なんて、ましてや 6 回連続でなんて本当に些細な事である。

逆に言うならば「なんぼ一様なサイコロでも、それが有限回である限り振るだけ低い目が出る事はありうる」という事である。
「確率」と「結果」は即座に結びつけてはいけないし、確率の見積りができない様ならなおさらだ。

### 確率の見積り

例えば CoC で 1 回のセッションに 20 回の判定を要求されたとしよう。

セッション中 1 回以上 100 ファンブル が出る確率は約 18.2% だ。 2 セッション連続で同様の状況に陥いる確率は約 3.3% だ。
4 回連続で計算しても約 0.11% 残っている。これは「昨日もファンブル今日もファンブル」という人間を生み出すには十分な数字であり、この「0.11%」という数字を「無いも同然じゃないか」という人間はかなり確率の見積りができていない寄りというか、もうちょっと日常の色々な物に注意を払った方がいいというか、お願いだから二項分布の確率と試行回数の関係ぐらいは学び直して損はないので是非やってほしい。

というか、この手の話題が好きで「出目の悪い人間なんていない」という人間は同じ口で「 **今日は** 出目が悪かったかもしれないが」という台詞を平気で口にする。
「 **出目が悪い日** 」があるなら「 **出目の悪い人** 」もいるだろうというのが普通の思考であるはずだが、恐らく確率の見積りが著しくできていない。

「CoC の連続した 4 回のセッション全てで 1 回以上ファンブルを出す確率」を先程「0.11%」と言った。主観が入ってしまうが **これはだいぶ不運だ** と、少なくとも私は思っている。
日本に CoC をやっている人間がどのくらいいるかはわからないが、『クトゥルフ神話TRPG』は 2019 年時点で 20 万部売れており、これも結構前のデータなのでざっくりとアクティブユーザーが 10 万人ぐらいいるとする。
確率が低くても母数がケタ違いなのだ。年 100 本のペースで 30 年 TRPG をやっても 3000 セッションなのに、彼らが 10 万本クラスのセッションを行っているとはとても思えない。
期待値だけでも 100 人程度この状況に陥っている人がいる計算になり、目の前の人間に向って「不運なのはお前ではない」と無邪気には言えない数字である。界隈って狭いし。

CoC だけでそうなのだ。他の古今東西の TRPG の人口を含めたら「不幸な人間」というのはそれなりにいる、という事が彼らの好きな数字で示された。

### 出目は収束する

**しない** 。

この言説は大いなる間違いを含んでいる。正すとしたら「 **出目を回数で割った平均値は収束する** 」である。

逆に言うならば **出目そのものは収束しない** と言うべきか。この話をするためには今までに出てきた話を全て用いなければいけない。マインドセットの違い、「確率」と「統計」の混同、「一様」と「均一」の履き違えである。

さらに、新しい概念を導入する。「 **サイコロの出目はそれ以前の出目の影響をうけない** 」だ。確率の基礎の基礎の基礎であるため本当はわざわざ言うのもアホらしいのだが、 **多分彼らはこれを理解していない** 。よく「さっきまで悪い出目だったから今度こそいい出目が出るはずだぞー」と景気付けで言う TRPG プレイヤーがいるが、推測するに **彼らはこれを本心から言っている** 。

話を少し戻す。「ファンブルを 1 回のセッションで 5 回出し **た** 人」がいるとする。この「 **た**  [^ta] 」 が重要である。

[^ta]: ゆる言語学ラジオではない。

この人がこの先振るダイスの出目はほどほどなのかもしれない。いい目が出るかもしれない。悪い目が出るかもしれない。それは誰にもわからない。そう。 **この先は** である。

仮にこの先のダイスでとてもとても均等な目が出たとする。彼らの主張が正しければ (実のところ割と正しいのだが) **この先の** ダイスは振れば振るほど出目が均等に近づき、統計を取るならば **この先の**出目は平均値に近づくはずであるし、実際そうなる事は十分に期待できる。
つまりこの人は「 **ファンブルを 1 回のセッションで 5 回出した人** 」の汚名を返上する機会が **無い** 。「出目が一様に出る」という事実を加味すれば加味するほどこの人は「ファンブルを 1 回のセッションで 5 回出した人」であり続ける。

信じられない事に、ここまでの事を説明しても尚「 5 回ファンブルが出たセッションがあるならそのうち 5 回クリティカルが出るセッションもあるだろ！」と言い続ける人がいる。それは確かに正しい。ただし彼らは **5 回クリティカルが出るセッションと同じ確率でまた 5 回ファンブルを出すセッションがある** 事を忘れている。彼らはきっと、主張していないところで (あるいは無意識に)  **本気で「ファンブルが出た分クリティカルが出る筈だ」** と思っているのだろう。残念ながらそれは無い。「 **サイコロの出目はそれ以前の出目の影響をうけない** 」事をどうやら忘れているらしい。

## 総括

これが「出目が悪い人」の正体である。 **既に悪い出目を出してしまっており、その不幸を覆す事が(当然だが)自力でできない人** である。不幸な事に「出目に偏りなんて無い」と主張する彼らの意見を **加味すれば加味するほど** これらの「出目が悪い人」に挽回する機会は無い事になる。

つまりは……その…… TRPG じゃなくてもさ……なんか「平均が平均が」とか言いながらさ……よくわかんない数字とよくわかんないグラフ出してくるクソみたいな人いるじゃん……
数字って読みかたわからないと簡単に騙されるから……確率じゃなくても……その数字が何を意味するのか……みんな考えた方がいいよ……

うん……大したオチはないんだ……ごめんね……
