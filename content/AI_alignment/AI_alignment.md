# 人工智慧對齊：技術、價值與全球治理

> 研究書庫版本：2026-11-03。這是一份以卡片盒筆記方式編排的跨領域導讀，不宣稱已窮盡所有研究或取得全球共識。文獻以可追溯的論文、政策原文、研究者訪談與出版社書目為主；政策文件需隨法規與版本更新。

## 全書主張

AI alignment（人工智慧對齊）不是單純讓模型「聽話」，而是讓 AI 在特定用途與脈絡中，能可靠地理解人類意圖、尊重權利、避免不當傷害，並受到可問責的制度治理。這個問題同時有技術與規範兩面：技術研究處理目標規格、回饋學習、穩健性、可解釋性、可控性與評估；規範研究則處理價值由誰定義、不同群體如何協商、誰承擔錯誤成本，以及技術基礎設施如何分配權力。

本書以三條互相交織的主線組織：

1. **技術可靠性**：獎勵函數與人類意圖之間有落差；模型可能利用規格漏洞；訓練環境外的行為可能改變；監督者能力也可能落後於模型。
2. **價值正當性**：偏好不是完整價值，普遍價值也不是自動存在的共識。公平的制度必須承認文化差異、少數群體權利與社群參與。
3. **制度與物質條件**：AI 不是漂浮在雲端的模型，而是資料、勞動、能源、晶片、平台與法律制度的組合。安全治理需要涵蓋整個生命週期。

## 建議閱讀路徑

### 入門：先建立問題地圖

先讀 [[技術對齊概念地圖]] 與 [[價值與倫理概念地圖]]，再讀 [[Book_The_Alignment_Problem_Brian_Christian_2020]] 和 [[Book_Artificial_Intelligence_A_Guide_for_Thinking_Humans_Melanie_Mitchell]]。前者用案例介紹機器學習與人類價值之間的落差；後者協助理解 AI 能力與理解之間的差異。接著查閱 `term` 資料夾中 [[AI對齊]]、[[外在對齊]]、[[內在對齊]]、[[價值對齊]] 等基礎定義。

### 技術：從規格錯置走到監督與評估

建議順序：[[Concrete_Problems_in_AI_Safety_Amodei_et_al_2016]] → [[Specification_Gaming_DeepMind_2020]] → [[Inverse_Reward_Design_HadfieldMenell_et_al_2017]] → [[Cooperative_Inverse_Reinforcement_Learning_HadfieldMenell_et_al_2016]] → [[Risks_from_Learned_Optimization_Hubinger_et_al_2019]] → [[Weak_to_Strong_Generalization_OpenAI_2023]] → [[AI_Alignment_A_Contemporary_Survey_Ji_et_al_2025]]。閱讀時特別區分獎勵規格、內部目標、回饋監督與安全證據。

### 價值：從個人偏好走到社會正當性

先讀 [[Artificial_Intelligence_Values_and_Alignment_Gabriel_2020]]，再讀 [[Algorithmic_Injustice_Relational_Ethics_Birhane_2021]]、[[On_the_Dangers_of_Stochastic_Parrots_Bender_et_al_2021]]、[[Book_Data_Feminism_DIgnazio_Klein_2020]] 和 [[Book_Race_After_Technology_Ruha_Benjamin_2019]]。這條路徑會把問題由「怎樣更準確地讀取使用者偏好」推進到「誰有權定義好結果」。

### 全球治理：比較法律、政策與地方自主

閱讀 [[全球視角概念地圖]]，再依序比較 [[UNESCO_Recommendation_on_the_Ethics_of_AI_2021]]、[[OECD_AI_Principles_2019_2024]]、[[EU_AI_Act_2024_2026]]、[[NIST_AI_RMF_Generative_AI_Profile_2024_2026]]、[[China_AI_Safety_Governance_Framework_2024]]、[[ASEAN_Guide_on_AI_Governance_and_Ethics_2024]]、[[African_Union_Continental_AI_Strategy_2024]]、[[India_AI_Governance_Guidelines_2025_2026]] 與 [[Taiwan_Artificial_Intelligence_Basic_Act_2026]]。政策比較應同時看文件效力、監管能力、執法、申訴與社群參與，不能只比較原則名稱。

### 代理式 AI：將安全延伸到實際行動

最後讀 [[代理式AI與可擴展監督概念地圖]]、[[A_Survey_on_Value_Alignment_in_Agentic_AI_Systems_Zeng_et_al_2026]]、[[Sleeper_Agents_Anthropic_2024]] 與 [[Alignment_Faking_in_LLMs_Anthropic_2024]]。把工具權限、長期記憶、多代理通訊、撤回與人工接管納入測試。

## 核心概念與主要結論

- **目標不是價值本身**：獎勵函數與偏好資料只是意圖的代理指標，系統越會最佳化，越需要測試規格漏洞。
- **對齊有內外兩層**：外在規格正確，不代表模型內部學到的策略必然符合規格；內部分析也不能替代行為與部署評估。
- **監督需要擴展而不是盲目自動化**：模型可以協助評估模型，但監督獨立性、可驗證性與權力集中成為新問題。
- **人類價值是多元且關係性的**：單一使用者偏好不能代表所有受影響者；要讓社群參與目標制定、資料治理與救濟。
- **AI 對齊是整個社會技術系統的問題**：資料、勞動、能源、基礎設施與制度責任，不能被模型訓練階段的安全微調取代。
- **代理式 AI 擴大了行動風險**：記憶、工具使用、委派與跨代理互動，要求更細緻的權限控制與持續監測。

## 重要研究與政策來源

這份書庫刻意混合論文、正式政策、研究者訪談與跨領域書籍。技術文獻多以論文或研究機構原文為準；政策文件優先連到官方來源；書籍連結以作者或出版社頁面為主。對於 2026 年發布或修訂的制度材料，應在再次使用前確認最新版本。

## 研究限制與閱讀提醒

1. **不是系統性回顧**：這是具代表性的導讀型書庫，不是完整 PRISMA 系統性文獻回顧；搜尋語言以英文為主，區域覆蓋仍不均。
2. **地理代表性有限**：已納入北美、歐洲、中國、印度、東南亞、非洲與台灣的材料，但拉丁美洲、太平洋島國、中東與更多原住民族治理案例仍需擴充。
3. **證據層級不同**：理論論文、受控實驗、政策宣示、研究者訪談與通俗書籍不能當成同等證據。請參考 [[未來風險論述需要區分實證模型與情境推演]]。
4. **法律資訊可能變動**：歐盟 AI Act 的適用時程、台灣法規子法、印度及其他地區政策都應回到官方最新版本確認。
5. **價值立場需要持續協商**：本書不把任何企業憲章、國家政策或研究者主張視為人類價值的唯一代表。

## 概念地圖

- [[技術對齊概念地圖]]
- [[價值與倫理概念地圖]]
- [[治理與問責概念地圖]]
- [[全球視角概念地圖]]
- [[代理式AI與可擴展監督概念地圖]]

## 全部文獻筆記（data）

- [[AI_Alignment_A_Contemporary_Survey_Ji_et_al_2025]]
- [[ASEAN_Guide_on_AI_Governance_and_Ethics_2024]]
- [[A_Survey_on_Value_Alignment_in_Agentic_AI_Systems_Zeng_et_al_2026]]
- [[African_Union_Continental_AI_Strategy_2024]]
- [[Algorithmic_Colonization_of_Africa_Birhane_2020]]
- [[Algorithmic_Injustice_Relational_Ethics_Birhane_2021]]
- [[Alignment_Faking_in_LLMs_Anthropic_2024]]
- [[Artificial_Intelligence_Values_and_Alignment_Gabriel_2020]]
- [[Book_AI_Snake_Oil_Narayanan_Kapoor_2024]]
- [[Book_Artificial_Intelligence_A_Guide_for_Thinking_Humans_Melanie_Mitchell]]
- [[Book_Atlas_of_AI_Kate_Crawford_2021]]
- [[Book_Data_Feminism_DIgnazio_Klein_2020]]
- [[Book_Human_Compatible_Stuart_Russell_2019]]
- [[Book_Race_After_Technology_Ruha_Benjamin_2019]]
- [[Book_The_Alignment_Problem_Brian_Christian_2020]]
- [[Book_The_Costs_of_Connection_Couldry_Mejias_2019]]
- [[CARE_Principles_Indigenous_Data_Governance]]
- [[China_AI_Safety_Governance_Framework_2024]]
- [[Concrete_Problems_in_AI_Safety_Amodei_et_al_2016]]
- [[Constitutional_AI_Bai_et_al_2022]]
- [[Cooperative_Inverse_Reinforcement_Learning_HadfieldMenell_et_al_2016]]
- [[Deep_Reinforcement_Learning_from_Human_Preferences_Christiano_et_al_2017]]
- [[EU_AI_Act_2024_2026]]
- [[India_AI_Governance_Guidelines_2025_2026]]
- [[Interview_Narayanan_and_Kapoor_AI_Snake_Oil_2024]]
- [[Interview_Stuart_Russell_Quanta_2015]]
- [[Interview_Timnit_Gebru_Scientific_American_2026]]
- [[Interview_Timnit_Gebru_WIRED_2026]]
- [[Interview_Yoshua_Bengio_WEF_2026]]
- [[Inverse_Reward_Design_HadfieldMenell_et_al_2017]]
- [[NIST_AI_RMF_Generative_AI_Profile_2024_2026]]
- [[OECD_AI_Principles_2019_2024]]
- [[On_the_Dangers_of_Stochastic_Parrots_Bender_et_al_2021]]
- [[Risks_from_Learned_Optimization_Hubinger_et_al_2019]]
- [[Sleeper_Agents_Anthropic_2024]]
- [[Specification_Gaming_DeepMind_2020]]
- [[Taiwan_Artificial_Intelligence_Basic_Act_2026]]
- [[UNESCO_Recommendation_on_the_Ethics_of_AI_2021]]
- [[Weak_to_Strong_Generalization_OpenAI_2023]]
## 全部永久筆記（note）

- [[AI對齊同時是工程問題與政治哲學問題]]
- [[AI風險時間尺度不同但不必互相排斥]]
- [[不同地區的治理框架反映不同的公共目標]]
- [[人類偏好只是價值的局部證據]]
- [[人類相容性需要機器對人類偏好保持不確定]]
- [[代理式AI的價值對齊必須跨越模型代理與多代理層次]]
- [[價值多元要求可爭議而非假裝一致的治理程序]]
- [[價值對齊必須區分指令偏好利益與價值]]
- [[全球對齊需要跨文化協商與制度互通]]
- [[分布偏移會暴露訓練目標的隱藏假設]]
- [[可修正性是AI接受人類監督的制度與技術條件]]
- [[可擴展監督不是增加標註數量而已]]
- [[可解釋性不能單獨證明模型安全]]
- [[國家自主能力與跨境互通必須同時討論]]
- [[外在對齊與內在對齊是不同的失敗來源]]
- [[多語言公平必須檢查語料代表性與錯誤成本]]
- [[安全與可信任需要可驗證而非宣傳式的證據]]
- [[安全評估必須同時測量行為與內部機制]]
- [[對齊既有制度可能讓不正義更有效率]]
- [[工具權限應依風險與可逆性逐步授予]]
- [[指標最佳化可能犧牲指標原本要代表的福祉]]
- [[未來風險論述需要區分實證模型與情境推演]]
- [[模型對齊不能取代資料與基礎設施責任]]
- [[模型能力表現不等於人類式理解]]
- [[治理制度決定誰能定義可接受的AI風險]]
- [[治理議程應揭露風險排序背後的價值選擇]]
- [[法律原則必須轉化為可追責的部署義務]]
- [[演算法殖民主義會把價值對齊變成基礎設施依賴問題]]
- [[獎勵函數只是意圖的代理指標而不是意圖本身]]
- [[監督者能力落差會變成新的權力與責任問題]]
- [[社群參與應是治理權而不只是資料蒐集程序]]
- [[讀者應把通俗案例轉化為可檢驗的研究問題]]
- [[資料主權是社群決定資料用途與收益的能力]]
- [[部署前應先確認AI是否是適當的問題解法]]
- [[長期記憶會讓價值對齊成為持續治理問題]]
- [[關係倫理讓對齊的單位從個人擴展到社群]]
## 全部靈感筆記（idea）

- [[將內觀式覺察轉譯為AI使用者的停看問流程]]
- [[建立AI安全證據等級與不確定性標籤]]
- [[建立一份可公開檢查的AI對齊主張帳本]]
- [[建立台灣多語言AI對齊測試共作庫]]
- [[建立資料勞動與環境足跡的模型卡附錄]]
- [[把AI代理權限設計成可逐步撤回的階梯]]
- [[比較不同治理框架如何定義風險與責任]]
- [[用多方審議取代單一平均偏好作為公共AI價值基準]]
- [[設計社群共同制定的AI使用憲章]]
- [[讓AI系統保留拒絕與暫停的能力]]
## 全部概念定義（term）

- [[AI回饋強化學習]]
- [[AI安全]]
- [[AI對齊]]
- [[AI治理]]
- [[CARE原則]]
- [[RLAIF]]
- [[RLHF]]
- [[mesa最佳化]]
- [[人類偏好]]
- [[人類回饋強化學習]]
- [[人類相容性]]
- [[代理式AI]]
- [[價值多元]]
- [[價值對齊]]
- [[內在對齊]]
- [[全球治理]]
- [[分布偏移]]
- [[可修正性]]
- [[可擴展監督]]
- [[可解釋性]]
- [[合作式逆向強化學習]]
- [[問責]]
- [[外在對齊]]
- [[多代理協作]]
- [[安全評估]]
- [[對齊偽裝]]
- [[對齊評估]]
- [[工具權限]]
- [[弱到強泛化]]
- [[憲章式AI]]
- [[指標最佳化]]
- [[模型卡]]
- [[機制可解釋性]]
- [[演算法殖民主義]]
- [[獎勵模型]]
- [[獎勵駭客]]
- [[社群參與]]
- [[程序正當性]]
- [[穩健性]]
- [[紅隊測試]]
- [[規格遊戲]]
- [[資料主權]]
- [[資料殖民主義]]
- [[資料治理]]
- [[資料表單]]
- [[逆向強化學習]]
- [[逆向獎勵設計]]
- [[長期記憶]]
- [[關係倫理]]
## 全部概念地圖（moc）

- [[代理式AI與可擴展監督概念地圖]]
- [[價值與倫理概念地圖]]
- [[全球視角概念地圖]]
- [[技術對齊概念地圖]]
- [[治理與問責概念地圖]]
## 研究者與政策文件的多元觀點

技術安全路線可從 Stuart Russell、Yoshua Bengio 與相關研究群體進入；公平與權力批判可從 Timnit Gebru、Abeba Birhane、Ruha Benjamin、Kate Crawford 等人的作品進入。兩條路線並非必然互斥：前者提醒人類可能失去對高能力系統的有效控制，後者提醒當前 AI 已經在具體制度中分配權力與傷害。較好的閱讀方式，是要求雙方都交代證據、假設、風險排序與可行的治理方案。
