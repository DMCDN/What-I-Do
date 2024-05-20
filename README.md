
# [專題題目]畢業門檻查詢&輔助程式
![image](https://github.com/DMCDN/What-I-Do/assets/128150279/7d4d338a-67f6-4007-be70-375d40f63c4f)

每個學生的第一目標以及擔憂的就是如何畢業，也包含我自己，再加上專題導師帶的畢業生也總是在畢業前才發現自己疏漏了某項畢業門檻。
因此大學專題選擇開發一款 提供給學生查詢、並輔助完成畢業門檻的軟體 ，讓應屆畢業生或是本系學生能夠使用。

* 包含網頁與軟體：
    - 網頁：軟體介紹、下載，會員、軟體啟用功能
    - 軟體：主程式功能、更新系統、軟體啟用檢測系統

* 使用Python開發
    - UI：PyQt6
    - 打包工具：Nuitka
    - 網頁：Flask
    - 資料庫：SQLite3

* 使用的第三方套件&用途：
  - requests：爬取學生資料、對網頁API發送GET/POST請求
  - BeautifulSoup：網頁資料處理
  - pickle：儲存/使用Cookies
  - Crypto.Cipher：文件加密/解密
  - hashlib：紀錄/檢測文件或資料的Hash值
  - zstandard、lzma：文件壓縮/解壓
  - traceback、logging：紀錄程式錯誤訊息
  - concurrent.futures：多線程操作
  - Flask：製作網頁後端功能

**詳細介紹：https://github.com/DMCDN/LHWork**

# [學校作業]網路購物平台功能實作
 ![image](https://github.com/DMCDN/What-I-Do/assets/128150279/dd79c259-c5f5-4372-ae87-9c972f0ca2e2)
  
  學校期末作業，使用ASP.NET製作的一個虛擬購物平台網頁
* 程式語言：
  - 後端：C# 
  - 資料庫：MSSQL

* 會員功能：
    - 基本的登入、登出、註冊功能
    - 使用Cookie實現"記住我"的功能
* 商品功能：
    - 使用GridView物件與SQL Select指令連接
    - 商品篩選功能實作
    - 購物車功能實作

**詳細介紹：https://github.com/DMCDN/ASP.NET-Work**

# [Discord Bot]服務馬文
![image](https://github.com/DMCDN/What-I-Do/assets/128150279/f1006b1b-564c-4a8f-9736-42009fd72753)

早期作品，使用Python設計的Discord群組機器人，曾經在99個群組內服務

* 設計一些與用戶互動、或是群組管理功能：
    - 動態語音頻道管理
    - 自定義歡迎訊息
    - 批量刪除訊息
    - 提取指定用戶頭像(取最高畫質)

* 串接API，為遊戲玩家設計出的功能：
    - 基本玩家資料查詢
    - 對局玩家資料批量查詢
    - 玩家分數動態追蹤
    - 個人每日商城提取(並額外提供物品相關資訊)

* 使用的第三方套件&用途：
  - discord.py：Discord API wrapper
  - psutil：獲取電腦狀態(CPU/GPU/RAM使用率等)
  - Crypto.Util：加密/解密用戶資料
  - requests：對網頁API發送GET/POST請求
  - traceback、logging：紀錄程式錯誤訊息

**詳細介紹：https://github.com/DMCDN/MRVN_Bot**

# [漏洞分析紀錄]紀錄某更新程序的漏洞
  ![image](https://github.com/DMCDN/What-I-Do/assets/128150279/266f8afc-e9f1-440a-9877-79f233ae0a56)

  某公司提供的遊戲更新服務，早期許多開發商使用此服務時都犯的錯誤，可能會使開發版本遭外洩，進而導致許多問題(如開發版本附帶的GM功能被研發成作弊程式，未上市活動、美術資源被提前洩漏)
  
  使用抓包、逆向工具分析資料傳輸方式後，再寫一個Python腳本修改並遍歷關鍵值ChannelID。
  
**詳細介紹：https://github.com/DMCDN/GlitchLog-UpdateSys**

