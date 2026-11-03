Christiano 等人示範如何讓人類比較兩段行為軌跡，再把比較結果用作獎勵模型的訓練訊號，讓強化學習系統在沒有直接提供完整獎勵函數的情況下學習複雜任務。這個方法開啟了以人類偏好監督強化學習的重要路線，也成為後來 RLHF 的關鍵前身。它同時把新問題帶進來：偏好標註究竟代表什麼、標註者是否有能力判斷、獎勵模型是否只學到表面線索？

### 思與行
* 把偏好回饋視為有噪音、受情境影響的觀察資料，而不是人類價值的直接讀取。
* 記錄標註者背景、任務說明、比較條件與不確定性，並測試不同群體是否產生系統性分歧。

### 參考
* **原始論文**：[Deep Reinforcement Learning from Human Preferences](https://proceedings.neurips.cc/paper/7017-deep-reinforcement-learning-from-human-preferences)，Christiano et al., NeurIPS 2017。
* **延伸研究**：[[人類偏好只是價值的局部證據]]、[[人類偏好只是價值的局部證據]]。
