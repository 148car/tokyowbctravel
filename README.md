# 東京 WBC 應援旅遊助手（Gemini Canvas UI 風格）

已改成你提供的 UI 方向：

- 入口頁（深藍主題 + 應援感）
- 主頁 Header（WBC 風格標頭）
- 三分頁：行程 / 錢包 / 助手
- 行程時間軸卡片 + AI 應援攻略
- 聊天互動（可輸入訊息並收到 AI mock 回應）

## 啟動

```bash
python3 -m http.server 4173
```

開啟：<http://localhost:4173>

## 技術

- React 18 UMD
- Babel Standalone
- Tailwind CSS CDN
- LocalStorage（key: `tokyo-wbc-ui-v1`）

## 備註

目前 `apiKey` 預設為空字串，因此圖片生成功能會 fallback 到本地佔位視覺（⚾）。
