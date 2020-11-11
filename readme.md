# 課題：02 じゃんけんのwebサイト

デプロイ先：https://ayakonishi.github.io/02_26_JankenBaseball/

## プロダクトの紹介
- じゃんけんを応用し、バッティングゲームを作りました
- 空振り、シングルヒット、ツーベース、スリーベース、ホームランが打てます。
- ホームランの確率は、５％です。

## 工夫した点，こだわった点
- ホームランになると、若干画面が派手になります。
- 構想では、もっと派手でした。（力と時間不足…）
- 空振り3回でバッターアウト、５回くらいコンピュータと対戦できる風にしたかった。（９回まで行くとユーザーが飽きるので５回）。それができると意地悪要素が入れられたのに。

## 苦戦した点，共有したいハマりポイントなど
- CSS がまだ苦手で、CSS が効かないとハマっていました。原因は、「.class{}」の最初のピリオドがなかったこと………。道理で「img.gamen_img{}」だけは効いたはずだわ。
- ホームランになった時、画面いっぱいに紙吹雪が舞う予定でした。サンプルをネットで見つけたけど、そのまま使っていいか権利的に判らなかったのと、やや複雑すぎてただコピペしただけでは動かなかったのが敗因です。
- もうちょっと、画面装飾に凝りたかった。