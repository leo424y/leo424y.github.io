# 傳統內觀冥想熟練度與經驗解離腦電研究（2018）之後續研究進展與方法學演進

Ratna Jyothi Kakumanu、Bindu M. Kutty 等人於 2018 年在《Biological Psychology》發表的《Dissociating meditation proficiency and experience dependent EEG changes during traditional Vipassana meditation practice》，首次在傳統葛印卡（S.N. Goenka）內觀架構下透過非線性腦電複雜度指標，將「冥想熟練度（proficiency）」與單純的「練習經驗時長（experience duration）」加以解離。截至 2026 年的後續文獻顯示，該研究已衍生出四條明確的推進主軸：其一為印度國家心理健康與神經科學研究院（NIMHANS）原班團隊向認知任務（P300）、熟練度心理計量表與皮質相位滑移（phase slips）的延伸；其二為該團隊與 Georg Northoff 等學者的跨國合作，重新剖析 2018 年原始內觀專家腦電數據並跨足四種冥想傳統，導入內在神經時間尺度（INT）、非週期性 1/f 參數化與機器學習分類；其三為外部獨立團隊運用高階機器學習解碼內觀主觀冥想深度，並結合腦磁圖（MEG）檢驗腦臨界動力學（criticality）；其四為 2025 年多篇系統性綜述對 2018 年研究進行效應量彙整，同時指出「狀態上升、特質下降」的複雜度悖論與實驗基線污染等方法學瓶頸。

在評估上述後續成果時，需同步考量兩項證據成熟度限制。首先，2025 至 2026 年間多項針對內觀相位滑移、跨傳統神經動力學與非週期性測量信度的核心研究，目前仍屬於 bioRxiv 或 Preprints.org 預印本，尚未完成正式同儕審查。其次，近年腦電方法學研究已指出，若未先將頻譜中的非週期性 1/f 背景活動分離，單純依據傳統窄頻帶功率解讀 2018 年或早期研究結果，容易將寬頻變化或皮質興奮—抑制平衡位移誤判為真實的神經振盪差異。

## 2018 年原始研究的基準發現與遺留課題

為理解後續研究的問題意識，需先對照 Kakumanu 等人（2018）的實驗設計與核心結論。該研究使用 128 通道 EGI 高密度腦電系統，記錄葛印卡體系不同層級的內觀修行者依序進行觀息法（Anapana-Sati，屬專注冥想 FA）、內觀（Vipassana，屬開放監測冥想 OM）與慈悲觀（Metta-Bhavna，屬慈愛冥想 LK）。根據後續系統性綜述與原團隊重分析文獻所揭露的樣本細節，該研究納入初學者（Beginners，n = 24，平均 2.2 年經驗）與內觀教師（Teachers，n = 21，平均 16.3 年、15,349 小時練習經驗），而重分析研究亦記錄該原始數據集中共有 43 位內觀專家（含教師與資深修行者，其中一項重分析納入了 22 位資深內觀修行者數據）。

在腦電特徵上，該研究呈現了傳統頻譜與非線性動態的結構性分工。在傳統頻譜功率方面，資深者與教師相較於初學者，整體展現出特質性（trait）的 Delta（1–4 Hz）、Theta-Alpha（6–10 Hz）與低 Gamma 頻段功率升高（亦見於慈悲觀期間的 Theta-Alpha 與低 Gamma 功率提升）；組內比較方面，專注冥想相較於靜息態伴隨 Alpha、Beta 與 Delta 功率上升，而組間 Theta 功率則未達顯著差異。真正將高熟練度（教師組）從單純經驗累積中區隔出來的關鍵指標是排列熵（Permutation Entropy, PE）與 Higuchi 分形維度（Higuchi Fractal Dimension, HFD）：初學者僅在內觀（OM）期間出現 PE 與 HFD 上升，唯有教師組在觀息法、內觀與慈悲觀各階段及狀態轉換時，皆呈現相較於靜息基線一致的網路複雜度上升，同時教師組在靜息基線下的特質性複雜度反而低於初學者與對照組。這項結果留下了三個待解問題：熟練度效應能否遷移至冥想以外的認知作業、熟練度如何建立標準化心理計量工具，以及此複雜度模式在跨傳統與新訊號分解方法下是否穩健。

## NIMHANS 原團隊的縱深延伸：認知遷移、量表建構與相位滑移

延續 2018 年的解離架構，Kakumanu、Ajay Kumar Nair、Arun Sasidharan 與 Bindu M. Kutty 等 NIMHANS 原班團隊將研究脈絡推展至任務態認知控制、熟練度量表開發與微觀皮質動力學三個面向。

在認知功能遷移與心理福祉驗證方面，Kakumanu 等人（2019）於《Progress in Brain Research》發表〈State-trait influences of Vipassana meditation practice on P3 EEG dynamics〉，利用刺激辨別（如 oddball）範式檢驗內觀練習對 P300 事件相關電位的調節效應。研究結果指出，冥想練習的「量」與「質」皆會影響認知加工期間的腦電動態，且在認知任務前進行冥想可提供額外的狀態—特質疊加效應，協助因應特定的注意力與認知資源分配需求。同一團隊的 Nirmala Maruthai 與 Sasidharan 亦透過 P300 預印本研究指出，較高的冥想熟練度有助於個體從干擾刺激中抽離（disengaging from distraction）。與電生理同步，Nair 等人（2018）在《International Journal of Wellbeing》探討主觀心理福祉的提升究竟歸因於練習熟練度抑或累積時長，為腦電指標提供了行為與心理層面的對照。

針對 2018 年研究僅能以「初學者／資深者／教師」的身分分組作為熟練度代理指標的限制，Ramajayam Govindaraj、Kakumanu、Rahul Venugopal 與 Mariyamma Philip 等人開發並驗證了《內觀熟練度量表》（VIPASSANA Proficiency Scale）。該成果於 2023 年 Mind, Brain, and Consciousness 研討會首度發表後，於 2026 年正式刊載於《Consciousness, Cognition, and Contemplative Sciences》（Studies in Rhythm Engineering）專書系列，為後續評估內觀熟練度提供了專門的心理計量工具。此外，該實驗室亦持續延伸臨床與日常意識研究，包含證實長期正念冥想者的脫氫表雄酮（DHEA）濃度與 N3 慢波深睡期呈正相關（Nagendra et al., 2022），以及透過經驗取樣法探討冥想者心智漫遊的質性差異（Mishra et al., 2026）與呼籲關注冥想者神經生理個體差異（Gururajan & Sasidharan, 2026 預印本）。

在微觀腦電訊號解析上，Kakumanu 等人與華盛頓大學 Ceon Ramon 合作，於 2025 年在 bioRxiv 發表預印本〈EEG Phase Slips Reveal Detailed Brain Activity Patterns of Novice Vipassana Meditators During Decision Making Tasks〉。研究將焦點從冥想靜坐轉向決策與物體辨識任務下的「腦電相位滑移率」（Phase Slip Rates, PSRs），結果顯示初學內觀冥想者（NVP）相較於對照組（NMC）展現更快的物體辨識速度，且相位滑移率可作為區辨兩組在任務態下認知差異的量化生物標記。

## 跨傳統整合與新計算框架：時間尺度、非週期性 1/f 與機器學習

2024 至 2026 年間，NIMHANS 團隊與 Georg Northoff、Steven Laureys 等學者展開跨國合作，將 2018 年的內觀發現納入跨冥想傳統的統一計算框架，導入內在神經時間尺度（Intrinsic Neural Timescales, INT）、非週期性（aperiodic 1/f）參數化以及機器學習分類。

最直接的數據延續見於 Saketh Malipeddi、Sasidharan、Kutty 與 Northoff 等人的系列研究。該團隊先於 2024 至 2025 年發布 bioRxiv 預印本，並於 2026 年在《Communications Biology》正式發表〈Non-duality in brain and experience of advanced meditators-key role for intrinsic neural timescales〉。該研究不僅探討進階冥想者在經驗主客二分消融（non-duality）時的神經基礎，更直接重新分析了 2018 年同一批以 128 通道 EGI 系統採集的 43 位內觀專家數據，指出內在神經時間尺度（INT）在進階冥想者的非二元體驗與腦動態中扮演關鍵角色。

為釐清 Kakumanu 等人（2018）觀察到的非線性與頻譜模式是否具跨傳統普遍性，Prakash Shrimali、Sasidharan、Malipeddi 與 Bianca Ventura 等人於 2025 至 2026 年發表 bioRxiv 預印本〈Similar States, Different Paths: Neurodynamics of diverse meditation techniques〉。研究整合 170 名受試者（121 位進階冥想者與 49 位對照組）的高密度腦電數據，涵蓋內觀（Vipassana）、Brahma Kumaris Raja Yoga、Heartfulness 與 Isha Yoga 四種傳統，並同時提取振盪、非週期（1/f 斜率）、非線性（PE、HFD、SVD entropy）與時間尺度特徵。隨機森林分類器在區分內向冥想狀態與外向認知任務時，達到 91% 的總體分類準確率。該預印本更進一步揭露經驗程度帶來的特徵權重轉移：進階冥想者的分類準確率高於對照組（92% 對比 85%），且主要由「非線性與非週期性特徵」驅動區分，對照組則以「振盪與時間尺度特徵」為主。在各傳統比較中，內觀在冥想對比任務時展現出四種傳統中最大幅度的 Alpha 功率提升；同一合作群的 Ventura 等人（2026）亦於《Neuroscience of Consciousness》證明，僅透過 Alpha 頻帶的神經動力學輪廓即可區辨不同形式的冥想。

延續多維特徵思路，Praerna Chowdhury、Govindaraj、Sasidharan、Northoff 與 Kutty（2026 年 bioRxiv 預印本）發表〈The Neurodynamic Core of Meditation: Dissociating Meditation from Rest and Task in a Reliability-based EEG study〉。該研究明確援引 Kakumanu 等人（2018）的基礎，並運用 IRASA 演算法分離非週期斜率與截距，同時計算去趨勢波動分析（DFA）、HFD 與 PE。初步結果顯示，相較於靜息與任務狀態，冥想一致伴隨 Theta–Alpha 功率升高、IRASA 非週期截距上升，以及 DFA、HFD 與 PE 的系統性調控，試圖從測量信度角度界定冥想的核心神經動力學架構。同合作團隊亦於 2026 年在《Mindfulness》針對 Isha Yoga 觀息冥想發表時間動態研究，定位出腦電波變化在開始冥想後第 7 分鐘達到高峰。

## 外部獨立研究：冥想深度動態解碼與 MEG 臨界動力學

在 NIMHANS 體系之外，獨立研究團隊亦針對內觀專家的主觀冥想深度、情緒抑制與臨界腦動力學提出關鍵驗證，彌補了 2018 年研究缺乏即時主觀經驗追蹤與空間源定位的不足。

針對主觀冥想深度的連續解碼，Nicco Reggente、Christian Kothe 與 Tim Mullen 等人於 2024 年底至 2025 年初在《Biological Psychiatry Global Open Science》發表〈Decoding Depth of Meditation: Electroencephalography Insights From Expert Vipassana Practitioners〉。研究針對 34 位內觀專家進行兩次獨立場次的腦電記錄，並為避免傳統定時音訊探詢（probing）打斷冥想體驗，設計了由受試者自主回報 1 至 5 分深度的「自發浮現法」（spontaneous emergence）。研究團隊透過機器／深度學習模型融合皮質源空間（source-level）的 Theta（4–7 Hz）、Alpha（8–12 Hz）與 Gamma（31–42 Hz）活動及有效連結（effective connectivity）資訊，成功跨未見過的實驗場次顯著預測時變冥想深度；且自發浮現法的解碼準確度與場後心理結果指標的相關性均優於傳統探測法，而傳統電極層級分析或僅鎖定預設模式網路（DMN）的方法則無法捕捉該多變量動態。

在認知控制與情緒調控的任務態延伸上，Catherine I. Andreu 等人（2019，《Scientific Reports》）採用情緒 Go/Nogo 任務檢驗經驗豐富的內觀冥想者，發現其具備更強的反應抑制能力，並伴隨額中線 Theta 活動的降低，顯示長期內觀練習與情緒反應控制增強之間的電生理關聯。

在非線性複雜度與臨界動力學（criticality）的延伸上，多項外部研究將 Kakumanu 等人（2018）的指標擴展至長程時間相關性（LRTC）與跨模態源空間分析。Walter 與 Hinterberger（2022，《Neuroscience of Consciousness》）在 30 位平均擁有 20 年（6,498 小時）經驗的資深冥想者中，計算 DFA、多尺度熵（MSE）與 HFD，發現在無念空性（Thoughtless emptiness）狀態下相較閉眼靜息出現 DFA 下降（d = -0.37）與 HFD 上升（d = 0.23），專注冥想相較閉眼靜息亦呈現樣本熵上升（sf = 1 時 d = 0.61；sf = 3 時 d = 0.48）。Lu 與 Rodriguez-Larios（2022）針對無經驗者在呼吸專注對比心智漫遊時，亦報告左額葉、頂葉與右額中區的 Lempel-Ziv 複雜度（LZc，d = 0.3865）、樣本熵（d = 0.4329）與整體 HFD（d = 0.543）上升。在腦磁圖（MEG）的高空間解析度驗證方面，D'Andrea 等人（2024，PMC10869546）使用 eLORETA 與人類連接組計畫（HCP）皮質分區，分析 10 位具 2,265 小時以上經驗的上座部佛教僧侶的微狀態序列，發現微狀態轉換的 Lempel-Ziv 複雜度呈現由靜息、專注冥想到開放監測逐步遞增的趨勢（REST < FAM < OMM），而表徵長程時間相關性的 Hurst 指數則在兩種冥想中皆低於靜息態，表明冥想期間的認知狀態轉換伴隨著腦動力學相對於臨界點的位移。

|**代表性後續研究**|**發表年份與狀態**|**樣本與冥想傳統**|**核心分析技術**|**與 Kakumanu 等人（2018）的關聯與推進**|
|---|---|---|---|---|
|Kakumanu et al.|2019（同儕審查專書期刊章節）|內觀冥想者（多組熟練度）|P300 事件相關電位（刺激辨別／oddball 範式）|將 2018 年靜息與冥想態解離延伸至認知作業，顯示練習質與量皆影響 P300 注意力資源動態。|
|Andreu et al.|2019（同儕審查期刊）|經驗豐富之內觀冥想者|情緒 Go/Nogo 任務態 EEG|顯示經驗豐富的內觀者具備較強反應抑制能力與較低的額中線 Theta 活動。|
|Walter & Hinterberger|2022（同儕審查期刊）|資深冥想者（n = 30，平均 6,498 小時）|DFA、HFD、多尺度熵（MSE）、PSD|跨風格驗證冥想期間 HFD 與樣本熵上升、DFA 下降，支持複雜度上升與 LRTC 衰減趨勢。|
|Govindaraj et al.|2023 會議／2026 專書章節|內觀冥想者|量表建構與心理計量驗證|開發並驗證《VIPASSANA Proficiency Scale》，補強專門評估內觀熟練度的心理計量工具。|
|Reggente et al.|2024/2025（同儕審查期刊）|內觀專家（n = 34，跨 2 場次）|自發浮現法、源空間功率與有效連結 ML 解碼|突破傳統靜態分組限制，實現跨場次連續解碼個人化（1–5 分）主觀冥想深度。|
|D'Andrea et al.|2024（同儕審查期刊）|上座部佛教僧侶（n = 10，≥2,265 小時）|MEG、eLORETA 源微狀態、Hurst 指數、LZC|以高空間解析度證實微狀態轉換複雜度呈 REST < FAM < OMM 遞增，且 Hurst 指數下降。|
|Kakumanu et al.|2025（bioRxiv 預印本）|初學內觀者（NVP）與對照組（NMC）|決策任務 EEG 相位滑移率（PSRs）|導入毫秒級皮質相位轉換指標，發現初學內觀者具較快物體辨識速度與特定相位滑移模式。|
|Shrimali et al.|2025/2026（bioRxiv 預印本）|進階者（n = 121）與對照（n = 49），四種傳統|振盪、1/f 斜率、PE/HFD/SVD 熵、隨機森林分類|達 91% 跨傳統分類準確率；進階者由非線性與非週期特徵主導，內觀 Alpha 增幅最大。|
|Malipeddi et al.|2026（同儕審查期刊）|含重分析 2018 年 43 位內觀專家數據|內在神經時間尺度（INT）、非二元體驗|直接重用 2018 年原始 128 通道專家腦電，揭示 INT 在進階非二元體驗中的關鍵角色。|
|Chowdhury et al.|2026（bioRxiv 預印本）|冥想者（靜息、任務與冥想對比）|IRASA 非週期斜率／截距、DFA、HFD、PE|提出以測量信度為核心的分析，指出冥想相較靜息與任務在 Theta–Alpha 與非線性指標的系統變化。|

## 系統性綜述的重新定位與方法學爭議

在累積多項後續實證後，2025 年刊登的兩篇系統性綜述為 Kakumanu 等人（2018）確立了量化的文獻定位，同時揭示該領域面臨的理論與測量挑戰。

在非線性複雜度方面，Atad 等人（2025，《Neuroscience of Consciousness》）的系統性綜述重新計算並標準化了 Kakumanu 等人（2018）的組內效應量（Cohen's d）：教師組（n = 21）相較於靜息在觀息法（FA）、內觀（OM）與慈悲觀（LK）的排列熵（PE）一致上升（d = 0.284 至 0.292），內觀期間的 HFD 亦呈提升（d = 0.271）；初學者組（n = 24）在內觀期間的 PE 與 HFD 則分別為 d = 0.265 與 d = 0.241。更重要的是，該綜述藉由 2018 年研究的雙重結果總結出冥想複雜度的「狀態—特質分離現象」：在專家冥想者中，主動冥想「狀態」普遍伴隨神經訊號複雜度上升與長程時間相關性（LRTC）衰減；然而長期的「特質」效應卻表現為靜息基線複雜度相較於初學者與對照組降低。正因這項特質性基線差異，Kakumanu 等人（2018）在跨組（between-subject）比較中被列為與整體高複雜度趨勢相反的少數例外。Atad 等人（2025）指出，鑑於個體間基線複雜度變異龐大，研究設計應優先採用受試者內（within-subject）比較，並正視不同複雜度演算法（如 LZc、PE、SE、MSE、DFA、HFD）在相同數據集與不同腦電通道間可能出現方向分歧、缺乏統一理論框架的現況。

在傳統振盪與研究設計層面，2025 年刊於《Imaging Neuroscience》的專注冥想神經生理範圍綜述（PMC12327082）將 Kakumanu 等人（2018）納入頻譜與非線性證據整合。在 4 項比較長期冥想者與初學者／無經驗者 Theta 功率的組間研究中，2018 年研究是其中 2 項呈現不顯著差異的文獻之一；在組內比較上，則作為專注冥想相較靜息伴隨 Alpha（6 項同向組內比較之一）、Beta（2 項同向組內比較之一）與 Delta 功率上升（該綜述記錄到的唯一實例）的證據來源。但該綜述同時指出，包括 2018 年研究在內的既有文獻高度依賴橫斷面分組比較，極度缺乏追蹤同一群體從初學者轉變為高熟練度專家的縱貫研究（longitudinal studies），且各研究對經驗與熟練度的操作型定義異質性過高，導致長期塑性與短期狀態變化難以徹底區辨。

綜合近年方法學文獻，解讀 2018 年研究與其後續發展時尚須注意兩項訊號詮釋盲點。第一是「靜息基線污染」問題：正如 Tal 等人（2026）以及《Shifting Baselines: Longitudinal Reductions in EEG Beta Band Power Characterize Resting Brain Activity with Intensive Meditation》一文所指出，高度熟練的冥想者可能在實驗室「靜息基線」時段便自發進入冥想狀態，使靜息態本身承載訓練效應而不再是中立基線，進而模糊狀態與特質變化的界線。第二是「週期性振盪與非週期性 1/f 活動的混淆」：2024 年《PLOS ONE》針對 8 週正念訓練的縱貫腦電研究（發現訓練後前額 Alpha 振盪顯著減慢，而注意力渙散則與較慢且廣布的 3–6 Hz Theta 振盪相關），以及近年專注於正念腦電方法學的評述（PMC12640546、PMC11971390）均強調，窄頻帶功率變化可能同時混雜真實振盪、個體 Alpha 峰值頻率（IAF）漂移與背景 1/f 斜率改變。因此，結合 `specparam`（FOOOF）或 `IRASA` 的頻譜分離、時間尺度分析與主觀深度連續解碼，正成為延續 Kakumanu 等人（2018）開創性工作的主流研究標準。
https://share.gemini.google/Ntj5D0aJkQQW