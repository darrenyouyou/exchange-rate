# 高鐵時刻表查詢應用程式

這是一個用於執行外匯轉換的應用程式。您可以使用它來查看不同貨幣之間的匯率，以及進行貨幣轉換，以視覺化的方式呈現各國的匯率。

## 功能

這個應用程式提供以下功能：

- 顯示不同貨幣之間的當前匯率。
- 提供各種貨幣的匯率數據。

## 如何運行

要運行這個應用程式，您需要執行以下步驟：

1. 安裝相依套件：在項目資料夾中執行以下命令以安裝相依套件

2. 申請 open API ：這個應用程式使用了一個外部 API，您需要提供有效的 API 。請將您的 API 更新到 `constants.js` 檔案中的 `clientID` 和 `clientSecret`。

3. 運行應用程式：執行以下命令以啟動應用程式：

4. 使用應用程式：在瀏覽器中打開 [http://localhost:3000](http://localhost:3000) 來開始使用應用程式。

## 技術堆疊

這個應用程式使用了以下技術堆疊：

- 前端：React
- 狀態管理：useState 和 useEffect 
- 外部 API：openExchangeRate API
- 使用者界面：CoreUI 

## 屏幕截圖

![應用程式截圖](photo2.png)
![應用程式截圖](photo3.png)
