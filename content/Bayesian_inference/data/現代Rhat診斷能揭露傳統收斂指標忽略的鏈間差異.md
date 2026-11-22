Vehtari、Gelman、Simpson、Carpenter 與 Bürkner 提出 rank-normalization、folding 與 localization 等改進，指出傳統 R-hat 在厚尾分布或鏈間變異數不同時可能漏掉收斂問題。作者建議以多條鏈的 rank plot 等診斷，配合有效樣本數與 Monte Carlo 誤差評估抽樣品質。這項工作提醒研究者：MCMC 的輸出不是因為程式順利跑完就自動可信，必須檢查演算法是否充分探索目標分布。

## 思與行
* 同時檢查多鏈軌跡、rank plots、R-hat、有效樣本數與 Monte Carlo standard error，不要只看單一指標。
* 若診斷不佳，先思考模型參數化、先驗尺度、多峰或識別性問題，而不是單純增加迭代次數。

## 參考
* 論文與 Aalto 研究紀錄：[Vehtari et al. (2021), “Rank-normalization, folding, and localization: An improved R-hat for assessing convergence of MCMC”](https://research.aalto.fi/en/publications/rank-normalization-folding-and-localization-an-improved-r-hat-for/)。
* 延伸：[[計算收斂只是可信推論的必要條件而非充分條件]]、[[貝葉斯分析是一個反覆建模與檢查的工作流程]]。
