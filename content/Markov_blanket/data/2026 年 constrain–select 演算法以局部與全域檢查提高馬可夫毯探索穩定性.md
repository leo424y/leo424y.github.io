2026 年 *Neurocomputing* 論文〈A constrain–select Markov blanket discovery algorithm for causal feature selection〉提出 CSMB。作者針對高維資料中條件獨立證據易受有限樣本影響、早期刪除可能傳播錯誤的問題，採取先限制候選範圍、再確認成員資格，最後做局部—全域一致性修正的設計。論文報告以多個貝葉斯網路、真實資料與 TCGA-BRCA 資料集進行比較。這項研究顯示馬可夫毯探索仍在發展，但效能結論仍需考慮資料集與基準演算法設定。

## 思與行
* 把「穩定性」視為演算法評估的一級指標，不只看平均準確率或單次實驗排名。
* 後續可追蹤程式碼、資料切分方式、條件獨立檢定與可重現性資訊。

## 參考
* 原始論文：[A constrain–select Markov blanket discovery algorithm for causal feature selection（2026）](https://www.sciencedirect.com/science/article/pii/S0925231226009148)，DOI：[10.1016/j.neucom.2026.133517](https://doi.org/10.1016/j.neucom.2026.133517)。
* 延伸：[[有限樣本與隱藏變項會使馬可夫毯探索不穩定]]、[[馬可夫毯探索演算法的品質取決於條件獨立檢定]]。
