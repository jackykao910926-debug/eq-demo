# 文獻閱讀清單與來源索引

更新／查核：2026-10-12。以下是主題導向清單，不是窮盡式系統性回顧。以作者、出版社、研究機構、NIST 等來源核對；「核對摘要／書目」不代表已讀完整全文。未取得全文者不據以宣稱詳細實驗結果。

## 先讀順序

第一輪：R02 → R01 第 3–6 章 → R04 → R07 → R08 → R06。第二輪：R03、R05、R09。進階選讀：R10–R14。每篇筆記只先回答：改了什麼、控制什麼、量了什麼、結果可信到哪裡、能搬到我的研究哪一段。

## R01｜原研究基礎，必讀

**陳國益 / Chen Kuoyi (2021). 緊湊型六極柱 ECR 離子源研究及在等離子推進器之應用 / The Research on the Compact Hexapole ECR Ion Source and Application in the Plasma Thrusters. 清華大學博士論文。**

來源：使用者提供的 192 頁 PDF；不公開再散布全文。

先讀第 3 章結構、第 4–5 章磁場、第 6 章實驗、第 7 章總結，再回補第 2 章。重要位置：原文印刷 p.109–110（PDF 128–129）幾何；p.126 起探針與定性觀察限制；p.131–138 推力量測；p.137 表 6-1；p.154 总結。

用途：建立可重現的設計基準，並識別尚未量化的 Xe、磁材公差、密度、穩定操作證據。狀態：已核對相關正文、表格與圖頁。

## R02｜電推入門與公式，必讀

**Goebel, D. M., & Katz, I. (2008). Fundamentals of Electric Propulsion: Ion and Hall Thrusters. Wiley / JPL Space Science and Technology Series.**

官方公開章節入口：https://descanso.jpl.nasa.gov/SciTechBook/st_series1_chapter.html

先讀第 2 章推進原理、第 3 章基礎電漿、第 6 章中空陰極、第 7 章 Hall；需要時查 Appendix B 的氣體換算。用途：分清電離／加速／中和，理解推力、比衝、功率分母及 Xe 單位。狀態：已核對官方書籍與章節入口；本輪未逐章細讀整書。

## R03｜背景壓力，不可跳過

**Wachs, B., & Jorns, B. (2020). Background pressure effects on ion dynamics in a low-power magnetic nozzle thruster. Plasma Sources Science and Technology, 29, 045002.**

DOI：https://doi.org/10.1088/1361-6595/ab74b6

作者實驗室來源：https://pepl.engin.umich.edu/project/electron-cyclotron-resonance-thrusters/

用途：說明為何真空槽背景氣體是研究變因，不只是設備設定；規劃壓力–流量圖、量測位置與設施效應討論。狀態：已核對作者實驗室書目及文章摘要，期刊全文連結本輪未成功展開；定量引用前另讀全文。

## R04｜最值得模仿的受控實驗寫法，必讀

**Boni, F., Désangles, V., & Jarrige, J. (2022). Experimental characterization of thrust production mechanisms in a magnetic nozzle ECR thruster. Journal of Electric Propulsion, 1, 33.**

全文：https://link.springer.com/article/10.1007/s44205-022-00034-7

文章以低功率 Xe ECR，比較兩種磁拓樸並區分總推力、壁面作用和磁體作用。最值得學的是控制條件、功率參考平面、背景誤差和因果論述，而不是照抄一個最佳值。

對應本研究：A/B 對照、正反向 RF 功率與推力分支。狀態：已閱讀出版社全文的實驗配置及相關討論。這是 ONERA 團隊的文章，不是陳國益博士論文的同一份研究。

## R05｜工程化、放大與長時間測試

**Désangles, V., et al. (2023). ECRA thruster advances: 30W and 200W prototypes latest performances. Journal of Electric Propulsion, 2, 10.**

全文：https://link.springer.com/article/10.1007/s44205-023-00046-x

用途：以工程角度串起原型迭代、功率放大、測試設施差異、內導體侵蝕及穩定性。本文的總測試時間 100 h 不等於單段連續 100 h；正文記述前段分日操作，後段連續 64 h。不同表格的最佳性能亦不一定來自同一工況。

對應本研究：設計迭代紀錄、熱／侵蝕觀察、30 min 試驗的限制、避免將 2021 年比較當成現況。狀態：已閱讀出版社全文相關章節。

## R06｜直接推力量測品質，必讀

**Polk, J. E., Pancotti, A., Haag, T., King, S., Walker, M., Blakely, J., & Ziemer, J. (2017). Recommended Practice for Thrust Measurement in Electric Propulsion Testing. Journal of Propulsion and Power, 33(3), 539–555.**

DOI：https://doi.org/10.2514/1.B35564

作者稿：https://pmc.ncbi.nlm.nih.gov/articles/PMC7839308/

書目：https://pubmed.ncbi.nlm.nih.gov/33510551/

用途：推力架型式、校正、漂移、寄生力、解析度與不確定度、結果報告應揭露的資訊。先讀校正、誤差和 reporting 三部分，再决定是否要自建推力架。狀態：已核對摘要與公開作者稿索引中的校正、穩定性和報告建議內容；全文頁偶有存取驗證。

## R07｜探針製作方法，必讀

**Li, P., Hershkowitz, N., & Severn, G. (2021). Building Langmuir Probes and Emissive Probes for Plasma Potential Measurements in Low-Pressure, Low-Temperature Plasmas. Journal of Visualized Experiments.**

DOI：https://doi.org/10.3791/61804

出版社中文方法頁：https://www.jove.com/cn/t/61804/building-langmuir-probes-emissive-probes-for-plasma-potential

用途：對沒有探針製作經驗的學生，先了解材料、探頭、絕緣、偏壓與低溫低壓電漿量測流程。這不是六極柱強磁場的通用修正方案；局部 B、射頻干擾、鞘層與分布函數仍需另外檢查。

狀態：已核對出版社題名、作者、日期、方法摘要；本輪未取得完整影片及全部 protocol。實作前由熟悉診斷的老師或同儕審核電路與適用條件。

## R08｜不確定度寫作，必讀

**Taylor, B. N., & Kuyatt, C. E. (1994). Guidelines for Evaluating and Expressing the Uncertainty of NIST Measurement Results. NIST Technical Note 1297.**

官方入口：https://www.nist.gov/pml/nist-technical-note-1297

合成標準不確定度：https://www.nist.gov/pml/nist-technical-note-1297/nist-tn-1297-5-combined-standard-uncertainty

傳播法則：https://www.nist.gov/pml/nist-technical-note-1297/nist-tn-1297-appendix-law-propagation-uncertainty

用途：建立量測方程、分離重複性與校正／定位等分量、處理共變異數、交代涵蓋因子。不要把三次重複的標準差、儀器解析度、標準不確定度和 95% 區間寫成同一件事。狀態：已核對官方方法頁。

## R09｜磁材設定的技術文件

**COMSOL Multiphysics 6.3 Documentation, Ampère’s Law — Remanent Flux Density.**

官方文件：https://doc.comsol.com/6.3/doc/com.comsol.help.acdc/acdc_ug_magnetic_fields.08.032.html

用途：核對 Br、μrec 與方向場的本構關係，避免把 Hcb、Hcj、M 混用。實際材料的牌號、溫度與退磁曲線仍要向供應商取得；這份文件不是你的磁鐵規格。狀態：已核對官方對應段落。

## R10｜電子加熱與進階模擬，選讀

**Porto, J., Elias, P.-Q., & Ciardi, A. (2023). Anisotropic electron heating in an electron cyclotron resonance thruster with magnetic nozzle. Physics of Plasmas, 30, 023506.**

作者預印本：https://arxiv.org/abs/2301.11411

用途：了解電子平行／垂直能量與簡化粒子軌跡模型的限制。適合論文背景和討論，不建議把重做完整 kinetic/PIC 模型列為 11 個月必做工作。狀態：已核對預印本摘要與期刊題名；本輪未完整細讀數值算法。

## R11｜較新磁拓樸比較，選讀

**Boyé, C., Navarro-Cavallé, J., & Merino, M. (2025). Ion current and energy in the magnetic arch of a cluster of two ECR plasma sources. Journal of Electric Propulsion, 4, 10.**

全文：https://link.springer.com/article/10.1007/s44205-025-00100-w

作者資料來源：https://researchportal.uc3m.es/display/act574745

用途：學習磁拓樸改動下，離子電流、能量與羽流發散度可能互有取捨；「某個指標上升」不等於整體性能全面提高。不要因此把兩台推進器叢集也加進本次主線。

狀態：已核對出版社和作者機構摘要與書目，未重算原始資料。

## R12｜微波線纜如何污染推力量測，選讀

**Wachs, B. N., & Jorns, B. A. (2022). Sub-millinewton thrust stand and wireless power coupler for microwave-powered small satellite thrusters. Review of Scientific Instruments.**

DOI：https://doi.org/10.1063/5.0088831

作者提供 PDF：https://pepl.engin.umich.edu/pdf/2022_RSI_Wachs.pdf

用途：在決定直接推力分支前，評估線纜剛性、熱漂移及耦合器設計成本。無線耦合是參考技術，不是本計畫一定要重新開發的子計畫。狀態：作者實驗室書目已核對；PDF 本輪未成功展開，詳細數值需另讀全文。

## R13｜ECR 範圍與新近背景，選讀

**Svarnas, P. (2025). Electron cyclotron resonance (ECR) plasmas: A topical review through representative results obtained over the last 60 years. Journal of Applied Physics, 137, 070701.**

出版社：https://doi.org/10.1063/5.0249342

用途：快速理解工業電漿、離子源與推進器為何都使用 ECR，避免把單一同軸磁噴管架構說成所有 ECR。狀態：已核對出版社摘要及書目；屬回顧文章，定量設計應回查其引用的原始研究。

## R14｜傳統同軸 ECR 幾何優化，選讀

**Cannat, F., Lafleur, T., Jarrige, J., Chabert, P., Elias, P.-Q., & Packan, D. (2015). Optimization of a coaxial electron cyclotron resonance plasma thruster with an analytical model. Physics of Plasmas, 22, 053503.**

DOI：https://doi.org/10.1063/1.4920966

用途：理解單環同軸 ECR 中，源長度、天線和操作參數如何形成工程變因，作為 A/B 研究的歷史背景。本文書目亦見後續 ECR 研究引用；詳細性能須核對是直接推力量測還是羽流推估。

狀態：已核對題名、作者、期刊與 DOI；本輪未成功取得出版社全文，不引用未核對的細部結果。

## C01｜計畫工作需求（非公開全文）

使用者先前提供之計畫工作需求頁。用途：需求追溯與排程，不是物理理論文獻。實際決標日、履約計時及驗收認定須由正式文件與窗口確認。本 repo 不保存原契約、簽章或個人資料。

## 讀書筆記格式

每篇建立：完整書目、研究問題、構型／工質／功率、控制條件、實際量測量、推估量、誤差來源、與本研究可比性、想採用的方法、不可直接照搬之處。讀完一篇應產出一頁筆記與一項設計／試驗決策，而非只保存 PDF。
