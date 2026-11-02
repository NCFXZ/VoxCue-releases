# VoxCue

简体中文 | [English](README.en.md)

本仓库分发 VoxCue 安装包、模型资源和自动更新文件。

VoxCue 是一款 Windows / macOS 桌面面试准备助手。围绕简历和职位描述整理资料、准备面试技能，通过实时语音转写、AI 回答与面试记录完成练习和复盘。

[使用指南](https://voxcue.com.cn/install/) · [下载与更新](https://github.com/NCFXZ/VoxCue-releases/releases) · [问题反馈](https://github.com/NCFXZ/VoxCue-releases/issues)

## 下载

| 平台 | 当前安装包 | 系统要求 |
| --- | --- | --- |
| Windows | [0.6.7 · x64 EXE](https://github.com/NCFXZ/VoxCue-releases/releases/download/v0.6.7/VoxCue-Setup-0.6.7-x64.exe) | Windows 10 / 11，64 位 |
| macOS | [0.6.6 · Apple Silicon DMG](https://github.com/NCFXZ/VoxCue-releases/releases/download/v0.6.6/VoxCue-0.6.6-arm64.dmg) | macOS 14.2 及以上，M 系列芯片 |

本次 0.6.7 为 Windows 发行；Mac 0.6.7 尚未发布。两端按各自完整的稳定发行检查更新。首次安装只需下载 EXE 或 DMG；其他更新文件由应用使用。

## 主要功能

- **面试准备**：添加简历、职位描述和附件，与 AI 讨论个人经历、项目和目标岗位；首页根据资料状态提供三个下一步操作。
- **技能生成与更新**：根据简历和 JD 整理面试知识与回答要点，逐项查看、选择并保存修改；参考知识与真实个人经历分开处理。
- **AI 服务**：在设置中独立连接 ChatGPT 或 GitHub Copilot。模型可按需要搜索网页；准备聊天默认不使用知识库，明确要求后才检索所选资料。
- **实时面试辅助**：分别转写系统音频和麦克风，在置顶浮窗中查看问题与回答，也可输入问题或截图提问。
- **面试记录**：查看转写、回答与截图，支持定位、重命名和导出，方便复盘。
- **个人资料与知识库**：管理个人信息和文档原件，按需使用本地检索；个人资料、面试记录和知识库可分别开启云备份。
- **中英界面**：简体中文与 English 可随时切换，支持浅色、深色及系统外观；聊天和面试回答支持 LaTeX 公式与矩阵。

## 0.6.7 更新

- 新增完整中英界面，首次按系统语言选择，之后保留手动设置。
- 简化首页引导，完善按钮悬停说明、英文排版与控件对齐。
- 改进技能生成、更新和逐项确认；资料完善后可继续生成相关面试技能。
- 网页搜索改为由模型按需使用；准备聊天仅在明确要求时使用知识库。
- 新增聊天与面试公式显示，优化技能详情、思考过程的展开收起动画及滚动体验。
- 修复多项界面、稳定性和安全问题。

[完整发布说明（中文 / English）](https://github.com/NCFXZ/VoxCue-releases/releases/tag/v0.6.7)

## 开始使用

1. 安装并打开 VoxCue。可注册 / 登录 VoxCue 账号，也可跳过登录使用本地模式。
2. 在「设置 → AI 服务」连接 ChatGPT 或 GitHub Copilot；在「本地组件」下载所需语音和检索组件。
3. 添加简历与职位描述，确认 AI 整理的资料，再按需要生成面试技能。
4. 开始面试前检查音频设备，在面试浮窗中使用转写、提问和回答功能。

VoxCue 免费提供；AI 服务的账号权限和用量由对应服务决定。云备份需要登录 VoxCue，本地模式仍可独立连接 AI 服务。详细操作见[使用指南](https://voxcue.com.cn/install/)。

## 安装与更新

Windows 下载 EXE 后运行安装程序。Mac 打开 DMG，将 VoxCue 拖入 Applications。语音与检索模型在应用设置中按需下载，升级复用已下载的同版本组件。

`.blockmap`、`latest.yml`、`latest-mac.yml` 和 Mac ZIP 用于自动更新，首次安装无需下载。验证码邮件未出现时，可检查垃圾邮件文件夹。

## 数据与隐私

语音识别在本机运行，不保存或上传原始音频。AI 请求会发送任务需要的文字、相关资料片段，以及主动提交的附件或截图。个人资料、面试记录和知识库的云备份分别由用户开启，默认总容量为 100 MB。

基础使用统计不包含聊天 / 转写正文、原始文件、音频、截图或访问令牌。具体功能和操作说明见[使用指南](https://voxcue.com.cn/install/)。
