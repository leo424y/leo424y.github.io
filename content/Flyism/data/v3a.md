
# **《Decoding Depth of Meditation》（2024）後續研究整理**

**追蹤截止：2026 年 11 月 27 日**

先說主要發展：這篇研究開啟的研究方向，已從「能否用 EEG 辨識內觀深度」，逐漸延伸到三個問題：

1. 禪修深度是否伴隨心跳訊號在大腦中的處理方式改變？
    
2. 禪修越深入時，大腦對外界聲音的反應會變弱，還是變得更清晰？
    
3. 能否建立因人而異的神經指標，作為研究或神經回饋工具？
    

其中最重要的進展，是 **2026 年 11 月更新的心跳相關研究**。它修正了早期研究對心跳誘發電位的解讀，值得優先閱讀。

## **一、原始研究：2024**

**Reggente et al. — Decoding Depth of Meditation: Electroencephalography Insights From Expert Vipassana Practitioners**

- 期刊：_Biological Psychiatry: Global Open Science_
    
- DOI：[10.1016/j.bpsgos.2024.100402](https://doi.org/10.1016/j.bpsgos.2024.100402?utm_source=chatgpt.com)
    
- 2024 年 10 月 16 日線上發表，收錄於 2025 年 1 月期刊。
    
- 研究對象：34 位資深 Goenka 傳統內觀禪修者。
    
- 方法：64 通道 EEG、兩次實驗，禪修者以個人定義的 1–5 分回報當下禪修深度。
    

研究以 theta、alpha、gamma 頻段的腦電活動與有效連結性，結合機器學習預測自我回報的禪修深度。跨實驗時段的預測結果優於隨機基準：高低深度分類的 AUC 約 0.81，連續深度預測的 MAE 約 1.15。

一個重要發現是：**單一腦電頻段或單一腦區不容易辨識禪修深度，結合空間、頻譜與連結性特徵的多變量模型反而較有效。**研究也發現，讓禪修者在察覺覺察力游移時自行回報的 spontaneous emergence 方法，比定時提醒回報更能捕捉禪修過程的變化。

PubMed Central (PMC)+1

## **二、最直接的後續研究**

### **1. 心跳相關神經訊號可能隨禪修深度改變（2025–2026）**

同一實驗資料的延伸分析，不是獨立重複實驗

**早期版本：Heartbeat-Evoked Potentials as a Neural Marker of Meditative Depth**

- 作者：Mihir Nath 等人
    
- 2025 年 OSF 預印本
    
- 研究對象：30 位資料品質符合分析要求的資深內觀者。
    
- 方法：同時記錄 EEG、ECG，分析心跳誘發電位（Heartbeat-Evoked Potentials, HEP）。
    

這個研究明確表示資料來自 Reggente et al.（2024）所描述的同一實驗。早期版本報告，中央頭皮電極 C3 的 HEP 振幅會隨自我回報的禪修深度改變，因而提出 HEP 可能是禪修深度的神經指標。

meditation.mgh.harvard.edu+1

**最新版本：Heartbeat-related spectral power as a Neural Marker of Meditative Depth（2026）**

- 作者：Cedric Cannard、Mihir Nath、Nicco Reggente 等人
    
- 最新版本：2026 年 11 月 3 日
    
- DOI：[10.31219/osf.io/hpcgd_v3](https://doi.org/10.31219/osf.io/hpcgd_v3?utm_source=chatgpt.com)
    
- 研究對象：39 位資深內觀者。
    
- 狀態：OSF 預印本，尚非經同儕審查的正式期刊論文。
    

這個版本進一步比較三種心跳相關腦電訊號：

|指標|含義|最新版本的結果|
|---|---|---|
|HEP|心跳之後的腦電反應振幅|沒有穩定追蹤禪修深度|
|HRSP|心跳之後的時頻功率變化|隨禪修深度增加而下降|
|HRPC|腦電活動與心跳在相位上的一致性|沒有穩定追蹤禪修深度|

最值得注意的是 HRSP：在心跳之後約 20–348 毫秒，後部腦源成分的 10–24 Hz 頻譜功率隨禪修深度提高而下降；峰值約出現在 188 毫秒、15 Hz，效應量 Hedges' g = −0.70。結果通過替代心跳測試、逐一排除參與者的分析，以及部分生理活動混淆因素調整。研究也沒有發現自主神經指標隨禪修深度出現相應變化。

Sciety+2

**這裡有一個不可忽略的版本差異：**2025 年早期稿件強調 HEP 振幅隨深度上升；2026 年最新版本重新分析後，主要結果轉為 HRSP 下降，而 HEP 本身沒有穩定關聯。早期版本的表格還將 η² 列為 5.55；η² 通常應介於 0 與 1，這是值得追查的統計報告異常。因此，引用這條研究線時，應以最新 v3 的結果為主，不宜將早期的 HEP 結果當作已確立的生理指標。

**我的解讀：**這不是說禪修越深，就越感受不到心跳；它比較接近「心跳訊號出現後，大腦對該訊號的特定振盪活動如何改變」。目前也不能直接把 HRSP 下降解釋成更強的平等心、較少執著或更高的內觀智慧。

Sciety+1

### **2. 禪修越深入，大腦對聲音的神經反應可能越清晰（2026）**

與原始研究計畫高度相關的延伸分析；尚非獨立重複驗證

**Nath et al. — Meditation Depth Enhances the Functional Signal-to-Noise Ratio of the Brain**

- DOI：[10.64898/2026.06.30.735351](https://doi.org/10.64898/2026.06.30.735351?utm_source=chatgpt.com)
    
- 2026 年 7 月發表於 bioRxiv，後續有更新版本。
    
- 研究對象：29 位資深內觀者。
    
- 方法：禪修期間播放聲音刺激，同時收集腦電訊號與主觀深度評分。
    

研究以兩種方式衡量大腦的功能訊噪比（functional signal-to-noise ratio, f-SNR）：聲音誘發電位的訊噪比，以及單次聲音反應能否與沒有聲音時的背景腦電活動區分。

結果顯示，深度較高時：

- 聲音誘發電位的訊噪比提高。
    
- 不同次聲音刺激所誘發的神經反應更加一致。
    
- 機器學習更容易從背景腦電中辨識聲音刺激。
    

研究者因此提出，深度禪修可能提高大腦對感官訊號的處理清晰度，而非單純降低對外界刺激的反應。這並不等於禪修者實際聽力變好，而是指腦電反應對聲音刺激的可辨識程度提高。

bioRxiv+1

這篇與原始研究的關聯值得特別留意：2024 年研究的實驗設計包含持續注意力被動聽覺 oddball（SAPO）區塊，並明確表示這部分資料預留給後續 ERP 分析。2026 年聲音研究與這項設計高度吻合，因此更適合視為同一研究計畫的延伸，而非獨立重複驗證。

Advanced Consciousness+1

## **三、其他值得一起閱讀的研究**

以下不是直接複製 2024 年實驗，而是從不同角度補充「內觀如何改變腦部動態」。

### **3. 不同禪修方法具有不同的 alpha 腦波時間動態（2026）**

**Ventura et al. — Neurodynamic Profiles in the Alpha Band Distinguish Different Forms of Meditation**

- 期刊：_Neuroscience of Consciousness_
    
- DOI：[10.1093/nc/niag036](https://doi.org/10.1093/nc/niag036?utm_source=chatgpt.com)
    
- 發表日期：2026 年 7 月 7 日
    
- 研究對象：15 位 Vipassana 禪修者、19 位 Shoonya 禪修者。
    

研究不只比較 alpha 波的平均功率，也分析其時間上的變化程度與規律性，包括：

- Peak Frequency Sliding（PFS）：alpha 振盪頻率的時間變化。
    
- Power Sliding（PS）：alpha 振盪功率的時間變化。
    
- Coefficient of Variation（CV）：變異程度。
    
- Permutation Entropy（PE）：時間序列的不規則程度。
    

結果顯示，Vipassana 組的 alpha 頻率與功率動態具有較低的變異程度與排列熵；相較於平均腦波功率，這些時間動態指標更能區分兩種禪修方式。

PMC+1

這篇的意義在於：**腦波不只要看某一頻段有多強，也要看它如何隨時間變化。**對身體掃描式內觀而言，注意力在不同身體部位之間規律移動，可能與非定向覺察的時間組織不同。

但要注意，這項研究採用既有資料集的再分析，並非全新招募的獨立樣本；研究也不是在測量個人當下禪修深度。

OUP Academic+1

### **4. 禪修腦波研究的統合分析：alpha、beta、gamma 有整體效應，但異質性很大（2026）**

**Yan et al. — EEG Oscillatory Correlates of Meditation Practice: A Systematic Review and Exploratory Meta-analysis**

- 期刊：_Neuroscience_
    
- DOI：[10.1016/j.neuroscience.2026.07.012](https://doi.org/10.1016/j.neuroscience.2026.07.012?utm_source=chatgpt.com)
    
- 發表日期：2026 年 9 月 11 日
    

這篇系統性回顧與探索性統合分析發現：

|頻段|統合分析結果|
|---|---|
|Alpha|整體正向效應|
|Beta|整體正向效應|
|Gamma|整體正向效應|
|Theta|沒有顯著的整體效應|

研究也發現，測量狀態（禪修中或休息時）可能影響效應量；不過相關調節效果在敏感度分析中並不穩定。禪修類型與修行經驗也沒有顯示為顯著調節因子。作者強調，目前研究之間存在明顯異質性，需要更標準化的實驗與長期追蹤。

PubMed+1

這也提醒我們，不應把「alpha 增加」或「gamma 增加」當作所有內觀者都適用的深度指標。

### **5. 從腦電辨識走向個人化神經回饋（2026）**

**Brandmeyer, Simmons & Reggente — Toward Personalized Neurofeedback for Meditation**

- 期刊：_Mindfulness_
    
- 發表日期：2026 年 11 月 25 日
    
- DOI：[10.1007/s12671-026-03031-1](https://doi.org/10.1007/s12671-026-03031-1?utm_source=chatgpt.com)
    

這是概念性論文，而非新實驗。作者主張，神經回饋不應讓所有人追求相同的腦波指標，而應根據每位禪修者的個人神經特徵、認知差異與修行脈絡進行校準。

作者也提醒，目前神經回饋協助禪修的證據仍有限，尚不能確定它能帶來持久、可轉移的禪修能力提升。技術應該是暫時的輔助，而不是取代禪修者本身的覺察與練習。

Springer Nature Link

## **四、研究脈絡總結**

以下是依研究問題整理的發展方向，不代表所有結果已獲獨立驗證。

|研究方向|重要發現|目前證據狀態|
|---|---|---|
|EEG 多變量解碼|可預測禪修者自評的深度|2024 同儕審查論文|
|心跳相關腦電|HRSP 隨深度增加而下降|2026 預印本、同一研究資料延伸|
|聲音處理|深度較高時，聲音神經反應更清晰|2026 預印本、延伸分析|
|Alpha 時間動態|不同禪修方法呈現不同規律性|2026 同儕審查論文、既有資料再分析|
|EEG 統合分析|alpha、beta、gamma 有整體正向效應，結果仍異質|2026 系統性回顧與統合分析|
|個人化神經回饋|可能需要依個人特徵校準|2026 概念性論文|

## **五、對 Goenka 內觀禪修者的研究啟發**

我認為目前最值得追蹤的，不是「哪一種腦波代表禪修比較深」，而是以下三個研究問題：

**1. 身體感受與大腦內感受處理之間的關係**

HRSP 研究提供了一個新的研究方向：身體訊號持續存在，但大腦對心跳訊號的特定處理方式會隨自評深度改變。未來可以進一步研究，這種變化是否與身體感受的清晰度、注意力穩定性或平等心有關。目前還不能把這些概念直接畫上等號。

**2. 對內在與外在刺激的覺察，是否能同時變得更清晰？**

聲音 f-SNR 研究值得注意。它暗示深度較高的禪修狀態，不一定是對所有外界刺激都變得遲鈍。未來可以比較聲音、呼吸、心跳、觸覺等不同刺激，看它們的神經反應是否呈現不同規律。

**3. 禪修深度是否應該被視為多個維度，而不是單一數值？**

2024 年研究使用 1–5 分深度評分，但禪修經驗可能包含注意力穩定度、身體感受清晰度、覺察力、心的平靜程度與反應性等不同面向。這些面向未必同步變化。後續研究若能將主觀經驗描述得更細緻，可能比單純預測一個「深度分數」更有研究價值。

**我的閱讀優先順序：**

1. [Heartbeat-related spectral power as a Neural Marker of Meditative Depth（2026 v3）](https://doi.org/10.31219/osf.io/hpcgd_v3?utm_source=chatgpt.com) — 最重要的直接延伸。
    
2. [Meditation Depth Enhances the Functional Signal-to-Noise Ratio of the Brain（2026）](https://doi.org/10.64898/2026.06.30.735351?utm_source=chatgpt.com) — 理解禪修深度與外界感官處理。
    
3. [Neurodynamic Profiles in the Alpha Band（2026）](https://doi.org/10.1093/nc/niag036?utm_source=chatgpt.com) — 理解身體掃描式內觀的時間動態。
    
4. [EEG Oscillatory Correlates of Meditation（2026）](https://doi.org/10.1016/j.neuroscience.2026.07.012?utm_source=chatgpt.com) — 建立整體 EEG 研究的證據背景。
    
5. [Toward Personalized Neurofeedback for Meditation（2026）](https://doi.org/10.1007/s12671-026-03031-1?utm_source=chatgpt.com) — 思考神經科學研究如何回饋禪修實踐。
    

**總結：**2024 年研究的主要貢獻，是證明資深內觀者自我回報的禪修深度，能透過多變量 EEG 模式被一定程度地解碼。到 2026 年，研究已進一步探索心跳訊號、外界感官處理與腦波時間動態。但目前仍缺少真正獨立的重複驗證，也尚未證明某個腦電指標可以客觀代表禪修的深度、平等心或智慧。對內觀研究而言，最有價值的方向或許是讓第一人稱經驗描述與第三人稱神經測量彼此校準，而不是讓其中一方取代另一方。