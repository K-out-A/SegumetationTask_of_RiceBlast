# SegumetationTask_of_RiceBlast
【概要】

大学院での研究対象がいもち病であり、画像認識手法を用いて罹患部位の抽出がしたい。今回は領域認識手法であるセマンティックセグメンテーション（Segnet）を用いて罹患部位の抽出を行う。
   
# 開発環境
- Ubuntu 18.04.5 LTS
- Google Colabratory
- Tensorflow ver2.3
# 使い方
### Githubからclone
Github上からソースコードをローカルPC上にcloneする。
```
$ git clone git@github.com:K-out-A/SegumetationTask_of_RiceBlast.git
```
### ソースファイルの実行
[Google Colabratory](https://colab.research.google.com/notebooks/intro.ipynb?hl=ja#recent=true"Colabratoryへようこそ")に遷移し、フォルダ（SegumetationTask_of_RiceBlast）をアップロードする。

test.ipynbを開き、上から順にセルを実行する。

# 実行結果
imgsフォルダにある画像を読み込ませると推論が始まります。

出力結果は黒、緑、赤でセグメンテーションされます。

順に背景、葉、罹患部位となります。

以下が➀原画像と➁出力結果です。

①original-img

<img src="https://github.com/K-out-A/SegumetationTask_of_RiceBlast/blob/main/imgs/DSCF1481.png" width="480">

②result-img

<img src="https://github.com/K-out-A/SegumetationTask_of_RiceBlast/blob/main/results/DSCF1481_result.png" width="480">
