# linebot19890604

### 一. 自動部署 Heroku
首先我們先做一個最簡單的 Echo Bot (也就是你跟他說什麼，他都會回覆一模一樣的話給你) 點擊下面紫色的 Deploy to Heroku 按鈕

<a href="https://heroku.com/deploy?template=https://github.com/s098031/linbot19890604/tree/main">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>


# 公主連結優衣聊天機器人

* 先說框架很廢 閒暇時獨立開發 沒用啥特別演算法 初學者可讀性很高
* 當初只是為了快速看本所寫的機器人 改著改著變成了迫害優衣的元凶
* 會一直持續更新到遊戲垮 但作者很懶更新很慢 見諒><
* 就...以休閒來說真的很好用啦
* 我就孤單寂寞覺得冷只能找優衣聊天...

## 目錄

- [公主連結優衣聊天機器人](#公主連結優衣聊天機器人)
  - [目錄](#目錄)
  - [使用須知](#使用須知)
  - [目前適用聊天軟體](#目前適用聊天軟體)
  - [此專案特色](#此專案特色)
    - [漫步於公主連結的世界](#漫步於公主連結的世界)
    - [試算表資料庫](#試算表資料庫)
    - [私心功能](#私心功能)
  - [部分截圖](#部分截圖)
  - [事前準備](#事前準備)
  - [Python插件準備](#Python插件準備)
  - [安裝方式](#安裝方式)
  - [注意事項](#注意事項)
  - [指令範例](#指令範例)

## 使用須知

本專案已配置好所有程式所需之環境，只需跟著[安裝方式](#安裝方式)，進行操作即可。

## 目前適用聊天軟體

* [Line](https://line.me/zh-hant/)


## 此專案特色

### 漫步於公主連結的世界
* 支援至日版プリコネ最新角色、漫畫 (大量圖庫)
* 抽卡模擬
* 正版動畫 (測試性)
* 聊天、圖片回覆 

### 試算表資料庫
* 調整回覆訊息等級 (最高級將停止發車服務)
* 可私訊作者 待幾日後回覆

### 私心功能
* 發車功能
* 各功能隱藏彩蛋

更多詳細資訊請洽[作者巴哈](https://home.gamer.com.tw/creationDetail.php?sn=4914939)

## 事前準備

* [Git](https://git-scm.com/)
* [Google_APIs](https://console.developers.google.com/apis)
* [Python](https://www.python.org/)
* [Line機器人申請](https://manager.line.biz/)，自行填上 Access Token & Client Secret

## Python插件準備

* line-bot-sdk
* flask
* opencv-python-headless
* pydub
* gspread
* oauth2client
* bs4 (已於根目錄下，可不必額外安裝)

## 安裝方式

1. 打開你的CLI跟著我一起輸入(終端機、命令提示字元、命令介面)
2. `git clone https://github.com/PolarisZenya/Yui_LineBot.git`
3. `cd linebot`
4. `start app.py`
5. 自行填入Channel Access Token & Client Secret

## 注意事項

* #建議 與 #權限 功能有使用到 google sheet，記得要先拿到你的google sheet的金鑰檔案或填入金鑰資料於cred.json內哦
* 在提醒一次進行安裝方式第四步之後，記得編輯裡面的內容，填上你機器人的相對應的資料哦
* 丟到自己的 server 上啟動哦 預設port5000 我是丟在[heroku](https://www.heroku.com/)上的

## 指令範例

    #log、#求圖
    #抽 泳裝、#漫畫 123、#動畫 公主連結
    #權限 3、#建議 xxx
    n228922、w0、18c237644
