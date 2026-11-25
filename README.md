# 🎮 Kuso Game by Raymond

Raymond 的遊戲收藏｜每款遊戲只保留目前能確認的最新版本。

> 更新日期：2026-11-25。此 repository 為靜態遊戲入口與原始碼收藏。外部 Sites 的原始碼尚未匯入，外部網站的存取權與功能未重新測試。

## 遊戲清單

| 遊戲 | 最近確認更新／版本 | 類型 | 入口／匯入狀態及說明 |
|---|---|---|---|
| 三國方塊無雙（Three Kingdoms Voxel Warriors） | v2.1 | 3D 動作闖關／方塊建造 | [立即遊玩](https://chenkaie.github.io/minecraft-sanguo/) · [原始 Repo](https://github.com/chenkaie/minecraft-sanguo)；12 位武將、6 關 Boss、哥吉拉三段變身、三種難度、中英雙語、鍵鼠及觸控 |
| 方塊王國 2P（全 3D 創造模式） | 2026-11-23 | 沙盒建造 | 待取回原始碼 |
| 宇宙卡牌大亂鬥 | 2026-11-15 | 卡牌對戰 | [HTML 修正版](games/crossover-cards/index.html) |
| 畫線交鋒 | 2026-11-09 | 策略對戰 | 待確認原始網址及原始碼 |
| 星際遠征：銀河飛行員 | 2026-11-07 | 太空飛行 | [原始 Sites（v8）](https://starflight-castle-nov1.chenkaie.chatgpt.site) |
| 新手射擊訓練場 | 2026-11-07 | 射擊 | [原始 Sites（v10）](https://easy-target-arena-kent.chenkaie.chatgpt.site) |
| 水果貪吃蛇 | 2026-11-01 | 休閒 | [原始 Sites（v2）](https://fruit-snake-garden-kent-1101.chenkaie.chatgpt.site) |
| 光劍合成大戰 | 2026-10-31 | 動作格鬥 | [HTML 修復版](games/lightsaber-fusion/index.html) |
| 劍影對決｜火柴人競技場 | 2026-10-30 | 2D 劍術對戰 | [原始 Sites（v1）](https://stickman-sword-arena-kent.chenkaie.chatgpt.site)，不同於第一人稱光劍合成大戰 |
| 雙城爭霸：未來軍團 | 2026-10-18 | 城堡攻防 | [原始 Sites（v1）](https://castle-future-legion.chenkaie.chatgpt.site) |
| 士兵大對決 | 2026-09-15 | 3D 即時戰略 | [原始 Sites（v13）](https://soldier-clash-arena.chenkaie.chatgpt.site) |
| 霓虹跑酷：天際衝刺 | 2026-09-10 | 3D 跑酷 | [原始 Sites（v1）](https://neon-rooftop-runner.chenkaie.chatgpt.site) |
| 寵物／貓咪養成 | 2026-09-08 | 養成 | 寵物養成升級版，待取回原始碼 |
| 甲蟲對戰擂台 | 2026-09-06 | 競技 | 待取回原始碼 |
| 武士對戰遊戲 | 2026-09-06 | 2D 對戰 | 藍色武士對 AI；是否為劍影對決前身待核對 |
| 太空戰機 | 2026-09-06 | 太空射擊 | 是否為其他太空射擊遊戲前身待核對 |

此作品已由獨立 Repo 透過 GitHub Pages 發布，Dashboard 連至該 Repo 的最新正式遊戲入口，不複製歷史版本或遊戲本體，以維持單一原始碼來源。遊戲與方塊王國 2P 分別保留，尚無證據顯示為同一作品。版本及特色依 [原始 README](https://github.com/chenkaie/minecraft-sanguo/blob/main/README.md)。

`/67` 中的四個 HTML 是同一款第一人稱光劍合成大戰的迭代版本。2026-10-31 的 `光劍合成大戰_修復版.html` 已與本 repo 的 [games/lightsaber-fusion/index.html](games/lightsaber-fusion/index.html) 核對，內容相符；不重複提交前三個舊版。2026-11-01 的操作改善需求尚未取得可確認的新版原始碼。非遊戲 JPEG 不匯入公開 repository。

寵物／貓咪養成、甲蟲對戰擂台、武士對戰遊戲及太空戰機僅為可確認的製作對話紀錄，尚無可核對的原始碼或遊玩網址，不算作已移植遊戲。

## Sites 原始碼移植

已整理 8 款外部 Sites 的最新可取得版本、原始網址及畫面文字：[完整移植清單與驗收標準](docs/sites-migration.md)。其中新手射擊訓練場更新至 Sites v10。Library 目前只提供畫面文字擷取，不能匯出完整原始碼；直接下載網站亦未成功。這八款尚未完成移植。取得實際完整原始碼或靜態建置輸出後，才會改用本站遊戲入口。

## 長期維護原則

最終建議是將所有遊戲完整移植至 GitHub，讓每款遊戲都能獨立運作，不再依賴 ChatGPT Sites。這樣未來就能透過 Git 進行版本管理、功能更新及長期維護。

有新的遊戲版本時，優先取回實際原始碼、確認能獨立運作、更新同一個遊戲目錄及首頁，不另建重複的舊版入口。

## GitHub Pages

在 [Settings → Pages](https://github.com/chenkaie/kuso_game_by_raymond/settings/pages)，將 Source 設為 **Deploy from a branch**，Branch 選 **main / (root)**，儲存。

GitHub Pages 已由使用者設定；部署網址：https://chenkaie.github.io/kuso_game_by_raymond/

本網站不需要後端或編譯。可直接開啟根目錄 `index.html`，或使用 GitHub Pages。

## 版本管理

- 每款遊戲使用獨立的 `games/<slug>/index.html` 路徑。
- 目前有兩款取回的原始 HTML，以及一款已獨立維護的 GitHub Pages 遊戲（三國方塊無雙）；外部 Sites 文字備份不是完整遊戲原始碼。
- 外部 Sites 使用原始網站入口，待取得實際程式碼後再移入。
- 未確認原始網址或原始碼的遊戲保留清單項目，不建立假遊戲。
- 此次僅匯入原始 HTML，不修改遊戲內容，也不宣稱已完成瀏覽器遊玩測試。
