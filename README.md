# 🍅 番茄醬節奏大師：現烤脆腸長音特訓系統 (Rhythm Ketchup Chef)

> **第一拍準時出發 ✕ 嚴密對齊長音時長！**  
> 專為音樂節奏聽覺感知與音符長度訓練設計的 HTML5 歡樂街機網頁遊戲。

![HTML5](https://img.shields.io/badge/HTML5-Pure_Web-E34F26?style=flat-square&logo=html5&logoColor=white)
![Web Audio API](https://img.shields.io/badge/Audio-Web_Audio_API-2ED573?style=flat-square)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-FF4757?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-FFA502?style=flat-square)

---

## 🎮 關於這款遊戲 (About)

《番茄醬節奏大師》是一款結合了**料理街機手感**與**嚴謹音樂教學理念**的節奏遊戲。  
玩家將在熱情親切的**台灣黑熊主廚 🐻** 帶領下，面對盤中香噴噴的「現烤脆皮香腸」，隨著進度光束與節拍，精準地在食物上擠出美味鮮紅的番茄醬長條！

### 為什麼這款遊戲能有效訓練節奏？
在許多傳統音樂或數拍教學中，初學者常遇到兩個瓶頸：
1. **找不到第一拍正拍（起拍點迷失）**  
   本遊戲透過「進度光束進場即第一拍」與前奏倒數提示，訓練玩家準確抓住樂句的第一拍。
2. **只點一下就放開，忽略了「音符的長度（時值）」**  
   本遊戲採用 **長音按壓 (Hold Notes)** 判定！如果題目是 `1 : 1 : 2`，第 3 個音符長度為 `2 拍`，玩家就必須**按住持續完整 2 拍的長度**直到音符結尾才能鬆手；若按住不放超時或放開太早，系統將給予提醒並中斷連擊。

---

## 🌟 遊戲核心特色 (Key Features)

- **🐻 台灣黑熊主廚出題互動**：全程陪練，完美擊中或失誤時會即時展現豐富的可愛表情反應。
- **🎵 依序上行聽覺音階引導**：每次按對擠醬時，系統會同步合成大調自然音階依序上升（`DO ➔ RE ➔ MI ➔ FA...`），用純粹的聽覺帶領感知目前打到了第幾拍。
- **💥 爽快街機打擊特效**：高對比電光激光流束、番茄醬星光粒子物理飛濺與餐盤彈性微震動。
- **🎲 不重複洗牌隨機關卡**：第 1 關固定為標準四拍暖身，第 2 ~ 10 關採用隨機牌庫洗牌推進，確保特訓豐富有變化。
- **🖥️ 橫屏滿版自適應 (100vw × 100vh)**：自動適應各式大螢幕、筆電與橫向平板瀏覽器。
- **🏆 本地通關進度儲存**：自動記錄每關最高通關星級與全連擊 (`FULL COMBO 👑`) 榮譽。

---

## 🚀 快速遊玩 (Quick Start)

本系統採用**純 HTML5 + Web Audio API** 架構開發，**無需安裝任何後端伺服器或 NPM 套件**！

1. 下載或 Clone 本專案至電腦：
   ```bash
   git clone https://github.com/YourUsername/Rhythm-Ketchup-Chef.git
   ```
2. 直接雙擊打開 **`rhythm_chef.html`** 即可在 Chrome、Edge、Safari 等主流瀏覽器中順暢執行。
3. **建議按 `F11` 進入全螢幕模式**，取得最佳街機沉浸體驗！

---

## 🕹️ 操作方式 (Controls)

| 操作設備 | 按鍵指令 | 說明 |
| :--- | :--- | :--- |
| **💻 電腦鍵盤** | `[ 空白鍵 Space ]`、`[ Z 鍵 ]`、`[ X 鍵 ]` | 看到光束抵達金環時**按下不放**，抵達音符結尾處**鬆手**。支援雙鍵交替連擊！ |
| **📱 行動裝置 / 滑鼠** | 觸控長按畫布 / 滑鼠左鍵按住 | 直接點按中央遊戲區域即可持續擠醬。 |

---

## 📂 素材自訂指南 (Customization)

您可以輕鬆替換同目錄下的檔案，打造屬於自己的專屬版本：

- 🎵 **背景音樂**：放入命名為 `bgm1.mp3` 的音樂檔，遊戲首頁會自動載入並循環播放。
- 🖼️ **首頁封面**：替換同目錄下的 `title_cover.png` (16:9 PNG 圖片)。
- 🏆 **全破通關賀圖**：完成 10 關後會顯示大滿貫賀圖，可替換 `cover2.png` 為自訂紀念圖。
- 💬 **社群縮圖**：替換 `social_share_thumb.png` 即可自訂社群轉貼時的封面預覽。

---

## 🔗 社群與創作者資訊 (Connect)

喜歡這款特訓遊戲嗎？歡迎追蹤創作者社群與頻道取得最新音樂與遊戲內容：

- 💬 **Threads 社群互動**：[@lycbert](https://www.threads.com/@lycbert)
- 📺 **YouTube 音樂頻道**：[@datoemusic](https://www.youtube.com/@datoemusic)

---
*Enjoy slicing beats and squeezing ketchup! Happy Rhythm Training! 🍅⭐*
