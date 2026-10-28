# Foigent

[English](https://github.com/foigent)

我们构建开源工具，帮助团队管理 AI 访问、了解用量和费用，并调查实际发生了什么。

## 产品

| 项目 | 用途 | 当前状态 |
| --- | --- | --- |
| [UniRouter](https://github.com/foigent/unirouter) | 模型接入、路由、策略、用量与计费，并提供可检查的执行回执。 | 源码已公开 |
| [X-Insight](https://github.com/foigent/x-insight) | 将获授权的执行与工作事实关联到调查和复核流程。 | 源码已公开 |

UniRouter 处理模型请求，记录用量与计费事实；X-Insight 异步接收获授权的事实。
两个产品可以独立使用，X-Insight 不进入同步模型请求的关键路径。

## 公共组件

- [Event & Connector Specification](https://github.com/foigent/event-connector-spec)：
  交换可检查事实所需的共享合同与跨语言测试。
- [Integration Control](https://github.com/foigent/integration-control)：
  在产品执行相应操作前，验证离线授权制品。

## 开始使用与参与贡献

从 [UniRouter 入门指南](https://github.com/foigent/unirouter/blob/main/docs/community/getting-started.md)开始。
支持的安装方式与可用下载见[安装和发布状态](https://github.com/foigent/unirouter/blob/main/docs/community/release-readiness.md)。

欢迎贡献文档、可复现的问题报告、测试和代码。各仓库提供自己的贡献指南与安全报告说明。
UniRouter 使用问题可在 [Discussions](https://github.com/foigent/unirouter/discussions) 中交流。

英文是文档和社区交流的第一语言，也欢迎中文翻译、提问和贡献。本文为中文版本，以英文首页为准。

公开项目中归本项目所有的材料采用 Apache-2.0；第三方组件保留各自的许可证与声明。
