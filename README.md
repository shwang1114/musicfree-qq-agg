# MusicFree QQ 聚合音源

解决 fusheng 订阅里 QQ 插件搜索列表为空的问题。

- **搜索**: 老接口 `client_search_cp`（腾讯废了 `DoSearchForQQMusicDesktop`，老接口仍活）
- **取链**: 轮询 `xunhuisi` → `cyapi` 双后端兜底（2026-08-29 实测唯二可用）

## 安装

MusicFree → 插件设置 → 从网络安装，粘贴：

```
https://raw.githubusercontent.com/shwang1114/musicfree-qq-agg/main/qq_agg.js
```

或订阅：`https://raw.githubusercontent.com/shwang1114/musicfree-qq-agg/main/plugins.json`

## 说明

- 第三方解析接口，可能随时失效，挂了请反馈。
