# How to Win? - Predicting the Outcome of League of Legends Matches

本專案旨在探討《英雄聯盟》（League of Legends, LoL）比賽中，哪些變數能有效的影響勝負，並藉由多種機器學習方法建立預測模型。

## 專案目標

1. 找出能在比賽前 10 分鐘內**準確預測勝負**的最佳模型
2. 分析哪些行為或特徵**最能影響勝負**

## 使用資料

- 來自高牌位（鑽石至大師段位）的比賽資料，共約 1 萬場對戰紀錄
- 每場比賽擷取前 10 分鐘的統計資料
- 共 38 個變數（每隊 19 個）
- 目標變數：`blueWins`（藍方是否獲勝）

## 使用方法與模型

- **EDA**（探索性資料分析）
- **LASSO 特徵選擇**
- **KNN（K 最近鄰）**
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting (gboost)**

## 📄 檔案下載
- [📄 書面報告（Written Report）](./final_presentation.pdf)
- [🎞️ 簡報投影片（Presentation Slides）](./How%20To%20Win.pdf)

## 🔗 參考資料

- https://www.kaggle.com/code/xiyuewang/lol-how-to-win/input
- https://www.rdocumentation.org/packages/caret
---

