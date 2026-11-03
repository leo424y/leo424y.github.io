OpenAI 等人研究弱模型監督強模型的可行性：在若干 NLP、棋類與獎勵建模任務中，強模型能從弱模型產生的標籤學到超過監督者本身的能力，但簡單微調仍無法完整恢復強模型能力。這項研究為「人類未來可能無法直接評估更強 AI」提供實驗切入點，同時也清楚指出監督落差尚未被解決。它不是強模型已可被可靠監督的證明。

### 思與行
* 把監督品質分成標籤準確度、對難題的覆蓋、強模型超越監督者的幅度與失敗可偵測性。
* 在部署前測試強模型是否能利用弱監督的盲點，並加入多來源審核與可驗證任務。

### 參考
* **原始研究**：[Weak-to-Strong Generalization: Eliciting Strong Capabilities With Weak Supervision](https://openai.com/index/weak-to-strong-generalization/)，Burns et al., 2023。
* **延伸研究**：[[可擴展監督不是增加標註數量而已]]、[[監督者能力落差會變成新的權力與責任問題]]。
