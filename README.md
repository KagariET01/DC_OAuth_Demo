# DC_OAuth_Demo

實作：使用DC做為網頁的第三方登入

### 正在尋找更安全、更詳細、更完整的做法？請考慮[discordjs.guide](https://discordjs.guide/oauth2/)的官方文件

## 架設教學：

0. 登入[DC](https://discord.com/login)  
0. 進入[DC Dev - APP管理介面]([https://discord.com/developers](https://discord.com/developers/applications))
0. 點擊右上角的 "New Application" 建立一個應用程式
0. 為你的應用程式命名、勾選同意、Create  
   ![image](https://github.com/user-attachments/assets/35c39c25-bd74-46e2-9fa1-b5ad57816be6)
0. （可選）美化你的應用程式（打簡介、上頭貼、......）  
0. 進入OAuth2設定頁面  
   ![image](https://github.com/user-attachments/assets/93f26735-937d-4269-bc1d-6b495bdd604d)
0. 點Add Redirects
0. 新增網址，使用者在DC授權後，會自動導向到這個網址
0. 如果你有多個網站節點，可以用Add Another新增更多站點
0. 最後：記得儲存
   ![image](https://github.com/user-attachments/assets/94c349b6-c361-4fa8-af84-bc5002a58c98)
0. 勾選identify
0. 選擇你的網站(ex: http://localhost)
0. 複製產生出的URL
   ![image](https://github.com/user-attachments/assets/3e30a9eb-6b2c-4855-b505-65c565f762ae)
0. 將 `index.html` line 4的網址改成你剛剛複製的網址
   ![image](https://github.com/user-attachments/assets/68bb1b2e-f935-4b25-944a-0275a93659b5)
0. 將網站上架(上架的網址和11. 選擇的網址要是一樣的

