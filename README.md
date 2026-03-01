# 📚文系大学生による「データ分析100本ノック＆番外編LLM活用20本ノック」学習ログ
## 文学部の視点でITの専門用語やPythonプログラムを論理的に言語化。
非情報系でも直感的に理解できる完全独自解説を記述したGoogle Colabノートブックを提供します。
## 使用ライブラリ
pandas, numpy, matplotlib, matplotlib.pyplot, dateutil, sklearn, networkx, itertools, pulp, ortoolpy, cv2, dlib, google.colab, IPython, math, MeCab, mecab_python3, 
unidic-lite, torch, langchain, langchain_ollama, langchain_core, langchain_community, langchain_experimental, re, json, subprocess, time, ollama, os, gradio
## 解説プレビュー
#cv2.cvtColor()：色の並び順や色の種類を変更する。(引数↓)

#COLOR_BGR2RGB：デフォルトの色の並び順「B(青)G(緑)R(赤)」を「R(赤)G(緑)B(青)」に並び替える。

#COLOR_BGR2GRAY：色を「白黒」に変更。

#色の並び順を変更する理由：AIやグラフの誤作動を起こさないため。

#※OpenCVは、古い世界標準(BGR)の並び順を適用しているのに対し、他のライブラリは、新しい世界標準(RGB)の並び順を適用している。

#白黒に変更する理由：AIが物体を検知しやすくするため。※物体検知の妨げとなる設定を変更することで、精度向上と高速化を図る。

#内部API：自分の端末内で実行待機しているインストールしたアプリやOSをオフライン環境で操作するための接続口。

#外部API：他社の端末内で実行待機しているインストールしたアプリをオンライン環境で操作するための接続口。

#内部API：例）Ollama, Windows, Mac, Linux

#外部API：例）Google検索, LINE, Gemini

#ライブラリ（sklearn）：「教師あり学習」「教師なし学習」に100%特化したライブラリ。※強化学習は非対応。

#モジュール（cluster）：クラスタリングのプログラムを格納したファイル。

#モジュール（preprocessing）：AIが扱いやすいようにデータの単位や型を均一にするプログラムを格納したファイル。

#クラス（KMeans）：グループの平均値を探すAI。グループ全体のバラつき(標準偏差)を最小限にする。K＝グループ数。

#クラス（StandardScaler）：補正装置。バラついたデータの単位や型を標準化して均一に整える。※AIではない。

#パッケージ：類似性のあるモジュールを格納したフォルダ。

#モジュール：プログラムを再利用するために、コードを格納したファイル。

#クラス：データ型。

#コサイン類似度：特徴量同士の角度の近さで類似度を表す。

#特徴量：特徴を分析するために数値化したもの。

#プログラミング言語（Python）：AI, Webアプリ, 自動化(業務効率化)ツールの開発。

#プログラミング言語（C言語）：家電製品, OS, デバイスドライバ(OSと周辺機器を接続させるためのソフトウェア)の開発。

#プログラミング言語（C++）：3Dゲーム(メタバース,VR,AR), ウェブブラウザ, 金融システムの開発。
## 出典
下山輝昌・松田雄馬・三木孝行「Python 実践データ分析100本ノック 第3版」(秀和システム新社　2025)

