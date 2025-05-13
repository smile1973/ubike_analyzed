
# YouBike 使用量分析

本專案包含一份 Jupyter Notebook，進行對台北市 YouBike 使用量資料的分析，探索使用趨勢、熱門站點、使用時段等資訊，以利了解市民大眾的騎乘行為。

## 檔案說明

* `analyze.ipynb`：主分析程式碼，透過 Python 及資料視覺化工具（如 `pandas`, `matplotlib`）對 YouBike 使用數據進行處理與分析。

## 功能簡介

* 讀取 YouBike 使用量相關資料
* 清理與整理資料欄位
* 分析每日、每月使用趨勢
* 探索高使用量站點
* 分析不同時段或天氣對使用量的影響
* 繪製相關圖表協助理解資料

## 使用方式

1. 安裝必要套件（建議使用 virtualenv 或 conda）：

   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

2. 啟動 Jupyter Notebook：

   ```bash
   jupyter notebook
   ```

3. 開啟 `analyze.ipynb`，依序執行各區段程式碼，即可進行資料分析。

## 資料來源

請根據實際使用的資料來源補充，例如：

* [台北市政府 YouBike 開放資料平台](https://data.gov.tw/)
* 手動匯出或爬取的即時資料

## 注意事項

* 請確認你已取得正確的資料檔案並放置於 Notebook 中指定的資料夾或路徑下
* 若資料格式變動，請相應調整資料讀取與處理的程式碼

