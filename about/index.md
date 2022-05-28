您好，我是謝明宏，我來自台灣新北市淡水區 

## 個人資訊
####謝明宏

> email: jacob2hsieh@gmail.com   
> line-id: adodoh （_大雄_，因為開啟陌生加入，請另通知已加入好友）		 

![Jacob](../imgs/mylogo.jpg)

## 電腦專長

**前端開發：**
HTML / CSS3 / Javascript / JQuery / Bootstrap

**後端開發：**
ASP.net Core (C#, MVC）/  PHP (LAMP , fastCGI)

**資料庫：**
mySql / MSSql 

**作業系統：**
Windows / MacOS / Linux (Centos)

**虛擬平台:**
Docker 

**源碼：**
gitHub

**個人學習過的課程：**
iOS swift 手機設計，Vue 2.0  

## 工作經歷
依時間順序，由近及遠：

> #####宸毅科技 (2020-04-01 ~ 2021-10-15, 1.5年) 
~~~
* 職位：公司股東	
* 任務：前後台開發，API串接
* 資料庫：mySql 設計，維護
* 系統：CentOS 7 
* 主要工具：ASP.net Core MVC / jQuery / Redis / ELK	
~~~
> 
> #####諾傑 Nogle (2018-01-01 ~ 2020-03-31, 2年) 
~~~
* 職位：資深程式設計		
* 任務：前後台開發與支援其他專案
* 資料庫：mySql 維護
* 系統：Window Server / CentOS 7
* 主要工具：ASP.net Core MVC / jQuery / PHP  
~~~

> #####瑞嘉科技 (2010-01-01 ~ 2017-12-31, 7年) 
~~~
* 職位：MIS主管	
* 任務1：MIS 人事相關程式開發
* 任務2：支援其他單位開發
* 資料庫：MSSQL 設計，維護
* 系統：Window Server
* 主要工具：C# AP / ASP.net / jQuery     
~~~

> #####其他 (？ ~ 2017-12-31 )		
> ######華亞科技(美光)，威盛電子 ......		

## 最近一次工作內容

主要是負責全端開發，
製作管理者站台，客戶站台，第三方API回調，即時聊天室互動等。

### 工作伺服器環境介紹
~~~
* 系統：CentOS 7
* Web：Nginx，load balance  
* DB：Mariadb，db複寫，讀寫通過 stored procedure
* 後端：ASP.net Core，編譯，Linux service enabled
* 快取：Redis
* Log查詢：Kibana（ELK）
* Log Message：Telegram API 傳遞訊息
~~~

### 管理者介面
使用 AdminLTE 的 Bootstrap 改版，
登入介面與部分操作有 Google 的第二步驗證，
一帳號只能登入一台電腦，網頁驗証標頭採 JWT，
登入後網站是 SPA 一頁式的呈現方式，讀寫全採用AJAX來做資料傳遞。


### 客戶站台：
分別有信用卡刷卡，後端是接第三方信用卡公司API，與礦商合作進行泰達幣USDT交易。
也有各項支付通道畫面，後端也是串接API與產生條碼。
以上皆有電腦與手機網頁版本。手機是使用 OnsenUI 的免費套件

 
### 即時聊天室
運作在 PHP Workerman上，分為 server 端即時通訊 與 client端客戶介面及管理者介面。
即時通訊是 server 的 php port 連接 client 網頁的 socket.io，網頁上的功能有即時談話，
廣播，禁言與踢出，與擴充其他的客製行為。登入的角色有管理者與訪客的


以上在 gitbook 裡會另外說明，謝謝。


 