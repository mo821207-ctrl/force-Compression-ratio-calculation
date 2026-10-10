# Force 155 壓縮比與 Squish 計算器 V3

完整繁體中文 PWA，可離線使用。

## 功能
- 排氣量與靜態壓縮比
- 缸墊容積、活塞突出量修正
- Squish 間隙與提示狀態
- 深色／淺色模式
- 自動保存輸入值
- PWA 離線安裝

## Squish 公式
`Squish = 缸墊厚度 - 活塞突出量 + 缸頭 Squish 深度`

> 狀態文字僅供提醒，不代表安全保證。實際組裝應進行物理量測及間隙檢查。

## 本機執行
解壓縮後進入專案資料夾：

```bash
python3 -m http.server 8080
```

瀏覽器開啟 `http://localhost:8080`。Service Worker 需要 localhost 或 HTTPS。

## 部署
把全部檔案原樣上傳到支援 HTTPS 的靜態網站空間即可。


## V4 iPhone 介面
- iPhone 安全區域適配
- 底部原生風格導覽列
- 觸控尺寸與 16px 輸入框
- Safari 加入主畫面提示
- 180x180 Apple Touch Icon
