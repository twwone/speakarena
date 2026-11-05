# SpeakArena 演講擂台

新粗野主義風格的演講練習工具：錄音、翻簡報、交給 AI 評審講評。

**網址：** https://twwone.github.io/speakarena/

## 功能
- 錄音＋計時，結束後由 Google Gemini 聽錄音寫逐字稿
- 上傳簡報（PDF／PPTX／圖片），邊講邊用方向鍵或簡報筆翻頁，記錄每頁停留時間
- 依自訂評比重點逐項打分、算加權總分
- 四位評審（毒舌賈伯斯、邏輯鐵壁、節奏大師、溫柔文膽）各自講評
- 逐頁講評：內容是否對得上投影片、有沒有照念、轉場順不順
- 也可以上傳手機錄好的錄音檔

## 使用
1. 用 Chrome、Edge 或 Safari 打開網址
2. 按右上角 ⚙，貼上 Google AI Studio 的 Gemini API 金鑰（https://aistudio.google.com/apikey），按「測試連線」
3. 填評比重點、上傳簡報，按「開始演講」

金鑰、評比重點、講稿只存在你自己的瀏覽器裡，不會上傳到這個網站。

整個工具就是一個 `index.html`，沒有後端。
