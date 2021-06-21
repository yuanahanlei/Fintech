# FinTech Cloud Computing

## Introduction
* Name： Yuan-han Lei 雷沅翰 
* University： Soochow University 
* Department： Bid Data Management
* Student ID: 08170125

## Homework
* ### 作業一 : What do I think of Cloud Computing?
> 說明: 在完成第 1 堂雲端服務課程後，將您了解的知識與主觀想法來描述雲端運算與其產業的趨勢發展。內容不少於 250 字，並上傳 GitHub 然後將GitHub 鏈接貼在表單上傳作業。  
截止日期: 3/22  
[HW1](https://github.com/yuanahanlei/Fintech/tree/main/HW1) 

* ### 作業二 : Build a Website using Amazon EC2 with LAMP
> 說明: 在完成第 2 堂雲端服務課程後，藉由 Linux 2 虛擬機完成安裝 LAMP 解決方案包，並成功啟動網頁伺服器與資料庫伺服器的功能。  
截止日期: 3/29  
[HW2](https://youtu.be/KhdthxiUdcU)

* ### 作業三 : Build a Website using Amazon S3(Versioning) and AWS Amplify
> 說明: 在完成第 3 堂雲端服務課程後，運用 S3 與Amplify 服務進行網頁部署，過程中演示版本控制功能。  
截止日期: 4/12  
[HW3](https://youtu.be/GPXviAUjFuQ)

* ### 作業四 : Build a Telegram Chatbot using Amazon API Gateway and AWS Lambda
> 說明: 在完成第 4 堂雲端服務課程後，運用無伺服器框架串接 Telegram Chatbot，並且成功執行 DEMO文件，達到鸚鵡機器人的效果。  
截止日期: 4/26  
[HW4](https://youtu.be/B1avhQVSHyY)

* ### 作業五 : Create a Database using Amazon RDS or Amazon DynamoDB
> 說明: 在完成第 5 堂雲端服務課程後，運用資料庫服務上傳給定的資料集，並且可透過界面進行 CRUD行為。  
截止日期: 5/3  
[HW5](https://youtu.be/JsWPxbrLpNo)

* ### 作業六 : Create a Docker Container or Build your own Project Services
> 說明: 在完成第 6 堂雲端服務課程後，透過 Docker 建立Image，並執行該 Container，其內容可以是程序執行、各種伺服器服務等，並上傳至 Docker Hub。或您也可以選擇演示操作您的專案成品。  
截止日期: 5/17  
[HW6](https://youtu.be/_1Bo625UaKw)



## Project：個人投資風險管家
### Our Team
業師： 玉山證券 詹益安老師  
指導老師： 台大張智星老師、東吳巨資蔡芸琤老師  
組員： 卓大一、尚旻儀、黃子騰、雷沅翰  
題目訴求： 保護新手投資人、避免投資人跟著市場動向、導致過度投資、避免投資人違約切割（高單價投資）、投資紀錄與模式偵測系統、時間序列分析、RNN、服務設計、模型表現、系統實作API  
實作方向： 特徵工程、API設計、行為數據收集、分析歸納風險行為


### 分工狀況  
雷沅翰：建立資料庫、協助其他人（目前幫忙處理line api）  
黃子騰：研究顧客行為改變的標準，作為警戒對象  
卓大一：研究股票市場的風險，可作為新的參考值  
尚旻儀：研究API

### 業師回饋
* 重點是尋找投資行為改變轉折點，而不是偵測違約交割
> 考慮是投資標的or金額的改變
> 不只參考投資人資訊還要與當時市場資訊結合(市場對標的造成的風險)
* 需要重新定義模型，因為真正違約的人很少
* 定義的模型不一定適合所有資料，需再進一步篩選所需的資料
> 從交易行為分類，可藉由平均交易量以及交易次數組合出特徵，再進行分群，篩選出適合套模型的
* 投資標的裡有些 Alpha和 Beta 是空值，而那些空值是權證，交易很少，可以忽略掉  
* 有些標的可能上架不到一年，所以年的 Beta是空值，可以考慮用季的補上  
* 調整類股分類


### 專題匯報
[專案報告](https://docs.google.com/presentation/d/1TP-TGh9Zs-lSZh_5rX7t2WVwADLVUr4E/edit#slide=id.p1)

### 最終專題成果
* [3分鐘宣傳影片](https://www.youtube.com/watch?v=AM0ttOEBENw)
* [15分鐘成果發表](https://www.youtube.com/watch?v=ejTDAt_T9tM)
* [PPT檔](https://docs.google.com/presentation/d/1QRgPRwFWCx0eQgkV_LtcVbMxnW-85lXYNJqqy9iUIM4/edit?usp=sharing)







