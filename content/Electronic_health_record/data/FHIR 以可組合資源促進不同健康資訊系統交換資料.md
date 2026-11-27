HL7 FHIR（Fast Healthcare Interoperability Resources）是一套電子交換健康資訊的標準。它以模組化的 Resource 表達病人、就診、檢驗、處方、觀察值等資料，並透過網路 API 等機制支援系統交換。FHIR 可以降低不同軟體之間的資料交換摩擦，但標準本身不會自動解決術語一致性、資料品質、工作流程差異、授權與治理問題。真正互通還需要本地實作指南、共同術語、技術測試與臨床驗證。

## 思與行
* 將 FHIR 視為共同語法，而不是保證語意一致的魔法轉換器；檢查欄位定義、代碼系統與臨床使用情境。
* 開發介面時同時進行技術驗證與臨床驗證，並提供可讀文件，讓非工程角色也能參與規格治理。

## 參考
* HL7, [FHIR Overview](https://fhir.hl7.org/fhir/overview.html)。
* US ONC, [FHIR interoperability](https://healthit.gov/interoperability/investments/fhir/)（2026-01-21 更新）。
* 延伸：[[互通性必須同時處理技術標準與組織協作]]、[[結構化資料只有保留語意才適合跨系統使用]]。
