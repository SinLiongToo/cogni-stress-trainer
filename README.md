# 🧠 CogniStress Ultimate & Sudoku Master
### 高壓認知決策 × 專注數獨工坊 — 神經抗衰與邏輯巔峰訓練系統

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-success?logo=github)](https://sinliongtoo.github.io/cogni-stress-trainer/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20(Pure%20Vanilla%20JS)-purple.svg)](#技術架構)
[![Web Audio API](https://img.shields.io/badge/Audio-Web%20Audio%20API-orange.svg)](#生體動態壓力機制)

---

## 📌 緣起與雙核心架構 (System Architecture)

現代神經科學與認知心理學指出，維持大腦神經可塑性（Neuroplasticity）與防範認知退化（防失智），需要兩種互補的思維刺激：

1. **⚡ 高壓動態反應訓練（極限面試與應變決策）**：在極短時限與生理緊迫下（如外商 McKinsey、BCG、投行及科技巨頭評估中心），調動背外側前額葉皮質（DLPFC），克服杏仁核帶來的恐慌與確認偏誤。
2. **🧩 靜態深度專注訓練（數獨排除與邏輯推理）**：在免於計時壓迫的沉浸環境中，透過嚴謹的數理刪去法、候選數推導與全域空間檢索，深度鍛鍊頂下小葉與海馬迴的工作記憶與空間關聯。

本系統採用**雙核心獨立分流架構**，首頁頂部提供一鍵切換分頁，亦支援 URL Hash（`#stress` 與 `#sudoku`）直達，兩者在邏輯運算、鍵盤監聽與音效系統上**徹底分開、獨立運作**。

---

## 🚀 線上即時體驗 (Live Demo)

🔗 **GitHub Pages 線上直接玩**：  
👉 [https://sinliongtoo.github.io/cogni-stress-trainer/](https://sinliongtoo.github.io/cogni-stress-trainer/)

* ⚡ **高壓認知訓練模組**：[https://sinliongtoo.github.io/cogni-stress-trainer/#stress](https://sinliongtoo.github.io/cogni-stress-trainer/#stress)
* 🧩 **專注數獨工坊模組**：[https://sinliongtoo.github.io/cogni-stress-trainer/#sudoku](https://sinliongtoo.github.io/cogni-stress-trainer/#sudoku)

*(完全免安裝、零外部伺服器依賴、全站純前端離線可用，支援桌面全鍵盤快捷鍵與手機/平板觸控)*

---

## 🧩 模組一：五大高階認知維度 (CogniStress Ultimate)

針對世界級管理顧問公司、外商投行及科技業高階筆試設計：

| 維度 | 經典測驗機制 | 面試實戰應用 | 神經科學與防失智機制 |
| :--- | :--- | :--- | :--- |
| **🧩 3×3 瑞文與展開圖** | **XOR 疊加相消律**、正方體 6 面十字展開圖心智摺疊 | 對標 Mensa 門薩智商測驗、SHL 抽象推理 | 鍛鍊頂枕葉三維空間旋轉與視知覺解構能力 |
| **⚙️ 機械齒輪物理** | 4～5 級齒輪連動咬合、轉向反轉律與齒數速比計算 | 對標外商工程、科技業物理機械筆試 | 刺激大腦頂葉的「動態心智物理模擬 (Mental Simulation)」 |
| **📊 數理矩陣與商務速算** | 3×3 行列複合函數方陣、符號天平代數置換、商業季度圖表環比估算 | 對標投行 Quantitative Math、管顧 Case Fast Math | 活化頂內溝與海馬迴短期數理運算存取 |
| **🔤 批判推理與證偽** | 多條件假言三段論、德摩根定律否定轉換、**Wason 4-Card 證偽任務** | 對標 GMAT、Watson-Glaser 決策能力測試 | 抑制「確認偏誤 (Confirmation Bias)」，強化前額葉嚴謹邏輯 |
| **🧠 雙重工作記憶 2-Back** | 9 格光點連續推進，動態比對滑動隊列中 2 題前的點位 | 國際醫學界唯一證實可擴充流體智力 (Fluid Intelligence) | 高強度活化背外側前額葉皮質 (DLPFC) 與工作記憶容量 |

### ⚡ 生體動態壓力引擎
* **三檔極限秒數**：⚡ 極限競賽 (6s)、🎯 外商標準 (10s)、🧠 深思熟慮 (18s)。
* **加速心跳生物反饋**：Web Audio API 原生合成。最後 4 秒心跳由 **80 BPM 飆升至 150 BPM**，螢幕伴隨脈衝紅光邊框，模擬臨場心跳加速逆境。
* **快捷鍵秒答**：鍵盤 <kbd>1</kbd>、<kbd>2</kbd>、<kbd>3</kbd>、<kbd>4</kbd> 秒速作答。
* **全維度診斷評估**：五軸動態 SVG 雷達圖、推算大腦神經年齡（20s 頂峰腦 ➔ 60s 疲憊腦）、本機錯題專攻庫（LocalStorage）。

---

## 🔢 模組二：專注數獨工坊 (Sudoku Master)

與高壓模組獨立分開的沉浸式數獨空間，提供世界標準的九宮格邏輯思維挑戰：

### 1. 核心機制與演算法
* **程序式保證解生成（Procedural Backtracking Generator）**：對角 3x3 九宮格獨立隨機填充，配合回溯搜索解題演算法，以挖洞法精確生成具備唯一邏輯解之謎題。
* **四級難度梯度**：
  - 🌱 **初階入門 (38 已知數)**：適合熱身與直觀排除法演練。
  - 🌿 **中階進階 (30 已知數)**：需要基礎行、列、宮交錯推理。
  - 🔥 **高階骨灰 (25 已知數)**：考驗區塊刪除法（Pointing/Claiming）與隱性數對。
  - 👑 **專家大師 (21 已知數)**：極限骨灰級挑戰，極考驗多步驟候選數推導。

### 2. 人性化輔助與電競級操作介面
* **✏️ 鉛筆草稿模式（Pencil Notes）**：支援在單元格內標註 1～9 候選數（3x3 迷你排列），按快捷鍵 <kbd>N</kbd> 即時切換。
* **🎯 十字聚焦與全域同數發光**：選中格自動高亮所在行、列與 3x3 宮，點擊數字時全盤相同數字同步高亮，瞬間洞察空間布局。
* **⚠️ 行列宮衝突實時警示**：違規數字填入時即時紅字警示與震動動畫。
* **❤️ 3 次失誤扣血機制**：防範亂猜盲填，培養嚴謹推導習慣。
* **💡 智慧提示 (Hint) 與 ↩️ 復原 (Undo)**：卡關時一鍵揭曉正確數字，亦可隨時撤銷填入。
* **⌨️ 完整鍵盤快捷鍵**：
  - <kbd>1</kbd> ～ <kbd>9</kbd>：填入數字 / 標註草稿
  - <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd>：移動聚焦格
  - <kbd>Backspace</kbd> / <kbd>Delete</kbd>：清除單元格
  - <kbd>N</kbd>：切換鉛筆草稿模式
  - <kbd>H</kbd>：獲取提示
  - <kbd>Z</kbd>：復原上一步

---

## 🔥 開始前的實例暖身 (Interactive Warm-Up Guide)

在高壓倒數計時開始之前，系統提供專屬的「**🔥 題型實例與解題熱身**」互動導引系統，協助建立推導手感與消除慌亂：

* **視覺化題目實例拆解**：
  - **瑞文 XOR 疊加圖解**：透過雙圖疊加相消、保留相異的 SVG 視覺展示，具體理解幾何邏輯。
  - **立方體 6 面展開圖**：「同排隔一格必為相對面」的心智折疊技巧與反向排除法。
  - **齒輪物理心智模擬**：奇數級咬合同向、偶數級反向；齒數與轉速圈數的守恆等式（$N_1 \times T_1 = N_2 \times T_2$）。
  - **天平代數置換**：共用仲介符號代換心法與商業百分比（15% = 10% + 5%）心算拆解。
  - **沃森 4-Card 證偽反駁**：擊破「確認偏誤」，透析為何必須檢查「肯定前件 P」與「否定後件 非 Q」。
  - **2-Back 雙重記憶**：滑動窗口佇列的心智更新機制（比對 $K-2$ 刺激）。
  - **數獨三大解法**：唯一數法 (Naked Single)、隱性單數法 (Hidden Single) 與鉛筆筆記法。
* **各題型互動自我小試 (Mini Warm-Up Quizzes)**：
  - 每個題型均配有一道獨立熱身試題，使用者可點擊選項進行自我檢測。
  - **完全不計入計時與測驗成績**，並即時給予對錯反饋、音效提示與詳細思維解析，支援一鍵重試！

---

## 🛠️ 技術架構 (Tech Stack)

* **架構**：單一檔案自包含 (Zero-Dependency Single-Page App)
* **樣式**：Tailwind CSS (深色太空科技 HUD 風格，完美適配行動裝置與桌面寬螢幕)
* **向量圖形**：原生 SVG（幾何九宮格、展開立方體、齒輪咬合物理、雷達圖全向量渲染）
* **音訊合成**：Web Audio API (OscillatorNode, GainNode 純程式物理波形生成)
* **狀態管理與儲存**：Client-Side LocalStorage 儲存錯題與紀錄，100% 離線隱私保障

---

## 💻 本地運行 (Local Run)

無需安裝 Node.js、npm 或任何編譯工具：
```bash
# 1. 複製專案
git clone https://github.com/SinLiongToo/cogni-stress-trainer.git

# 2. 開啟 index.html
cd cogni-stress-trainer
# 直接用任何現代瀏覽器（Chrome, Edge, Safari, Firefox）雙擊 index.html 即可運行！
```

---

## 📜 授權協議 (License)

本專案基於 [MIT License](LICENSE) 開源授權，歡迎自由學習、訓練、推廣與改進。
