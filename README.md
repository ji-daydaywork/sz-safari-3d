# 深圳野生動物園 · 3D 互動導覽

低多邊形 3D 園區地圖，單一 HTML 檔（Three.js，無 build step）。

**線上版：** https://ji-daydaywork.github.io/sz-safari-3d/

## 功能

- 六大園區 3D 平台：入口廣場、猛獸谷、食草動物區、熊貓莊園、海洋天地、表演區
- 點擊平台／底部按鈕：鏡頭飛近＋右側攻略卡（貼士、價錢、表演時間）
- 動物模型：長頸鹿、大象、斑馬、老虎、熊貓、紅鶴
- 環園小火車（沿 Catmull-Rom 曲線行駛）、飛鳥、湖景、樹林
- 日夜切換、自動環繞、一鍵「一日路線」導覽
- 手機自適應（底部橫向卡片、bottom sheet）

## 資料來源

園區資訊綜合自官方公開資料、旅遊平台（Trip.com／KKday／Klook）及香港 KOL 實測影片（2026-02 至 2026-09）。

> 票價、表演時間會變動，出發前請以官方微信公眾號及購票平台為準。

## 本機預覽

```bash
cd ~/projects/sz-safari-3d
python3 -m http.server 8123
# http://localhost:8123
```
