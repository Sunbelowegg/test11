# 員工行程表管理系統

一個專業的員工行程表管理系統，支援多員工、多週期、多筆行程記錄，具備現代化介面和自動化功能。

## 功能特色

### 📅 行程管理
- **個人行程頁面** (`employee-schedule.html`)：每位員工可獨立填寫個人行程
- **週次切換**：支援多週期資料管理，自動產生正確日期
- **多筆行程**：每天可記錄多筆客戶拜訪或工作內容
- **自動儲存**：使用 localStorage 自動保存資料

### 🚗 加油記錄
- **加油標記**：可標記每日是否有加油
- **公里數記錄**：記錄加油時公里數和公升數
- **彙整功能**：自動計算每日行駛里程

### 👥 員工管理
- **動態員工名單**：可新增、刪除、編輯員工姓名
- **獨立頁面**：每位員工有專屬填寫頁面
- **資料同步**：個人頁面與總覽頁面資料即時同步

### 📊 總覽功能
- **週表總覽** (`weekly-schedule-summary.html`)：依員工橫向顯示週表
- **公里數彙整**：顯示所有員工本週每日里程統計
- **專業版面**：現代化設計，支援響應式佈局

### 🎨 使用者體驗
- **主題切換**：支援深色/淺色主題
- **自動化操作**：行程表自動補空白行，無需手動新增
- **預設時間**：上下班時間預設為 08:30-18:00
- **頁面導航**：頁首快速切換連結

## 檔案結構

```
行程表/
├── employee-schedule.html          # 員工個人行程頁面
├── weekly-schedule-summary.html    # 週表總覽頁面
├── .gitignore                      # Git 忽略檔案
└── README.md                       # 專案說明文件
```

## 使用方式

1. **開啟個人行程頁面**：點擊 `employee-schedule.html`
2. **填寫員工資訊**：在頁面頂部編輯員工姓名
3. **選擇週次**：使用週次選擇器切換不同週期
4. **填寫行程**：直接在表格中填寫每日行程
5. **記錄加油**：勾選加油選項並填寫相關資訊
6. **查看總覽**：點擊頁首連結切換到總覽頁面

## 技術特色

- **純 HTML/CSS/JavaScript**：無需額外依賴
- **localStorage**：資料自動保存於瀏覽器
- **響應式設計**：支援各種螢幕尺寸
- **現代化 UI**：圓角、陰影、hover 效果
- **主題系統**：深色/淺色主題切換

## 資料備份

系統支援多種備份方式：
- **本機下載**：可匯出 JSON 格式資料
- **雲端備份**：支援 Google Drive、Dropbox 等
- **Email 備份**：可透過 Email 發送備份檔案

## 瀏覽器相容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 授權

此專案為開源專案，可自由使用和修改。

---

**注意**：資料儲存於瀏覽器 localStorage，清除瀏覽器資料會導致資料遺失，建議定期備份重要資料。 