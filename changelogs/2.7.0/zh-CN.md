# SimpMusic 2.7.0 播放修复版

## 播放修复

- 将分支的 YouTube Music 登录播放修复移植到 2.7.0。提取音频流时保留登录状态，并在部分音质不可用时尝试其他可用音轨。
- 修复部分歌曲只有 AAC 音轨时被跳过的问题。流地址验证遇到临时限流时，仍允许播放器尝试播放。
- 当首选音轨不可用或播放器响应缺少歌曲详情时，继续尝试可用音轨。

## 2.7.0 更新

- 新增自定义电台和常听回顾，可按喜欢的内容创建电台，也能在媒体库重听最近常播的歌曲。
- 新增设置搜索、AMOLED 纯黑主题、可切换的 Android 应用图标，以及长标题滚动开关。
- 歌词页支持删除当前歌词、动态背景和低音律动，AI 设置新增服务商和可搜索的模型列表。
- 改进 AutoMix 淡入淡出、Android Auto 播放队列、本地歌单随机播放、重复歌曲删除和跨设备同步。
- 补齐新增功能的简体和繁体中文界面。

[上游完整更新说明](https://github.com/maxrave-dev/SimpMusic/releases/tag/v2.7.0)

## Android 安装包

下载 [SimpMusic-2.7.0-arm64-v8a.apk](https://github.com/LuoH-AN/SimpMusic/releases/download/v2.7.0/SimpMusic-2.7.0-arm64-v8a.apk)。这是 Android ARM64 Full 版，可覆盖安装到本分支的 2.6.0 播放修复版。
