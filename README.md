# 密室脫逃遊戲｜期中作業

三人協作開發純 HTML、CSS、JavaScript 前端密室脫逃遊戲。

## 三條分支與分工

| 分支 | 職責 | 工作範圍 | 預計維護或新增的檔案 | 負責人 |
| --- | --- | --- | --- | --- |
| [story-assets](https://github.com/K-BVL/escape-room-midterm/tree/story-assets) | 劇情與素材 | 故事背景、遊戲流程、謎題文案、線索、提示、結局；整理圖片、音效及素材授權 | BRIEF.md 的故事與流程；content/；assets/；CREDITS.md；VERIFY.md、TESTS.md 中的劇情與謎題項目 | 待組內分配 |
| [web-mechanics](https://github.com/K-BVL/escape-room-midterm/tree/web-mechanics) | 網站與機關 | 網頁結構、版面、互動、機關判定、遊戲狀態及前端串接 | index.html；CSS、JavaScript；PLANS.md；VERIFY.md、TESTS.md 中的網頁與機關項目 | 待組內分配 |
| [test-integration](https://github.com/K-BVL/escape-room-midterm/tree/test-integration) | 測試與整合 | 測試案例、通關與錯誤路線、重置與邊界情況；整合檢查、試玩問題追蹤、部署驗證及交付文件 | TESTS.md 的測試紀錄；VERIFY.md 的整合驗收；必要的測試程式與測試報告；README.md 的啟動及操作說明 | 待組內分配 |

上表列出的是預計工作範圍；目前建立分支與分工說明，不代表遊戲、素材或測試已完成。

## 各職責的完成條件

- 劇情與素材：提供完整故事與線索、每題答案和提示；素材逐一註明來源與授權。
- 網站與機關：依約定流程實作純前端遊戲，讓操作、機關判定與遊戲狀態可驗證。
- 測試與整合：依 VERIFY.md 的預期行為執行測試，在 TESTS.md 記下步驟、實際結果與問題；未執行的項目明確標為「未測」。

## 協作規則

1. main 用來整合經確認的版本；三條工作分支從同一個 main 版本建立。
2. 每位組員使用自己的 GitHub 帳號，在對應分支修改並提交自己的 commit。
3. 完成一小段工作就開 Pull Request，說明改動與驗證方式，經組員檢查後再合併 main。
4. BRIEF.md、VERIFY.md、TESTS.md 為共用文件：各職責更新對應段落，合併前檢查衝突並同步 main。VERIFY.md 寫預期行為，TESTS.md 區分測試案例與實際結果。
5. 分支名稱表示工作職責；建立分支本身不等於各組員已有個人開發紀錄。
