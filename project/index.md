# 專案說明

#### 經營目標

成立軟件服務中心，租借服務給予廠商使用，由其經營客戶 

#### 工作伺服器
* 系統：CentOS 7
* Web：Nginx，load balance  
* DB：Mariadb，db複寫，讀寫通過 stored procedure
* 後端：ASP.net Core，編譯，Linux service enabled
* 快取：Redis / Server Cache
* Log查詢：Kibana（ELK）
* Alarm Message：Telegram API 傳遞訊息

#### UI 設計
Bootstrap AdminLTE / OnsenUI (Mobile app) / SPA Webpage (C# 裡的 PJAX + AJAX 實現)

#### 登入驗証
JWT Header /  Google Authenticator 2FA 

#### 邏輯說明
* `總管理`：建立管理`分站台`
* `分站台`：建立管理`商戶`
* `商戶`： 營銷管理

## 網站
#### 總管理
* 建立管理分站台，限制黑名單白名單，並踢除與限制使用者的權限，與操作檢視分站台與商戶的資料與安全性控制。

#### 分站台
* 建立管理商戶，限制黑名單白名單，並踢除與限制使用者的權限，與操作檢視商戶的資料與安全性控制。
* 管理金流通道

#### 商戶
* 建立管理帳戶
* 管理支付通道，信用卡 / USDT / 支付寶等相關
* 電腦版畫面與行動裝置畫面
 
## 維護即時聊天室
運作在 PHP Workerman上，分為 server端的 TCP port 與 客戶 / 管理者介面。	
client 透過 socket.io 與 server 溝通。功能有即時談話，廣播，禁言與踢出，與擴充的客製行為。