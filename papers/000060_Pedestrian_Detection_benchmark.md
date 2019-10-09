# [Pedestrian Detection: A Benchmark](http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/)
Piotr Dollar´, Christian Wojek, Bernt Schiele, Pietro Perona

California Institute of Technology

## どんなもの？(コントリビューション)
* 研究を加速させるための新しい歩行者検出データセットの提供

## 先行研究と比べてどこがすごい？
* データセット量が既存のデータセットより二桁多い．
* 新しい評価指標を提案．

## 技術や手法の肝はどこ？
* 既存のper-window Performance評価ではデータセット全体では評価がよくなるが，画像単体では悪い場合がある．その改善のため，per-image Performanceを提案．
* オクルージョンや群衆など曖昧な対象に関してはアノテーションはするも，評価に関してはどちらでも良い．とするなど柔軟に評価を行う．

## どうやって有効だと検証したか？
* 既存手法を利用，再実装し新規データセットで評価

## 議論はある？
* 既存の手法（HOG）ではオクルージョンと小さいものの検出が困難．

## 次に読むべき論文は？
* How Far are We from Solving Pedestrian Detection?
