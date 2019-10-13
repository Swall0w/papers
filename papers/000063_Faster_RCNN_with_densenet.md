# [Faster R-CNN with densenet for scale aware pedestrian detection vis-à-vis hard negative suppression](https://www.semanticscholar.org/paper/Faster-R-CNN-with-densenet-for-scale-aware-hard-Choudhury-Padhy/7b60734442b705d2383973cfad175aa527864d31)
Suman Kumar Choudhury, Ram Prasad Padhy, Pankaj Kumar Sa

National Institute of Technology Rourkela

## どんなもの？(コントリビューション)
* 歩行者検出タスクにおいて2つのデータセットで他手法よりも精度を高くした．

## 先行研究と比べてどこがすごい？
* 人っぽいFalse Positiveを減らすための2段階訓練方法．
* RPNでは人っぽいものかそうじゃないかで提案．
* 分類器で人だけを分けるように学習
* 小さいスケールの検出は困難なため，Densenet161の複数の中間層を用いて，RPNで提案

## 技術や手法の肝はどこ？
* グランドトゥルースだけでなく，False Positiveになりそうな領域をSelective Search + HOG特徴量で作り，RPNの訓練と分類機の訓練で違うデータセットを用いている．
* Densenet-161

## どうやって有効だと検証したか？
* Caltech, Inria dataset

## 議論はある？
* どっちの手法がどれほど効果があるのかがわからない．
* ベースラインがそもそもないため，densenet161とRPNの通常の学習からどれだけ減っているのか？

## 次に読むべき論文は？
* None
