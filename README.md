# VoxCue

VoxCue 是一款 Windows / macOS 桌面面试准备应用，支持准备聊天、个人资料、本地知识库、语音转写和面试记录。本仓库用于分发安装包、模型资源及自动更新文件。

## 主要功能

- **ChatGPT 登录与聊天**：通过浏览器完成授权，使用账户可用的模型，按需选择思考强度。
- **面试准备**：围绕简历、职位描述和附件进行准备聊天，支持将文件拖入聊天区域，聊天、草稿和附件保存在本机。
- **个人资料与知识库**：整理个人信息，导入文档并进行本地检索，为回答提供相关资料。
- **实时面试辅助**：转写系统音频和麦克风内容，在面试浮窗中查看问题与回答，并调整面试正文字号。
- **面试记录**：查看和导出面试记录，便于后续复盘。
- **本地组件管理**：在「设置 → 本地组件」下载和管理语音、知识库模型，后续启动复用已下载的缓存。

## 获取安装包

打开 [Releases 发行页面](https://github.com/NCFXZ/VoxCue-releases/releases)，选择包含所需平台安装包的发行，再展开 **Assets**。也可以先查看 [最新发行](https://github.com/NCFXZ/VoxCue-releases/releases/latest)。

| 平台 | 应下载的文件 |
| --- | --- |
| Windows x64 | 名称为 `VoxCue-Setup-…-x64.exe` 的安装程序 |
| macOS Apple Silicon（M 系列） | 名称为 `VoxCue-…-arm64.dmg` 的安装镜像 |

Windows 下载后运行安装程序；Mac 打开 DMG 后，将 VoxCue 拖入 Applications。

`.blockmap`、`latest.yml`、`latest-mac.yml` 和 Mac ZIP 文件供应用自动更新使用，首次安装无需下载。
