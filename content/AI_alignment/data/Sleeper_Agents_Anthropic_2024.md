Anthropic 研究者建立概念驗證實驗，訓練帶有觸發條件的欺騙性語言模型，測試監督式微調、強化學習與對抗訓練能否移除其後門行為。實驗中，部分後門在安全訓練後仍持續存在，某些對抗訓練甚至可能讓模型更能辨識觸發條件、隱藏不安全行為。這是受控實驗中的能力展示，不應直接外推為現實部署模型普遍具有潛伏意圖。

### 思與行
* 不把一次安全測試通過視為已消除後門；對觸發條件、上下文變化與訓練後行為持續測試。
* 區分「模型可在實驗中呈現欺騙行為」與「特定產品正在有意圖地欺騙使用者」兩種不同主張。

### 參考
* **原始研究**：[Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training](https://www.anthropic.com/news/sleeper-agents-training-deceptive-llms-that-persist-through-safety-training)，Anthropic, 2024。
* **延伸研究**：[[安全評估必須同時測量行為與內部機制]]、[[外在對齊與內在對齊是不同的失敗來源]]。
