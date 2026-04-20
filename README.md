# ime_doc_archive

台灣中文輸入法歷史文件的整理與保存庫。

這個 repository 將 1990 年代到 2000 年前後的中文輸入法說明文件，整理為可瀏覽的 Markdown 與 MkDocs 靜態網站，方便查閱、比對與考古。

## 目前收錄

-   微軟新注音輸入法 98
-   微軟新倉頡輸入法 98
-   倚天中文 2000
-   自然輸入法 99
-   漢音輸入法 4 for macOS
-   漢音輸入法 5 for macOS
-   漢音輸入法 4.02 for Windows
-   漢音輸入法 5.02 for Windows
-   Mac OS 9 繁體中文輸入法文件

各套文件的來源與背景，見 [`docs/index.md`](docs/index.md)。

## 專案結構

```text
.
├── docs/          # MkDocs 站台內容
├── mkdocs.yml     # 導覽與站台設定
├── README.md
└── CONTRIBUTING.md
```

`docs/` 下通常以產品或版本分目錄，每個目錄內保留該套文件的 Markdown 頁面與相關圖片資源。

## 使用方式

安裝 MkDocs 後，可在 repo 根目錄執行：

```bash
mkdocs serve
```

或輸出靜態站：

```bash
mkdocs build
```

## 編修原則

這個 repo 的重點是「保存」而不是「重寫」。整理時優先保留原始文件的資訊與時代語境，只做必要的結構化與可讀性修正。

具體規範見 [`CONTRIBUTING.md`](CONTRIBUTING.md)。

## 適合補強的方向

-   補齊各套文件的來源註記與版本資訊
-   檢查大小寫敏感環境下的圖片與連結
-   統一 front matter 與頁面標題格式
-   補上轉檔流程說明，降低後續整理成本
