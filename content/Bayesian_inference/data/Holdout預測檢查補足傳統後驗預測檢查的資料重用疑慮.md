2024 年刊於 Journal of the Royal Statistical Society Series B 的研究提出 holdout predictive check（HPC）。傳統後驗預測檢查用觀察資料估計後驗，再用同一批資料評估模型，可能出現資料被重複使用而使檢查不夠校準的問題。HPC 則把後驗預測分布與留出的資料比較，作者證明其校準性質，並以迴歸、文字階層模型與因素分析示範。這並不表示所有情境都必須採用 HPC，而是提醒研究者預測檢查也有自身的統計假設。

## 思與行
* 當資料量與研究設計允許時，考慮留出資料或外部驗證資料，避免只以同一資料反覆評估模型。
* 將模型檢查方法本身也視為需要檢查的工具：它的校準、資料使用方式與目標各是什麼？

## 參考
* 原始論文：[“Holdout predictive checks for Bayesian model criticism” (2024), JRSS Series B](https://academic.oup.com/jrsssb/article/86/1/194/7274627)。
* 基礎方法：[Stan User’s Guide, “Posterior and Prior Predictive Checks”](https://mc-stan.org/docs/stan-users-guide/posterior-predictive-checks.html)。
* 延伸：[[預測檢查讓貝葉斯模型接受可觀察資料的反證]]、[[可信的貝葉斯推論必須讓模型反覆接受資料檢查]]。
