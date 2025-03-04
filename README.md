# AI Tutor Chatbot

## 簡介
AI Tutor Chatbot 是一款基於 OpenAI GPT-3.5 的智慧家教聊天機器人，專門為國高中生提供學科輔導。使用者可以輸入問題，AI 會根據對話歷史提供適當的解答，並記憶先前的對話內容，以提供更具連貫性的學習體驗。

## 功能特點
- **記憶對話歷史**：AI 能夠記住過去的對話內容，以提供上下文相關的回答。
- **即時學科輔導**：適用於數學、語言學習、程式設計等多種學科。
- **自動管理對話歷史**：當對話超過 20 條時，自動刪除最舊的對話，確保不超出 OpenAI API 的 token 限制。
- **簡單直觀的 CLI 介面**：使用者可以直接在終端機與 AI 進行互動。

## 環境需求
- Python 3.7 以上
- OpenAI API Key
- `dotenv` 套件（用於管理 API Key）

## 安裝與執行
1. **克隆專案**
   ```sh
   git clone https://github.com/your-repo/ai-tutor-chatbot.git
   cd ai-tutor-chatbot
   ```

2. **安裝所需套件**
   ```sh
   pip install openai python-dotenv
   ```

3. **建立 `.env` 檔案並設定 API Key**
   在專案根目錄建立 `.env` 檔案，並新增以下內容：
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **執行程式**
   ```sh
   python ai_tutor.py
   ```

## 使用方式
- 啟動程式後，輸入問題即可獲得 AI 家教的回答。
- 輸入 `exit` 或 `退出` 可結束對話。
- 按 `Ctrl + C` 可強制中斷程式。

## 未來改進方向
- **優化對話歷史管理**：增加 token 計算機制，避免對話超過 OpenAI 限制。
- **自動生成練習題**：根據學生的錯誤模式提供個性化練習。
- **語音互動**：加入語音輸入與輸出功能。
- **知識推薦系統**：根據學生的學習進度推薦適合的學習內容。

## 授權
本專案採用 MIT License，歡迎自由使用與改進。



