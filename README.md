# Kaggle Titanic 生存預測練習環境

這是一個專為 Kaggle Titanic 競賽準備的機器學習實作環境。

## 目錄結構
- `data/raw/`: 存放原始的 Titanic 數據庫檔案 (`train.csv`, `test.csv`)。
- `notebooks/`: 存放數據分析與模型訓練的 Jupyter Notebooks。
- `.venv/`: Python 3.11 虛擬環境目錄。

## 如何啟動環境
1. 打開 VS Code 並進入本目錄。
2. 開啟終端機 (Terminal)。
3. 確保虛擬環境已啟動 (看到 `(.venv)` 字樣)。
   - 若未啟動，請輸入: `.\.venv\Scripts\Activate.ps1`
4. 安裝套件 (初次使用): `pip install -r requirements.txt`
5. 開啟 `notebooks/titanic_analysis.ipynb` 並開始練習！

## 競賽目標
預測鐵達尼號劫後餘生的乘客人數。這是一個基礎的二元分類問題。
