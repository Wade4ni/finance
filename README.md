# 股價預測(台美股適用)

參考 WillKoehrsen的 stocker模型，使用 Yahoo股市取代原本的 Wiki作為資料來源，可以應用在台股與美股的價格預測。套件相關功能可以參考原作者的[Github](https://reurl.cc/rDl9EN)。

[台股代號查詢](https://tw.stock.yahoo.com/h/kimosel.php) <br> [美股代號查詢](https://finance.yahoo.com/lookup)


## 簡易安裝:
1.先在電腦安裝 [ANACONDA DISTRIBUTION](https://www.anaconda.com/products/distribution)。<br>
2.安裝完畢後，開啟 Anaconda Prompt，並輸入以下程式碼安裝必要套件。<br>
```pip install -U quandl numpy pandas matplotlib pytrends pystan plotly```<br>
3.有些套件無法使用一般的 pip 安裝方式，需要使用 conda install。<br>
```conda install -c conda-forge fbprophet```

## 使用方法:
1.下載 **stocker.py** 及 **stockprice_predict.ipynb** 並將其放在同一個資料夾內。<br>
2.開啟 Jupyter Notebook並執行 **stockprice_predict.ipynb**。

## 參考資料:
1. WillKoehrsen/Data-Analysis/stocker([Github](https://reurl.cc/rDl9EN))<br>
2. 教你如何用 Python 預測股票價格([連結](https://reurl.cc/Dy1jKN))
