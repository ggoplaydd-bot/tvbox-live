# 电视直播纯净源 (央视频道 + 各省卫视)

基于 TVBox 开源格式整理，已彻底剔除所有带货、健康养生等内置广告频道，按 CCTV-1 ~ 17 标准顺序重排并合并多源线路。

## 订阅地址

- **国内高速 CDN 直播源 (直接填入 TVBox 直播地址)**：
  `https://cdn.jsdelivr.net/gh/ggoplaydd-bot/tvbox-live@main/live.txt`

- **GitHub Raw 原地址**：
  `https://raw.githubusercontent.com/ggoplaydd-bot/tvbox-live/main/live.txt`

- **完整配置接口 (填入 TVBox 配置地址)**：
  `https://cdn.jsdelivr.net/gh/ggoplaydd-bot/tvbox-live@main/config.json`

## 如何维护更新
直接在 GitHub 上编辑 `live.txt`，保存后所有使用此订阅的电视盒子会在下一次进入时自动同步最新直播流，无需重新打包或重装 APK。
