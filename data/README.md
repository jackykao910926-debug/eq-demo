# 實驗紀錄範本使用說明

`run-log-template.csv` 只有欄位，沒有量測結果。每列記錄一個運轉／量測工況，完整原始時間序列與 I–V 另存不可覆寫的檔案，使用欄位中的路徑建立連結。

## 如何識別一次實驗

`run_id` 是唯一量測編號；`independent_start_id` 用來區分真正獨立啟動與同一啟動內的多次掃描。`config_id`、`geometry_version`、`magnet_batch`、`magnetization_map` 使結果能追溯至實際磁座、幾何及磁材。

## 工況與參考平面

填入 MFC 校正編號和 sccm 的標準溫度／壓力，再換算質量流率。`pf_W` 與 `pr_W` 必須來自同一個已定義的射頻參考平面，`pnet_W = pf_W - pr_W` 不代表全部被電漿吸收。`system_power_W` 是另一個量，不與射頻淨功率混用。

`base_pressure_Torr` 是關氣底壓；`operating_background_pressure_Torr` 是運轉背景壓力。必須記錄真空計位置與氣體修正，不能用底壓冒充操作壓力。

## 探針與溫度

記錄探針座標、方向、面積與局部磁場。保留完整 I–V、上掃／下掃、掃描速率及各項原始檔路徑；無法確認收集模型有效時，不硬算密度。溫度欄位對應磁體、饋入與腔壁。`continuous_duration_min` 必須是真正不中斷的一段運作時間，不把多次重新點火時間相加。

## 推力與品質

只有直接推力量測、校正及誤差分析完成時，才填入推力結果；不能由照片亮度或單點密度代替。`quality_flag` 可使用 valid、invalid、pending；排除資料仍保留 `exclusion_reason`。分析腳本版本填在 `analysis_commit`。

## 公開範圍

原始資料與操作者身分是否可公開，先依研究團隊規範處理。本公開儲存庫目前只收錄範本及研究規劃；不包含博士論文全文、契約原檔、簽章、個人資料或未授權實验資料。
