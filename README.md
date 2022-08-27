# JableTVDownload

## 下載JableTV好幫手

每次看正要爽的時候就給我卡住轉圈圈  

直接下載到電腦看沒煩惱

-------------
## 虛擬環境建置 (Virtual Enviroment)
1. 安裝虛擬環境
`$ pip3 install virtualenv`
2. 創建虛擬環境，輸入指令後會產生名為 JableTV 資料夾
`$ virtualenv JableTV`
3. 將路徑指引至 JableTV/Scripts，並輸入下方指令，開啟虛擬環境
`$ activate`
4. 安裝環境
`$ pip install -r path/to/requirements.txt `
-------------
## 開發環境 (Requirements)
``` 
Python == 3.9.13
requests == 2.25.1
beautifulsoup4 == 4.9.3
m3u8 == 0.8.0
pycryptodome == 3.9.9
cloudscraper == 1.2.58
```
##### 安裝 [FFmpeg] (未安裝也能下載 但影片拖拉時間軸會有卡幀情況發生)
-------------
1. 執行程式
`python main.py`

    ![image](https://imgur.com/IcIPI8M.png)

2. 選擇待下載影片，並點擊 "開始下載"
    ![image](https://imgur.com/G0TC0w7.png)  

3. 完成
    ![image](https://imgur.com/iymySIF.png)

4. 其他功能說明
    a. "導入文件"：將 `JableTV.csv` 資訊匯入至視窗中。
    b. "存方位置"：可自行設定影片儲存路徑，預設為 `JableTVDownload\DownloadVideos`。
    c. 關閉視窗時會將下載的相關資訊儲存至 `JableTV.csv`。
