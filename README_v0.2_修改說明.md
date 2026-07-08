# Kreiner B2B 網站 v0.2 — 修改說明

日期：2026-07-08
依據：Mabel 轉交的 Neville 意見（Kreiner OEM Website.docx）＋ Lyric 決策

## 本版修改（相對 v0.1）

### 1. 中國定位修正（Neville 意見 #4）
- 全站（EN＋ZH）將「China — Partner Facilities／中國合作工廠」改為
  「China — Main Manufacturing Hub／中國 — 主要生產基地」。
- 影響頁面：index、about（公司簡介＋集團實體）、why-kreiner（對比表）、
  contact（直接聯繫渠道新增中國基地一列）、頁尾文案、meta description。
- 原 TODO-A02（中國揭露程度待定）已因決策確定而移除；
  新增 TODO-C05d（中國基地地址待補）。

### 2. 新增 Request a Call／預約回電（Neville 意見 #2）
- 首頁 Hero 新增「Request a Call／預約回電」按鈕。
- Contact 頁新增金色邊框回電卡片（#request-call）：
  姓名、公司、電話/WhatsApp、國家與時區、方便時段。
  表單為靜態 demo，後端待接（TODO-C08）。
- 產品詳情頁模板、首頁詢盤區、頁尾均加入回電入口。

### 3. 英文全站潤飾（Neville 意見 #5）
- 逐頁打磨用字（例：held on → held by、designer bathtubs、
  can't say → simply can't make 等）。
- 英文頁面全形括號（）改半形 ()。

### 4. 視覺設計升級（Neville 意見 #1，設計師到位前的過渡版）
- 字體：標題 Archivo、內文 Inter（Google Fonts）。
- Hero：多層漸層＋光暈＋細格紋理、標題底部金色飾線、字級加大。
- 各區塊新增 eyebrow 小標（金色大寫小字）。
- 卡片／步驟／產品卡 hover 浮起與陰影、按鈕 hover 狀態、
  表單 focus 金色光圈、統計數字區改分隔線排版、頁尾加金色頂線。
- 間距整體加大（section 80px）。

### 5. 修復 3D 渲染圖
- v1 的 renders 資料夾在本機是空的（圖檔遺失，全站破圖）。
- 已從「Australia/客製化浴缸專案/3D渲染圖轉換成CAD圖/renders」
  補齊 18 張 .webp 至 v2/renders。

## 未改動
- 所有 TODO 佔位標記保留（除 TODO-A02），資料到位後逐一替換。
- 表單仍為靜態 demo；正式版需接 CRM／email／reCAPTCHA（TODO-C04）。

## 待 Neville／Mabel 確認
- 中國「主要生產基地」的英文措辭是否符合預期。
- 視覺升級後是否仍需外聘平面設計師（實景照片仍是質感關鍵）。
