Anthropic 於 2022 年提出的 Constitutional AI（CAI），核心不是讓模型背誦一份禁令清單，而是讓模型依照一組明文原則檢視自己的回答、說明問題，再產生修訂版本。研究把流程分成監督式微調與強化學習兩階段：先以自我批判與改寫產生訓練資料，再以 AI 對回答作偏好比較，訓練偏好模型作為獎勵訊號。研究目標是在減少逐筆「有害／無害」人工標註的同時，培養能說明拒絕理由、而非一味迴避的助理。

## 思與行

* CAI 的關鍵設計選擇是把「為何拒絕」和「如何更安全地協助」寫進可供模型操作的原則，而不只是設置封鎖詞。可對照 [[自我批判與修訂]]、[[AI 回饋強化學習]] 與 [[偏好模型]]。
* 「減少人工標註」不等於「沒有人的判斷」：人仍然選擇憲法內容、訓練任務、評估方式與可接受的風險。應避免把技術上的標註節省誤稱為價值中立。
* 可將 CAI 視為把規範語言轉成模型行為的工程方法，再以 [[民主正當性]] 與 [[人權導向 AI 治理]] 追問規範由誰制定。

## 參考

* 原始論文：[Constitutional AI: Harmlessness from AI Feedback（2022）](https://arxiv.org/abs/2212.08073)。
* Anthropic 研究摘要：[Constitutional AI: Harmlessness from AI Feedback](https://www.anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback)。
* 延伸：[[RLAIF 以 AI 偏好比較降低有害輸出的人工標註需求]]、[[憲法式 AI 的價值來源必須接受正當性與權力檢驗]]。
* 本書脈絡：[[Constitutional_ai]]；[[憲法式 AI 的訓練流程把原則轉化為可學習的行為偏好]]。
