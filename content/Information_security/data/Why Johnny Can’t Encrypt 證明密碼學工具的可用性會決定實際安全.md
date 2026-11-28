Alma Whitten 與 J. D. Tygar 在 1999 年 USENIX Security Symposium 發表《Why Johnny Can't Encrypt: A Usability Evaluation of PGP 5.0》。研究以認知導覽分析與實驗室使用者測試，觀察密碼學新手能否使用 PGP 5.0 簽署與加密電子郵件。研究摘要指出，參與者有 90 分鐘完成任務，多數人仍無法成功完成；作者因此主張，安全軟體需要不同於一般消費軟體的可用性標準。

這篇研究成為可用安全（usable security）的重要案例：安全功能存在，不代表使用者就能正確使用；複雜流程、難懂的信任提示、金鑰管理與錯誤訊息，可能讓使用者放棄、誤用或形成錯誤安全感。真正有效的安全必須把使用者的理解、注意力、情境與錯誤可能性納入設計。

## 思與行
* 在設計 MFA、加密、權限授予及警示時，測試使用者能否在真實情境下完成任務，而非只測試功能是否存在。
* 將安全操作做成預設安全、步驟少、可逆且有清楚回饋的流程；對高風險操作提供分層提示。
* 不把人視為安全鏈中唯一薄弱環節，應檢查系統是否把不可行的判斷責任推給使用者。

## 參考
* 主要來源：Whitten, A. & Tygar, J. D., [Why Johnny Can't Encrypt](https://www.usenix.org/conference/8th-usenix-security-symposium/why-johnny-cant-encrypt-usability-evaluation-pgp-50)（USENIX Security 1999）；[全文 HTML](https://static.usenix.org/events/sec99/full_papers/whitten/whitten_html/index.html)。
* 延伸：[[安全控制必須讓人能正確且持續地使用]]、[[安全教育必須搭配可行的求證機制]]。
* 限制：這是針對 PGP 5.0 的歷史案例，不應把其參與者表現直接推論到今日所有加密工具；它的重要性在研究方法與核心設計問題。
