# City Social

一個 IG / Messenger 風格的社交網站  
支援 Firebase 帳號系統、即時聊天（WebSocket）、PWA 與 APK 打包

## 功能
- Firebase 登入 / 註冊
- 貼文 / 多圖 / 按讚 / 留言
- 加好友 / 追蹤 / 封鎖
- 即時聊天室（Socket.IO）
- 日夜模式
- PWA（可安裝）
- Android APK（Capacitor）

## 技術
- HTML / CSS / JavaScript
- Firebase (Auth / Firestore / Storage)
- Socket.IO
- Capacitor

## 啟動
```bash
# 聊天伺服器
cd chat-server
npm install
node server.js
