Joy Buolamwini 與 Timnit Gebru 的〈Gender Shades〉研究於 2018 年發表，檢驗商業性別分類系統在膚色與性別群體上的準確度差異。研究發現，既有評測資料集較偏向淺膚色樣本，而商用系統對深膚色女性的錯誤率最高；研究所測系統中，深膚色女性的錯誤率最高達 34.7%，淺膚色男性則低至 0.8%。

這篇研究使「平均準確率」的盲點變得具體：整體表現良好可能掩蓋特定群體承受的高錯誤成本。它也展示交織性分析的重要性，因為種族與性別並非彼此獨立的變項。數字來自特定資料集與當時受測產品，不應直接當作今日所有臉部辨識系統的現況。

## 思與行

* 設計模型評估時，除了整體準確率，至少檢查性別、膚色與交織群體的錯誤類型。
* 確認分類任務是否本身必要且正當；若模型用途造成權利侵害，改善指標不一定足夠。

## 參考

* 文獻來源：[Buolamwini & Gebru（2018）, Gender Shades, PMLR](https://proceedings.mlr.press/v81/buolamwini18a.html)；[MIT Media Lab 研究介紹](https://www-prod.media.mit.edu/publications/gender-shades-intersectional-accuracy-disparities-in-commercial-gender-classification/)
* 知識連結：[[公平不是單一指標而是必須公開承擔價值取捨]]；[[歷史不平等會透過資料與分類系統重新進入模型]]；[[自動化決策必須提供可理解理由與有效申訴管道]]；[[交織性]]；[[演算法公平]]；[[自動化偏見]]；[[人權導向設計]]
