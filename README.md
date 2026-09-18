# FriesArrangement - 籃具工件最佳擺放 3D 展示

直接雙擊 `index.html` 即可離線開啟（已內建 Three.js，無需 http 伺服器）。

- 籃具長寬高可選清單、自由擴充（localStorage）
- 工件長寬高 150×100×50 mm，不堆疊，最小間隔 5mm
- 自動計算最大數量（自由?放 `floor((L+gap)/(p+gap))`）並自動擇優 90° 旋轉
- FRIES 2026 型錄支援：variogrid/techtray 9mm / tech-rack 15mm Raster + 3mm 隔板取整對比
- 3D 拖曳旋轉 / 滾輪縮放 / 右鍵平移，顯示最佳擺法 `nx × ny = N`

線上預覽：啟用 GitHub Pages (`Settings → Pages → Deploy from branch → main / root`) 後 `https://sysheng17.github.io/FriesArrangement/`

參考：[FRIES 2026 Werkstucktrager Prospekt PDF](https://www.fries-kt.com/wp-content/uploads/2026_DE_FRIES-Werkstuecktraeger_Prospekt_web.pdf) p.6-10 / p.22-23 / p.74
