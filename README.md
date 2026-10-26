# 校書臺

**網址：<https://jiaoshutai.github.io/>**

校書臺是一個離線使用的列級校對工具。它讀取 eScriptorium 導出的 PAGE／ALTO XML 及對應的書頁圖片，逐列把裁切放大的原圖與轉寫並排顯示，供校對者判定、修改或獨立錄文。

## 資料留在本機

圖片、XML 與校對進度存於本機，無需上傳到網頁；無需聯網使用。在工具內點「導出進度 JSON（整本）」，即可導出進度。

## 從 Chrome 安裝

1. 用電腦版 Chrome 打開 <https://jiaoshutai.github.io/>。
2. 點網址列右側的安裝圖示，或打開選單 ⋮ →「投放、儲存及分享」→「安裝 校書臺」。
3. 安裝後，校書臺會出現在應用程式清單或 Dock 中。

有新版本時，已安裝的校書臺會在下次打開時自行更新。

## AI 使用聲明

校書臺的第一版完成於 2026 年 7 月。同年 10 月藉助 Claude Design（Anthropic）重新設計：作者提供原有工具、配色色值，以及使用說明頁裝飾圖所用的照片；定稿後，由 Claude Design 產出供開發使用的設計原型與交接規格。

自 2026 年 10 月起，大部分程式碼由 Claude Code（Anthropic）在作者指導下撰寫，分為三類：

- 把本機 HTML 檔改成可安裝、可離線使用的網頁應用程式，並發佈到 GitHub Pages；
- 實現介面設計的更新：
    - 三種配色主題與使用說明頁的裝飾圖；
    - 依最新的轉寫規則更新介面；
    - 加入盲轉寫模式；
- 修正錯誤：
    - 進度保存：重新開啟後自動恢復頁面清單與資料夾，導出時不再遺漏先前工作階段的頁面；
    - 載入：可一次載入多個資料夾，圖片與 XML 不論先後都能配對；
    - 更新：已安裝的版本能自動收到新版本。

每項修改都經作者測試，作者對本工具負責。

## 圖像來源

- **Icon**：作者設計。
- **使用說明頁裝飾圖**：取自西漢日月四神紋錯金青銅當盧，出土於江西南昌海昏侯劉賀墓，現藏江西省博物館。剪影由 Claude Design 依[百度百科](https://baike.baidu.com/item/%E8%A5%BF%E6%B1%89%E6%97%A5%E6%9C%88%E5%9B%9B%E7%A5%9E%E7%BA%B9%E9%94%99%E9%87%91%E9%9D%92%E9%93%9C%E5%BD%93%E5%8D%A2/64146354)的照片製作。

---

# 校書臺 (Jiaoshutai)

**Address: <https://jiaoshutai.github.io/>**

校書臺 is an offline, line-level collation tool. It reads PAGE/ALTO XML exported from eScriptorium together with the matching page images, and shows each line as a cropped, enlarged image beside its transcription, so collators can check it, correct it, or transcribe it independently.

## Data stays on your computer

Images, XML and collation progress are stored on your computer; nothing needs to be uploaded to the web, and no internet connection is needed. Click 'Export progress JSON (all pages)' in the app to export your progress.

## Install from Chrome

1. Open <https://jiaoshutai.github.io/> in Chrome on a computer.
2. Click the install icon at the right end of the address bar, or open the ⋮ menu → Cast, save, and share → Install 校書臺.
3. Once installed, 校書臺 appears in your app list or in the Dock.

When a new version is published, installed copies update themselves the next time they open.

## AI use

The first version of 校書臺 was completed in July 2026. In October 2026, it was redesigned with Claude Design (Anthropic). The author supplied the existing tool, the color values and the photograph used for the Help-page decoration. Once the design was final, Claude Design produced a prototype and a handoff specification for development.

Since October 2026, Claude Code (Anthropic) has written most of the code under the author's direction. Its work falls into three areas:

- turning the local HTML file into an installable web app that works offline, and publishing it on GitHub Pages;
- implementing interface updates:
    - the three color themes and the Help-page decoration;
    - interface changes that follow the latest transcription rules;
    - a blind-transcription mode;
- fixing bugs:
    - saving progress: the page list and folders reopen after a restart, and exports no longer leave out pages from earlier sessions;
    - loading: several folders can be loaded at once, with images and XML paired in any order;
    - updates: installed copies now receive new versions automatically.

The author tested every change and is responsible for the tool.

## Image credits

- **Icon:** designed by the author.
- **Help-page decoration:** based on a Western Han gold-inlaid bronze horse frontlet (*danglu*) with sun, moon and Four Spirits motifs, excavated from the tomb of Liu He, Marquis of Haihun, in Nanchang, Jiangxi, and now in the Jiangxi Provincial Museum. Claude Design made the silhouette from a photograph on [Baidu Baike](https://baike.baidu.com/item/%E8%A5%BF%E6%B1%89%E6%97%A5%E6%9C%88%E5%9B%9B%E7%A5%9E%E7%BA%B9%E9%94%99%E9%87%91%E9%9D%92%E9%93%9C%E5%BD%93%E5%8D%A2/64146354).
