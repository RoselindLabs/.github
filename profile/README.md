# RoselindLabs

围绕 MaiBot，开发聊天插件、连接外部服务，并维护实际使用中的集成与兼容补丁。

*Plugins, integrations, and maintained forks for MaiBot.*

我们关注主动交流、阅读与内容理解，以及图像、语音等表达方式，让这些能力在同一套聊天系统中自然协作。

## 插件项目

| 项目 | 用途 |
| --- | --- |
| [Neko Proactive](https://github.com/RoselindLabs/neko-proactive-mai) | 主动聊天、单次预约与周期唤醒，交由 Planner 结合会话决定如何回应 |
| [Neko Web](https://github.com/RoselindLabs/neko-web) | 联网搜索、网页阅读与聊天图片分享 |
| [Neko Files](https://github.com/RoselindLabs/neko-files) | 按需读取授权聊天中的文档、指定压缩包成员及可选 OCR |
| [Neko Video](https://github.com/RoselindLabs/neko-video) | 视频内容理解、抖音图文阅读与选定媒体发送 |
| [Neko Draw](https://github.com/RoselindLabs/neko-draw) | 接入 OpenAI 兼容接口与 Gemini 的图像生成 |
| [Neko TTS](https://github.com/RoselindLabs/neko-tts) | 按回复选择语音表达，支持预置音色与音色克隆 |

## 维护中的 Fork

这些项目基于社区原作继续维护。原作者、许可证与上游历史保留，具体修改范围见各仓库说明。

| 项目 | 维护方向 | 上游 |
| --- | --- | --- |
| [MaiBot](https://github.com/RoselindLabs/MaiBot) | 宿主集成、会话与消息处理的定向补丁 | [Mai-with-u/MaiBot](https://github.com/Mai-with-u/MaiBot) |
| [SnowLuma Adapter](https://github.com/RoselindLabs/maibot-snowluma-adapter) | SnowLuma 协议适配、消息与回执处理 | [Mai-with-u/MaiBot-SnowLuma-Adapter](https://github.com/Mai-with-u/MaiBot-SnowLuma-Adapter) |
| [B站手记](https://github.com/RoselindLabs/bilibili_autopilot) | 自主浏览、阅读感想、历史关联与聊天分享 | [namchengwuqiu/bilibili_autopilot](https://github.com/namchengwuqiu/bilibili_autopilot) |
| [GIF 动图识别](https://github.com/RoselindLabs/maibot-read-gif) | 动图内容识别与入站处理兼容 | [fabiocsa/maibot-read-gif](https://github.com/fabiocsa/maibot-read-gif) |
| [Mai Gatekeeper](https://github.com/RoselindLabs/Mai_gatekeeper) | 好友申请审批、异常申请人工查看与用户屏蔽 | [octmicy/Mai_gatekeeper](https://github.com/octmicy/Mai_gatekeeper) |

## 从哪里开始

- **安装与配置**：查看目标仓库的 README，确认支持的 MaiBot / SDK 版本、依赖和所需权限。部分插件依赖维护版宿主提供的接口。
- **了解改动**：查看 CHANGELOG；维护 fork 的差异以仓库内的 `NEKO_FORK.md`、补丁说明或 README 为准。
- **反馈与贡献**：在对应仓库提交 Issue 或 Pull Request。报告问题时附版本、复现步骤和脱敏日志。
- **许可证与来源**：以各仓库的 LICENSE、NOTICE 和来源说明为准。

感谢 MaiBot 社区及所有上游项目的作者与贡献者。
