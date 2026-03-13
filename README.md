# 💎 Python-Data-Analysis-LLM

> ### 「専門用語の壁を、言葉の力で取り払う。」
> 
本リポジトリは、書籍『Python 実践データ分析100本ノック 第3版』（秀和システム、2025年）の学習過程を記録したポートフォリオです。最大の特徴は、「文学部の視点でIT・データ分析を再解釈する」という試みにあります。非情報系の学習者が直面する「専門用語の壁」を取り払うため、すべての処理に対し、論理的かつ直感的な「完全独自解説」を記述しています。　　　

## ＊ 構成 ＊
### 📚 [01_Practice_Notebooks](./01_Practice_Notebooks)
**・ 実践データ分析100本ノック＆LLM活用20本ノック**
### ⛄ [02_Optimization_Reports](./02_Optimization_Reports.pdf)
**・ コード修正および最適化プログラム構築**
### 🍂 [03_Literary_Dictionary](./03_Literary_Dictionary)
**・ IT用語＆Python再定義辞書**

## ＊ 使用ライブラリ ＊
pandas, numpy, matplotlib, matplotlib.pyplot, japanize_matplotlib, dateutil, sklearn, networkx, itertools, pulp, ortoolpy, cv2, dlib, google.colab, IPython, math, MeCab, mecab_python3, 
unidic-lite, torch, langchain, langchain_ollama, langchain_core, langchain_community, langchain_experimental, re, json, subprocess, time, ollama, os, gradio

## ＊ 解説プレビュー ＊
#### ❄️ [Ch01_Web_Order_Analysis](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch01_Web_Order_Analysis.ipynb)
・ matplotlib：全ての工程を自らの手で制御する「プロ仕様版」グラフ作成ツール。

・ matplotlib.pyplot：複雑な工程を自動化した「簡易操作版」グラフ作成ツール。

#### ❄️ [Ch02_Retail_Data_Processing](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch02_Retail_Data_Processing.ipynb)
・ データの揺れ：同じ意味のデータなのに、書き方がバラバラで「別のもの」として認識されてしまっている状態。

#### ❄️ [Ch03_Customer_Profiling](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch03_Customer_Profiling.ipynb)
・ inplace = True：『元のデータ』そのものに修正を加える。※ユーザーに渡さない。

・ inplace = False：『コピーした新しいデータ』に修正を加えてユーザーに渡す。

#### ❄️ [Ch04_Customer_Behavior_Prediction](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch04_Customer_Behavior_Prediction.ipynb)
・ ライブラリ（sklearn）：「教師あり学習」「教師なし学習」に100%特化したライブラリ。※強化学習は非対応。

・ クラス（KMeans）：グループの平均値を探すAI。グループ全体のバラつき(標準偏差)を最小限にする。K＝グループ数。

・ クラス（StandardScaler）：補正装置。バラついたデータの単位や型を標準化して均一に整える。※AIではない。

#### ❄️ [Ch05_Customer_Churn_Prediction](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch05_Customer_Churn_Prediction.ipynb)
・ 決定木：最も綺麗にデータを「0と1」に分割できる「説明変数とその条件」を探す作業を木構造状に派生させていく作業。

・ ダミー変数化：フラグ化。文字列や複数の選択肢を、[True(1)」か「False(0)」だけで表す複数の列に作り替える。
#### ❄️ [Ch06_Logistics_Route_Optimization](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch06_Logistics_Route_Optimization.ipynb)
・ def：「define(定義する)」の略。手順を関数として定義する。

・ def trans_cost(df_tr, df_tc, ...)：def 手順に名付けた関数名(変数1, 変数2, ...)

※ 関数 = 計算式。変数1, 変数2 = 定義する関数の素材。

#### ❄️ [Ch07_Logistics_Network_Design](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch07_Logistics_Network_Design.ipynb)
・ AIモデル：機械学習。予測する。大量のデータが必要。

・ 数理モデル：最適化。計算する。制約条件と目的関数が必要。

#### ❄️ [Ch08_Consumer_Behavior_Simulation](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch08_Consumer_Behavior_Simulation.ipynb)
・ ハブ(Hub)：複数の端末(デバイス)を集めて連結させる集線装置。伝播させる装置。

#### ❄️ [Ch09_Image_Recognition_Analysis](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch09_Image_Recognition_Analysis.ipynb)
・ cv2.cvtColor()：色の並び順や色の種類を変更する。

※ 色の並び順を変更する理由：AIやグラフの誤作動を起こさないため。 OpenCVは、古い世界標準(BGR)の並び順を適用しているのに対し、他のライブラリは、新しい世界標準(RGB)の並び順を適用している。

※ 白黒に変更する理由：AIが物体を検知しやすくするため。※物体検知の妨げとなる設定を変更することで、精度向上と高速化を図る。

#### ❄️ [Ch10_NLP_Survey_Analysis](./01_Practice_Notebooks/01_Data_Analysis_100knocks/Ch10_NLP_Survey_Analysis.ipynb)
・ コサイン類似度：特徴量同士の角度の近さで類似度を表す。

【ベクトル空間】直面する状況下で、ベクトルと考えられる変数とそれに対応する特徴量のこと。【ベクトル】変数とそれに対応する特徴量。【スカラー】数値。1つ以上の変数に対応するベクトルの特徴量の積の和。【特徴量】特徴を分析するために数値化したもの。

#### ❄️ [Ch00_After_School_LLM_20knocks](./01_Practice_Notebooks/02_LLM_20knocks/Ch00_After_School_LLM_20knocks.ipynb)
・ 内部API：自分の端末内で実行待機しているインストールしたアプリやOSをオフライン環境で操作するための接続口。例）Ollama, Windows, Mac, Linux

・ 外部API：他社の端末内で実行待機しているインストールしたアプリをオンライン環境で操作するための接続口。例）Google検索, LINE, Gemini

## ＊ 教材 ＊
下山輝昌・松田雄馬・三木孝行 著「Python 実践データ分析100本ノック 第3版」(秀和システム新社、2025)

