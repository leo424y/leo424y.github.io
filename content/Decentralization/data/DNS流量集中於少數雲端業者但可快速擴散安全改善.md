Moura 等人在 2020 年 ACM Internet Measurement Conference 發表研究，分析 DNS 根伺服器與歐洲、大洋洲兩個國碼頂級網域的流量，發現超過 30% 的查詢來自五家大型雲端供應商。研究呈現網路基礎設施的集中化：看似全球分散的網路服務，可能依賴少數大型業者提供解析與運算能力。

作者同時指出集中化可能帶來正面效果：大型雲端供應商一旦部署某些安全功能，例如 QNAME minimization，就能快速讓大量使用者受益。這提醒去中心化並非在所有情況下都必然較安全或有效率；集中與分散的影響取決於系統風險、可替代性、透明度與權力制衡。

### 思與行
* 評估數位服務時，不只看服務是否開源，也要查 DNS、雲端主機、身份登入、支付與資料備份是否依賴少數供應商。
* 為關鍵社群資料保留可匯出格式、備份與遷移方案，降低單一服務中斷或政策改變造成的依賴。

### 參考
* **主要研究**：Giovane C. M. Moura et al., “Clouding up the Internet: How centralized is DNS traffic becoming?” *Proceedings of the ACM Internet Measurement Conference*, 2020, pp. 42–49. https://doi.org/10.1145/3419394.3423625
* **概念脈絡**：[[基礎設施集中化]]、[[單點故障]]、[[互通性]]、[[技術分散不等於民主化]]。
