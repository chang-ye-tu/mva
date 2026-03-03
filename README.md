# 多變量分析 

## 教科書

- [Härdle, W., Simar, L., 2015. Applied Multivariate Statistical Analysis. 4th ed., Springer.](https://link.springer.com/book/10.1007/978-3-662-45171-7)
- [Härdle, W., Hlávka, Z., 2019. Multivariate Statistics: Exercises and Solutions. 2nd ed., Springer.](https://link.springer.com/book/10.1007/978-3-642-36005-3)

## 評分標準

- 期中考（50%） 04/24 
- 期末考（50%） 06/12 

## 授課時程

| 上課時間 | 課程進度 |
|----------|----------|
| 03/06 | **描述性技術 ＋ 矩陣代數（上）**（Ch 1 精選 + Ch 2 前半）<br>① Ch 1 多變量資料視覺化：Boxplots、Histograms、Kernel Densities（§1.1–1.3）；Scatterplots、Parallel Coordinates（§1.4, §1.7）；Boston Housing 資料導覽（§1.9）<br>② Ch 2 矩陣基本運算（§2.1）<br>③ Ch 2 譜分解與二次式（§2.2–2.3） |
| 03/13 | **矩陣代數（下）＋ 高維隨機變數（上）**（Ch 2 後半 + Ch 3 前半）<br>① Ch 2 矩陣微分、分割矩陣、幾何觀點（§2.4–2.6）<br>② Ch 3 共變異數、相關係數（§3.1–3.2）<br>③ Ch 3 摘要統計量、兩變數線性模型（§3.3–3.4） |
| 03/20 | **高維隨機變數（下）＋ 多變量分配導論**（Ch 3 後半 + Ch 4 §4.1–4.2 前半）<br>① Ch 3 簡單 ANOVA、多元線性模型、Boston Housing（§3.5–3.7）<br>② Ch 4 分配函數與密度函數：邊際分配、條件分配、獨立性、Copula 初步與 Sklar 定理（§4.1）<br>③ Ch 4 動差與特徵函數：期望值、共變異數矩陣之性質、條件期望與偏相關（§4.2 前半） |
| 03/27 | **動差/特徵函數 ＋ 多元常態 ＋ 抽樣分配**（Ch 4 §4.2 後半–§4.5）<br>① Ch 4 特徵函數、累積量、偏態與峰態（§4.2 後半：§4.2.5–4.2.7）<br>② Ch 4 變數變換與 Jacobian（§4.3）；多元常態分配：定義、Mahalanobis 變換、幾何性質（§4.4）<br>③ Ch 4 抽樣分配、中央極限定理、統計量變換之漸近分配（Delta method）（§4.5） |
| 04/10 | **厚尾分配 ＋ Copula ＋ Bootstrap**（Ch 4 §4.6–4.8）<br>① Ch 4 厚尾分配（上）：Generalized Hyperbolic 分配、Student's t 分配及其多變量推廣（§4.6.1–4.6.2, §4.6.6–4.6.7）<br>② Ch 4 厚尾分配（下）：Cauchy、Mixture Model（§4.6.4–4.6.5）；Copula：定義、Gaussian copula、Gumbel–Hougaard copula、Fréchet–Hoeffding 界、d 維推廣（§4.7 精選）<br>③ Ch 4 Bootstrap 方法（§4.8）；Ch 4 習題演練 |
| 04/17 | **多元常態理論 ＋ 估計理論**（Ch 5 + Ch 6）<br>① Ch 5 多元常態基本性質：分割、條件分配、條件近似與多重相關（§5.1）<br>② Ch 5 Wishart 分配、Hotelling's T²、球面與橢圓分配（§5.2–5.4）<br>③ Ch 6 概似函數與 MLE 推導（§6.1）；Cramér–Rao 下界與 Fisher 資訊矩陣（§6.2） |
| 04/24 | **期中考**（範圍：Ch 1–6） |
| 05/01 | **假設檢定**（Ch 7）<br>① Ch 7 概似比檢定：單樣本與多樣本均值檢定（§7.1）<br>② Ch 7 線性假設與 MANOVA（§7.2）<br>③ Ch 7 Boston Housing 實例與習題演練（§7.3） |
| 05/08 | **資料矩陣分解 ＋ 主成分分析（上）**（Ch 10 + Ch 11 前半）<br>① Ch 10 幾何觀點：p 維與 n 維點雲之擬合、子空間關係（§10.1–10.4）<br>② Ch 11 標準化線性組合與 PCA 推導（§11.1）<br>③ Ch 11 PCA 實作與成分解讀（§11.2–11.3） |
| 05/15 | **主成分分析（下）＋ 因素分析（上）**（Ch 11 後半 + Ch 12 §12.1）<br>① Ch 11 PCA 漸近性質、正規化 PCA（§11.4–11.5）<br>② Ch 11 PCA 作為因子方法；Boston Housing 實例（§11.6, §11.8）<br>③ Ch 12 正交因素模型：模型設定、因素負荷與共同性（§12.1） |
| 05/22 | **因素分析（下）＋ 集群分析（上）**（Ch 12 §12.2–12.4 + Ch 13 §13.1–13.2）<br>① Ch 12 因素模型估計：主成分法與最大概似法（§12.2）<br>② Ch 12 因素分數、旋轉策略（Varimax 等）；Boston Housing（§12.3–12.4）<br>③ Ch 13 集群問題定義；距離與相似度測度（§13.1–13.2） |
| 05/29 | **集群分析（下）＋ 判別分析**（Ch 13 §13.3–13.4 + Ch 14）<br>① Ch 13 集群演算法：階層式法（Single/Complete/Average Linkage）、K-means、群數選擇準則（§13.3）<br>② Ch 13 Boston Housing 實例（§13.4）；Ch 14 已知分配之分類法則：Bayes、Fisher 判別（§14.1）<br>③ Ch 14 實務判別法則、誤判率估計、Boston Housing（§14.2–14.3） |
| 06/05 | **計算密集方法——SVM 與 CART**（Ch 20 精選）<br>① Ch 20 支持向量機（SVM）：最大間距分類器、核函數技巧、軟間距推廣（§20.4）<br>② Ch 20 分類與迴歸樹（CART）：遞迴分割、不純度準則（Gini / Entropy）、剪枝（§20.5）<br>③ Ch 20 Boston Housing 實例（§20.6）；與判別分析、集群分析之方法比較 |
| 06/12 | **期末考**（範圍：Ch 7, 10–14, 20 精選） |

<!--

## 授課教師

changytu @ o365.fcu.edu.tw

## 講義
| &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note01.pdf">01</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note02.pdf">02</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note03.pdf">03</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note04.pdf">04</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note05.pdf">05</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note06.pdf">06</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note07.pdf">07</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note08.pdf">08</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note09.pdf">09</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note10.pdf">10</a>&nbsp; | &nbsp;<a href="https://github.com/chang-ye-tu/mva/blob/master/note/note11.pdf">11</a>&nbsp; 
- [Härdle, W., Simar, L., Fengler, M., 2024. Applied Multivariate Statistical Analysis. 6th ed., Springer.](https://link.springer.com/book/10.1007/978-3-031-63833-6)
-->
