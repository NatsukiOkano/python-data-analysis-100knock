# 💎 Python-Data-Analysis-LLM

> ### 「専門用語の壁を、言葉の力で取り払う。」
> 
本リポジトリは、書籍『Python 実践データ分析100本ノック 第3版』（秀和システム、2025年）の学習過程を記録したポートフォリオです。最大の特徴は、「文学部の視点でIT・データ分析を再解釈する」という試みにあります。非情報系の学習者が直面する「専門用語の壁」を取り払うため、すべての処理に対し、論理的かつ直感的な「完全独自解説」を記述しています。　　　

## ＊ 構成 ＊
### 📚 [01_Practice_Notebooks](./01_Practice_Notebooks)
**・ 実践データ分析100本ノック＆LLM活用20本ノック**
### ⛄ [02_Optimization_Reports](./02_Optimization_Reports)
**・ コード修正および最適化プログラム構築**
### 🍂 [03_Literary_Dictionary](./03_Literary_Dictionary)
**・ IT用語＆Python再定義辞書**

## ＊ 使用ライブラリ ＊
pandas, numpy, matplotlib, matplotlib.pyplot, japanize_matplotlib, dateutil, sklearn, networkx, itertools, pulp, ortoolpy, cv2, dlib, google.colab, IPython, math, MeCab, mecab_python3, 
unidic-lite, torch, langchain, langchain_ollama, langchain_core, langchain_community, langchain_experimental, re, json, subprocess, time, ollama, os, gradio

## ＊ 解説プレビュー ＊
#cv2.cvtColor()：色の並び順や色の種類を変更する。 

#※色の並び順を変更する理由：AIやグラフの誤作動を起こさないため。 OpenCVは、古い世界標準(BGR)の並び順を適用しているのに対し、他のライブラリは、新しい世界標準(RGB)の並び順を適用している。 

#白黒に変更する理由：AIが物体を検知しやすくするため。※物体検知の妨げとなる設定を変更することで、精度向上と高速化を図る。 

#内部API：自分の端末内で実行待機しているインストールしたアプリやOSをオフライン環境で操作するための接続口。例）Ollama, Windows, Mac, Linux 

#外部API：他社の端末内で実行待機しているインストールしたアプリをオンライン環境で操作するための接続口。例）Google検索, LINE, Gemini 

#ライブラリ（sklearn）：「教師あり学習」「教師なし学習」に100%特化したライブラリ。※強化学習は非対応。 

#クラス（KMeans）：グループの平均値を探すAI。グループ全体のバラつき(標準偏差)を最小限にする。K＝グループ数。 

#クラス（StandardScaler）：補正装置。バラついたデータの単位や型を標準化して均一に整える。※AIではない。 

#np.linalg.norm()：ライブラリ（numpy）に格納されるモジュール（linalg）から関数（norm）を自分のプログラムに導入する。 

#【パッケージ】類似性のあるモジュールを格納したフォルダ。【モジュール】プログラムを再利用するために、コードを格納したファイル。【クラス】データ型。 

#コサイン類似度：特徴量同士の角度の近さで類似度を表す。 

#【ベクトル空間】直面する状況下で、ベクトルと考えられる変数とそれに対応する特徴量のこと。【ベクトル】変数とそれに対応する特徴量。【スカラー】数値。1つ以上の変数に対応するベクトルの特徴量の積の和。【特徴量】特徴を分析するために数値化したもの。 
## ＊ 教材 ＊
下山輝昌・松田雄馬・三木孝行 著「Python 実践データ分析100本ノック 第3版」(秀和システム新社、2025)

