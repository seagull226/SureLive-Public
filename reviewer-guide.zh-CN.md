# SureLive 审核说明

版本：0.1.6。单一用途：通过视频字幕、定位复读、查词收藏和学习卡片导出辅助英语学习。

## 操作步骤

1. 安装提交包，点击 SureLive 图标，检查入口及设置。核心学习无需注册账号或自建服务器。
2. 打开有可用字幕的 YouTube、哔哩哔哩或百度网盘视频，选择字幕，点击一句字幕定位播放并复读。
3. 进入本地影院，选择 Edge 可播放的视频及 SRT、VTT 或 ASS 字幕，检查播放、声音、字幕、拖动、倍速和全屏。
4. 点击词语查词并收藏，重新打开收藏查看保存结果。
5. 从导出入口生成 Anki APKG 卡包。附带媒体取决于来源可用性、浏览器权限与录制条件。

在线参考页面：https://www.youtube.com/watch?v=aP9fXhqI6vI 。视频及字幕可用性可能变化；也可选用其他有字幕的视频。本地步骤使用审核人员有权使用的媒体文件。

## 权限用途

| 权限 | 用途 |
| --- | --- |
| tabs、activeTab | 识别视频标签页，执行用户主动的页面及截图操作 |
| storage、unlimitedStorage | 保存设置、收藏和含音视频的本地历史，减少存储配额及回收对记录的影响 |
| contextMenus、sidePanel | 提供右键字幕操作及浏览器原生侧栏 |
| tabCapture、offscreen | 用户主动的音频录制、媒体处理及导出 |
| declarativeNetRequestWithHostAccess、bilivideo.com | 为扩展自身的哔哩哔哩媒体请求设置必要请求头 |
| 全站、多框架内容脚本 | 检测网页及嵌入播放器的视频和字幕，显示学习界面；已验证平台不等于完整访问范围 |

查词、翻译及用户配置的 AI 服务会联网发送相关文本；使用自定义 AI 时需自行配置服务凭据。本地媒体兼容性取决于 Edge 原生编码支持。

[隐私政策](privacy-policy.zh-CN.md) · [第三方声明](THIRD_PARTY_NOTICES.DRAFT.md) · [English](reviewer-guide.en.md)
