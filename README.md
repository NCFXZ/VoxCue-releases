# VoxCue

VoxCue 是一款 Windows / macOS 桌面面试准备应用，支持准备聊天、个人资料、本地知识库、语音转写和面试记录。本仓库用于分发安装包、模型资源及自动更新文件。

## 主要功能

- **账号与AI服务**：使用邮箱主账号注册、登录及找回密码，在设置中独立连接 ChatGPT 或 GitHub Copilot。
- **面试准备**：围绕简历、职位描述和附件进行准备聊天，支持将文件拖入聊天区域，聊天、草稿和附件保存在本机。
- **个人资料与知识库**：整理个人信息，导入文档并进行本地检索，为回答提供相关资料。
- **云同步**：个人资料、面试记录和知识库可分别开启同步，支持暂停、恢复及删除云端副本；标准总容量100 MB，个人资料可优先超额同步。
- **实时面试辅助**：转写系统音频和麦克风内容，在面试浮窗中查看问题与回答，支持输入问题与截图提问，并保存本次面试记录。
- **面试记录**：查看和导出面试记录，便于后续复盘。
- **本地组件管理**：在「设置 → 本地组件」下载和管理语音、知识库模型，后续启动复用已下载的缓存。

## 获取安装包

当前 Windows 版本为 [VoxCue 0.6.6（Latest）](https://github.com/NCFXZ/VoxCue-releases/releases/tag/v0.6.6)，Mac 版本为 [VoxCue 0.6.5](https://github.com/NCFXZ/VoxCue-releases/releases/tag/v0.6.5)。

| 平台 | 下载 |
| --- | --- |
| Windows x64 | [VoxCue-Setup-0.6.6-x64.exe](https://github.com/NCFXZ/VoxCue-releases/releases/download/v0.6.6/VoxCue-Setup-0.6.6-x64.exe) |
| macOS Apple Silicon（M 系列） | [VoxCue-0.6.5-arm64.dmg](https://github.com/NCFXZ/VoxCue-releases/releases/download/v0.6.5/VoxCue-0.6.5-arm64.dmg) |

Windows下载后运行安装程序。Mac支持Apple Silicon/macOS 14.2及以上，打开DMG后将VoxCue拖入Applications。Windows 与 Mac 按各自完整发行文件检查更新；旧发行和模型资源保留。

`.blockmap`、`latest.yml`、`latest-mac.yml` 和 Mac ZIP 文件供应用自动更新使用，首次安装无需下载。验证码邮件未在收件箱出现时，请同时检查垃圾邮件。
