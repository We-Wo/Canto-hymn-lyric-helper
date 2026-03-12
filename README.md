# Canto-hymn-lyric-helper
Helper tool for writing Cantonese hymn lyrics, offering Jyutping-to-character lookup and tone-sequence matching.

✝ 粵語詩歌創作助手 (Cantonese Hymn Writer)

👉 **[點擊這裡立即使用線上版](https://chimerical-dodol-031671.netlify.app/)**

📖 關於此工具 (About)

這是一個專為粵語詩歌創作者、敬拜主領與填詞人設計的網頁輔助工具。寫粵語歌最大的挑戰在於「啱音」（聲調必須與旋律走向一致），本工具內建了豐富的基督教專屬詞庫，幫助你透過聲調、粵拼或主題，快速找到適合填入旋律的字詞。

本專案完全在本地端（瀏覽器內）運行，無需連網、不收集任何使用者資料。

✨ 核心功能與使用教學 (Features & Tutorial)

本工具包含三個主要面板，點擊上方標籤即可切換：

1. 🎼 聲調查字 (Tone Search)

使用情境：你已經寫好了一段旋律，需要找對應聲調的詞語填進去。

如何使用：

根據旋律的高低起伏，點擊畫面上的聲調數字按鈕（1至6）。

例如：你想找一個先「低平」後「高平」的詞，就依序點擊 4 和 1。

點擊「查詞語」，系統會優先列出完全吻合的基督教詞彙（例如：「耶穌」、「全知」、「平安」）。

2. 🔡 粵拼搜字 (Jyutping Search)

使用情境：你想到一個發音，但不知道有哪些中文字，或者想找某個發音的詞語。

如何使用：

單字查詢：輸入單一粵拼（例如 jan1），系統會列出所有發這個音的單字（如：恩、因、殷）。

多字查詢：輸入多個粵拼（中間以空格隔開，例如 jan1 din2），系統會推薦對應的詞語（如：恩典）。

3. 🏷️ 主題詞庫 (Topical Dictionary)

使用情境：你缺乏靈感，需要特定主題的詞彙庫來激發寫詞方向。

如何使用：

直接點擊畫面上的快速標籤（如：讚美、敬拜、感恩、救恩等）。

系統會列出所有與該主題相關的常用詩歌詞彙，並附上每個字的粵拼與聲調，方便你直接套用進樂譜中。

🛠️ 給開發者：如何在本地執行 (Local Setup)

這個專案採用極簡的前端架構，極度輕量且易於修改：

技術棧：純 HTML5 + CSS3 + Vanilla JavaScript (無框架)

資料庫：所有詞庫皆內建於 JS 陣列中，無外部 API 依賴。

執行方法：

下載本專案的 .zip 檔，或使用 git clone 複製到本地。

確保 index.html 和 style.css 在同一個資料夾。

直接對著 index.html 連按兩下，用 Google Chrome、Safari 或任何現代瀏覽器開啟即可使用。

🤝 貢獻 (Contributing)

如果你發現有漏掉的基督教常用詞彙，或是發現聲調標示錯誤，歡迎發起 Issue 或提交 Pull Request 來幫助完善這個詞庫！
