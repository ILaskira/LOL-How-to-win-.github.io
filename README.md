# How to Win? - Predicting the Outcome of League of Legends Matches

本專案旨在探討《英雄聯盟》（League of Legends, LoL）比賽中，哪些變數能有效影響勝負，並藉由多種機器學習方法建立預測模型。

---

## 🎯 專案目標

1. 找出能在比賽前 10 分鐘內**準確預測勝負**的最佳模型
2. 分析哪些行為或特徵**最能影響比賽結果**

---

## 🧾 資料來源與特徵

- 來自高 Elo 階級（Diamond I 至 Master）的比賽資料，總計約 10,000 場
- 每場比賽擷取前 10 分鐘的統計資料
- 共 38 個特徵變數(包含了紅藍方的比賽資料)
- 目標變數：`blueWins`（藍方是否獲勝）

---

## 🧪 分析方法與模型

- **EDA**（探索性資料分析）
- **LASSO**（特徵選擇）
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting (gboost)**

---

## 📈 結果與結論

本專案針對兩項關鍵問題進行探討：

1. **如何用十分鐘內的資料準確預測比賽勝負？**  
   ➤ 我們比較多種模型並以Random Forest模型表現最佳，擁有同時高 sensitivity 和 specificity，整體 AUC 表現也佳。

2. **如何快速判斷哪些變數最關鍵？**  
   ➤ 我們發現無論是哪個模型，最常出現的關鍵變數都是「雙方經濟差」，只要觀察紅藍方的經濟差即可快速預測勝負結果。

---

## 📄 專案檔案下載

- [📄 書面報告（Written Report）](./final_presentation.pdf)
- [🎞️ 簡報投影片（Presentation Slides）](./How%20To%20Win.pdf)

---

## 🔗 參考資料

- https://www.kaggle.com/code/xiyuewang/lol-how-to-win/input
- https://www.rdocumentation.org/packages/caret


