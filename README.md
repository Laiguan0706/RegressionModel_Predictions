本研究旨在系統性地評估主流迴歸演算法的效能，並探討SHAP在特徵工程中的應用價值。
研究採用四種回歸演算法（KNN、SVR、Random Forest、XGBoost）對 Adult 資料集進行工時預測，並使用 XGBoost 模型對 Boston Housing 資料集進行房價預測與特徵重要性分析
-----------------------
程式執行步驟:
-----------------------
1.experiment1_adult_regression.ipynb:針對Adult資料集進行四種回歸演算法之效能比較分析，執行前請確保工作目錄中包含 adult.data 與 adult.test 資料集檔案
2.experiment2_boston_xgboost.ipynb: 針對Boston Housing資料集之XGBoost模型分析與特徵重要性探討
