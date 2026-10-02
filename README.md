# AstrBot · 冯昭月

> 基于 [AstrBot](https://github.com/AstrBotDevs/AstrBot) 框架构建的个人智能聊天机器人。

## 项目简介

**冯昭月** 是一个运行在 AstrBot 框架之上的 LLM 聊天机器人实例，具备自然语言对话、多平台消息接入与人格化回复能力。本仓库用于记录机器人的配置方案、人格设定与部署说明，并作为项目的对外展示主页。

## 功能特性

- 多平台接入：支持 QQ（NapCat / aiocqhttp）、微信公众号、Telegram 等消息平台
- 大模型对话：接入主流 LLM 服务，支持上下文多轮对话
- 人格化设定：通过 system prompt 定制「冯昭月」的说话风格与人设
- 插件扩展：兼容 AstrBot 插件生态，可按需扩展功能
- WebUI 管理：通过 AstrBot 可视化面板进行配置与监控

## 技术栈

| 组件 | 说明 |
| --- | --- |
| 框架 | AstrBot（Python） |
| 消息协议 | OneBot v11 / aiocqhttp |
| 模型服务 | OpenAI 兼容 API |
| 部署方式 | Docker / 本地 Python 环境 |

## 快速开始

```bash
# 克隆 AstrBot 框架
git clone https://github.com/AstrBotDevs/AstrBot.git
cd AstrBot

# 安装依赖
pip install -r requirements.txt

# 启动
python main.py
```

启动后访问 WebUI（默认 `http://localhost:6185`），在面板中配置模型服务与消息平台即可。

## 目录规划

```
AstrBot/
├── README.md        # 项目说明（本文件）
├── config/          # 人格与配置文件（规划中）
└── docs/            # 部署与运维文档（规划中）
```

## 说明

本项目仅用于个人学习与研究，基于开源项目 AstrBot 构建，遵循其开源协议。机器人「冯昭月」的言行不代表任何组织立场。

## License

MIT
