# unwall-app
打破限制，GitHub加速，B站/网易云一键直链，悬浮窗看进度。

# 星光拆墙 (Unwall)

[![Android](https://img.shields.io/badge/Android-5.0%2B-brightgreen)](https://developer.android.com)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)

**星光拆墙** 是一款 Android 下载辅助工具，专为解决国内访问 GitHub 慢、B站视频和网易云音乐下载繁琐等问题而生。  
它整合了多种解析服务，让你在一个 App 内完成**链接输入→解析→下载→文件管理**全流程。

## ✨ 主要功能

- 🚀 **GitHub 加速下载**：自动通过代理加速 GitHub 文件，无需手动找镜像。
- 🎬 **B站视频解析**：支持 `bilibili.com/video/` 和 `b23.tv` 短链接，一键获取 MP4 下载。
- 🎵 **网易云音乐解析**：支持歌曲链接，获取 MP3 下载。
- 🎵 **网易云音乐MV解析**:支持歌曲MV链接，获取 MP4 下载。
- 🌐 **有道翻译解析**:支持输入前缀`翻译:`或`Translate:`，处理后返回翻译结果。
- 
- 📁 **自定义下载路径**：Android 10+ 使用 SAF 选择文件夹，旧版自动适配存储权限。
- 🧊 **悬浮窗进度显示**：下载时悬浮窗展开气泡，实时显示文件名和百分比（1.1 版本新增）。
- 🔧 **MT 管理器联动**：下载完成后可直接用 MT 管理器打开文件，支持普通版/共存版切换。
- 🛡️ **权限一站式管理**：存储、所有文件访问、安装未知应用、悬浮窗权限快捷跳转。
- 📝 **本地日志记录**：下载异常自动写入日志，便于反馈问题。

## 🛠️ 使用说明

1. **下载安装**：从 [Releases](https://github.com/Gascy37/unwall-app/releases) 下载 APK 并安装。
2. **授予权限**：首次打开按提示授予存储/悬浮窗等权限（在“设置”页可查看状态）。
3. **开始下载**：
   - 功能请看上个板块主要功能。
4. **查看进度**：下载时悬浮窗会展开显示进度，点击可收缩。
5. **打开文件**：下载完成后点击“用MT管理器打开”即可。

## ⚙️ 技术栈

- 语言：Java
- 网络：`HttpURLConnection` + 公共代理 / 解析 API
- 存储：SAF（`DocumentFile`）+ FileProvider
- UI：Material Design + Fragment + Navigation
- 日志：本地文件滚动记录

## ⚠️ 注意事项

- 本软件仅供个人学习交流，请勿用于商业或侵权用途。
- 解析服务由第三方提供，稳定性无法保证，请理性使用。

## 🤝 贡献

欢迎提交 Issue 或 Pull Request。  

## 📧 联系作者

- 后室の星彩_：B站 [@后室の星彩_](https://space.bilibili.com/3546555082606623)
- ctnBobong32：B站 [@ctnBobong32](https://space.bilibili.com/1568237889)

---

**如果觉得有用，记得给个 ⭐ 支持一下～**
