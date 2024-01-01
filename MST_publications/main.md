# 業績一覧: 小江 一茶　<指導教員：藤澤克樹 教授>

## 1. 査読付き国際会議論文

　A. \*<span class="underline">**Oe Issa**</span>, Keiichiro Yamamura, Hiroki Ishikura, Ryo Hamahira, Katsuki Fujisawa, *Superpixel Attack: Enhancing Black-Box Adversarial Attack with Image-Driven Division Areas*, Australasian Joint Conference on Artificial Intelligence 2023, 28th Nov - 1st Dec, 2023

　B. \*Keiichiro Yamamura, Haruki Sato, Nariaki Tateiwa, Nozomi Hata, Katsuki Fujisawa, <span class="underline">**Issa Oe**</span>, Hiroki Ishikura and Toru Mitsutake, *Diversified Adversarial Attacks based on Conjugate Gradient Method*, Thirty-ninth International Conference on Machine Learning (ICML 2022), 19-21 Jul, 2022.

※ * は主著者

## 2. 査読付き学術誌論文

　C. \*Ishikura Hiroki, Tateiwa Nariaki, Egi Shingo, <span class="underline">**Oe Issa**</span>, Hata Nozomi, Mitsutake Toru, Yamamura Keiichiro, Fujii Miyu, Fujisawa Katsuki, *Scheduling system for automated storage and retrieval system with multiple machines using a time-expanded network*, Japan Journal of Industrial and Applied Mathematics, Springer, DOI : 10.1007/s13160-023-00619-1

※ * は主著者

## 3. 学会発表

　D. <span class="underline">**Issa Oe**</span>, *Improvement of black-box adversarial attacks based on discrete optimization using Superpixel*, The 7th ZIB-IMI-ISM-NUS-RIKEN-MODAL Workshop on Future Algorithms and Applications, 27th to 30th September, 2023.

　E. <span class="underline">**Issa Oe**</span>, *Superpixel Attack: Enhancing Black-Box Adversarial Attack with Image-Driven Division Areas*, Australasian Joint Conference on Artificial Intelligence 2023, 28th Nov - 1st Dec, 2023.

## 4. 技術本の執筆

　F. 藤澤 克樹，光武 亨，<span class="underline">**小江 一茶**</span>，秦 希望,「量子技術の実用化と研究開発業務への導入方法」,技術情報協会，ISBN 978-4-86104-915-6

# 研究内容

## 1. 離散最適化に基づく敵対的攻撃の提案

**査読付き国際会議論文 1件(業績一覧A)，学会発表 2件(業績一覧D, E)**

【概要】深層学習モデルはその性能の高さから様々なタスクに応用されている一方で，小さな摂動(悪意のあるノイズ)に脆弱であることが知られています．そのため脆弱性の検証，摂動に対する堅牢性の向上を目的として敵対的攻撃が研究されています．敵対的攻撃では非線形最適化によって誤分類させる入力を求めます．本研究では次の2つのアプローチによって新たな敵対的攻撃手法を開発しました．①一つ目のアプローチは実験的分析に基づいて探索領域を摂動領域の境界上に制限することです．このとき，非線形最適化で定式化されていた敵対的攻撃は離散最適化へと帰着されます．②二つ目のアプローチは一定領域に加える摂動をまとめて変化させながら探索することです．これによって探索回数の削減を試みます．これら二つのアプローチを取り入れた新たな攻撃手法は既存手法と比較して大きな性能向上を示していました．この内容は国際会議AJCAI2023に採択され，高い評価をいただいています．

keyword: 敵対的攻撃，離散最適化，深層学習，画像処理

![](./AdEx1.png)

## 2. 時間拡大グラフを用いた自動倉庫の運搬最適化

**査読付き学術誌論文1件(業績一覧C)，ロート製薬株式会社との共同研究，日経新聞等でプレスリリース**

【概要】
本研究はロート製薬株式会社との共同研究であり，ロート製薬株式会社は輸送機が自動で荷物を運搬する大きな倉庫を所有しています．しかし，入出庫の運搬が効率的でないために滞留が生じ，社内での不満が溜まっていました．そこで工場の輸送機と貨物の情報を受け取った後，それをもとに定式化と最適化を行い，自動倉庫を制御する．その後再び自動倉庫の状態を情報化してフィードバックすることで効率的に運搬を行うシステムを提案しました．ただし，輸送機によって運べない荷物や受け渡し口に容量制限があるなどの制約があり，運用していくために現実的な計算時間で解が出せるような定式化にする必要がありました．これらを解決した上で論文としてまとめ，日本経済新聞など様々な場所でプレスリリースされています．

keyword: 時間拡大グラフ，離散最適化，自動倉庫

![](./rohto.png)

## 3. 共役勾配法に基づく敵対的攻撃の提案

**査読付き国際会議論文 1件(業績一覧B)**

【概要】上記の敵対的攻撃手法とは異なり，本研究では非線形最適化からのアプローチによって新たな敵対的攻撃手法を提案しています．これまで既存手法の多くは単純な最急降下法に基づいた敵対的例の探索を行っていました．しかし過去の知見から単純な最急降下法では限られた領域のみを探索していることが想定されます．そこで，非線形最適化で用いられている共役勾配法に着目し，新たな攻撃手法を提案しました．実際に比較実験によって提案した攻撃手法が多くのモデルで高い攻撃成功率示しています．さらにグラフ理論で用いられているクラスタ係数という指標に基づいて探索点の多様性を評価する新たな指標を提案し，探索点の多様性について分析を行っています．

keyword: 敵対的攻撃，非線形最適化，深層学習

![](./AdEx2.png)

## 4. ゲート方式量子計算機を用いた物体検出アルゴリズムの提案

**技術本の執筆 1件(業績一覧F)，TIS株式会社との共同研究**

【概要】本研究はTIS株式会社との共同研究であり，TIS株式会社ではゲート方式の量子計算機の開発を行っています．ゲート方式の量子計算機は古典計算機(現在普及しているコンピュータ)を凌駕するとして期待されているものの，未だ有望な応用例が少ない状況です．そこで数理最適化の観点から様々なアルゴリズムを評価し，改善することを行ってきました．その過程で量子計算機を用いた物体検出アルゴリズムに着目し，既存の物体検出アルゴリズムの一部に量子計算機を適応した処理を加えることで計算速度と精度を高めることに成功しました．本研究で行った数理最適化の観点での既存アルゴリズムの評価を技術本としてもまとめています．

keyword: 量子計算機，量子ゲート方式，量子近似最適化アルゴリズム(QAOA)

![](./TIS.png)

## 5. グラフ理論を用いた量子計算機の性能改善

**NTT研究所との共同研究，プロジェクトリーダー**

【概要】本研究はNTT株式会社 R&D部門(通称 NTT研究所)との共同研究であり，NTT研究所ではアニーリング方式の量子計算機を開発しています．アニーリング方式量子計算機は上記のゲート方式とは異なり，すでに実用的な精度と速度を達成しています．しかし，最適化できる変数の数に限りがあるという大きな課題を抱えています．そこで注目したのがsubQUBOモデル抽出と呼ばれる技術です．subQUBOモデル抽出では変数の多い元問題に対して，一部の変数を抽出と抽出された変数のみの最適化を繰り返すことで元問題の解を探索します．この時に抽出する変数の選び方は最終的な解の精度に大きく影響します．そこで，元問題をグラフとして表現し，グラフ理論におけるクラスタ性に着目することでsubQUBOモデル抽出の精度を向上させる研究を行いました．また，その過程で量子計算機の性能予測アルゴリズムの開発などにも取り組んでいます．

keyword: グラフ理論，量子計算機，subQUBOアルゴリズム

![](./NTT.png)
