# 熱點雷達資料檔

熱點雷達 App 的「門牌包」放在這裡的 Release，App 在設定 → 關於可以直接下載，裝過的人開 App 時也會自動檢查有沒有新版。

## 門牌包（addr-pack.zip）

全台門牌位置（車機模式的單雙號、找門牌用）、全台路名與限速、快速道路。

資料來源：

- 各縣市政府在政府資料開放平臺公開的門牌坐標資料（政府資料開放授權條款第 1 版）
- 基隆市、宜蘭縣、南投縣、嘉義市、連江縣：政府門牌資料，經 [monkey1wizard/taiwan-address-data](https://github.com/monkey1wizard/taiwan-address-data) 整理（宜蘭、南投、嘉義市、連江是 2016 年的資料）
- 路名、限速、快速道路，以及部分門牌：© OpenStreetMap contributors（[ODbL](https://opendatacommons.org/licenses/odbl/)）

`meta.json` 是門牌包的版本資訊（`built` 是打包時間），App 用它判斷要不要更新。
