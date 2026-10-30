## Hi, I'm Shota 👋

I'm a graduate student in Mobile Multimedia Communications at Shibaura Institute of Technology.

## 🤖 I build AI

AIを作っています。麻雀AI（Transformer）の開発と、その判断根拠を説明するXAI（説明可能AI）の研究が中心です。

### この画像は何？

麻雀を知らなくても大丈夫です。麻雀には何十種類もの牌があり、AIは牌ひとつひとつを「数字の並び」として覚えています。人間にはその数字の並びをそのまま見ることはできないので、3次元の空間に配置し直して描いたのがこの画像です。

点ひとつが牌ひとつです。近くにある点ほど、AIにとって「似た牌」を表します。同じ色でまとまっているのは、AIが近い性質を持つと判断した牌のグループです。牌同士が似ているかどうかは人が教えたのではなく、大量のゲームのデータからAIが自分で学んだ結果です。

つまりこの図は、AIの頭の中にある「牌の地図」を覗いたものだと思ってください。

![麻雀AIの牌トークン埋め込み（層4）を3次元PCAで可視化](https://raw.githubusercontent.com/ShotaYmzk/mahjong-ai-qiita-images/main/pca3d_layer4.gif)
