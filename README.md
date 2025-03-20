# 精选 (MCP) 服务端和客户端列表 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![MCP Clients](https://img.shields.io/badge/MCP客户端-Click-orange)](mcp-clients.md)
[![MCP Servers](https://img.shields.io/badge/MCP服务端-Click-yellow)](mcp-servers.md)
[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://discord.gg/e7sXgrSP)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)

[精选 (MCP) 服务端列表](mcp-servers.md)

[精选 (MCP) 客户端列表](mcp-clients.md)

- [什么是 MCP？](#什么是MCP？)
- [教程](#教程)
- [社区](#社区)
- [说明](#说明)
- [框架](#框架)
- [实用工具](#实用工具)
- [工具与实用程序](#工具与实用程序)
- [提示和技巧](#提示和技巧)
- [收藏历史](#收藏历史)

## 什么是 MCP？

[Model Context Protocol（MCP）](https://modelcontextprotocol.io/) 是一种开放协议，通过标准化的服务器实现，允许 AI 应用（MCP 客户端）通过标准化的协议与各种数据源进行交互。仓库旨旨在展示可用于生产和实验性的 MCP 服务器，这些服务器通过文件访问、数据库连接、API 集成和其他上下文服务来扩展 AI 功能。

## 教程

- [快速开始【官方】](https://modelcontextprotocol.io/quickstart/client)
- [Model Context Protocol (MCP) 快速开始【glama.ai】](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)
- [设置 Claude 桌面应用程序以使用 SQLite 数据库【youtube】](https://youtu.be/wxCCzo9dGj0)

## 社区

- [Github 讨论](https://github.com/orgs/modelcontextprotocol/discussions)
- [r/mcp Reddit](https://www.reddit.com/r/mcp)
- [Discord 服务](https://discord.gg/e7sXgrSP)

## 说明

- 🎖️ –  官方实现
- 编程语言
  - 🐍 – Python 代码库
  - 📇 – TypeScript 代码库
  - 🏎️ – Go 代码库
  - 🦀 – Rust 代码库
  - #️⃣ - C# 代码库
  - ☕ - Java 代码库
- 范围
  - ☁️ - 云服务
  - 🏠 - 本地服务
- 操作系统
  - 🍎 – For macOS
  - 🪟 – For Windows

> [!NOTE]
> 关于本地 🏠 和云 ☁️ 的区别：
>
> - 当 MCP 服务器与本地安装的软件通信时使用本地服务，例如控制 Chrome 浏览器。
> - 当 MCP 服务器与远程 API 通信时使用网络服务，例如天气 API。

## 框架

- [FastMCP](https://github.com/jlowin/fastmcp) 🐍 - 用于在 Python 中构建 MCP 服务器的高级框架
- [FastMCP](https://github.com/punkpeye/fastmcp) 📇 - 用于在 TypeScript 中构建 MCP 服务器的高级框架
- [Foxy Contexts](https://github.com/strowk/foxy-contexts) 🏎️ - 用于以声明方式编写 MCP 服务器的 Golang 库，包含功能测试
- [Genkit MCP](https://github.com/firebase/genkit/tree/main/js/plugins/mcp) 📇 –  提供[Genkit](https://github.com/firebase/genkit/tree/main)与模型上下文协议（MCP）之间的集成。
- [LiteMCP](https://github.com/wong2/litemcp) ⚡️ - 用于在 JavaScript/TypeScript 中构建 MCP 服务器的高级框架
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) 🏎️ - 用于构建 MCP 服务器和客户端的 Golang SDK。
- [mcp-framework](https://github.com/QuantGeekDev/mcp-framework) - ⚡️ 用于构建 MCP 服务器的快速而优雅的 TypeScript 框架
- [mcp-proxy](https://github.com/punkpeye/mcp-proxy) 📇 - 用于使用 `stdio` 传输的 MCP 服务器的 TypeScript SSE 代理
- [mcp-rs-template](https://github.com/linux-china/mcp-rs-template) 🦀 - Rust 的 MCP CLI 服务器模板
- [metoro-io/mcp-golang](https://github.com/metoro-io/mcp-golang) 🏎️ - 用于构建 MCP 服务器的 Golang 框架，专注于类型安全。
- [rectalogic/langchain-mcp](https://github.com/rectalogic/langchain-mcp) 🐍 - 提供 LangChain 中 MCP 工具调用支持，允许将 MCP 工具集成到 LangChain 工作流中。
- [salty-flower/ModelContextProtocol.NET](https://github.com/salty-flower/ModelContextProtocol.NET) #️⃣🏠 - 基于 .NET 9 的 C# MCP 服务器 SDK ，支持 NativeAOT ⚡ 🔌
- [spring-ai-mcp](https://github.com/spring-projects-experimental/spring-ai-mcp) ☕ 🌱 - 用于构建 MCP 客户端和服务器的 Java SDK 和 Spring Framework 集成，支持多种可插拔的传输选项
- [@marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) - CodeMirror 扩展，实现了用于资源提及和提示命令的模型上下文协议 (MCP)

## 实用工具

- [boilingdata/mcp-server-and-gw](https://github.com/boilingdata/mcp-server-and-gw) 📇 - 带有示例服务器和 MCP 客户端的 MCP stdio 到 HTTP SSE 传输网关
- [isaacwasserman/mcp-langchain-ts-client](https://github.com/isaacwasserman/mcp-langchain-ts-client) 📇 - 在 LangChain.js 中使用 MCP 提供的工具
- [lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway) 📇 - MCP SSE 服务器的网关演示
- [mark3labs/mcphost](https://github.com/mark3labs/mcphost) 🏎️ - 一个 CLI 主机应用程序，使大型语言模型 (LLM) 能够通过模型上下文协议 (MCP) 与外部工具交互
- [MCP-Connect](https://github.com/EvalsOne/MCP-Connect) 📇 - 一个小工具，使基于云的 AI 服务能够通过 HTTP/HTTPS 请求访问本地的基于 Stdio 的 MCP 服务器
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) 🐍 - OpenAI 中间件代理，用于在任何现有的 OpenAI 兼容客户端中使用 MCP
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) 🐍 - MCP stdio 到 SSE 的传输网关
- [upsonic/gpt-computer-assistant](https://github.com/Upsonic/gpt-computer-assistant) 🐍 - 用于构建垂直 AI 代理的框架

## 工具与实用程序

> 用于管理、配置和使用 MCP 服务器的工具。这些实用程序简化了安装过程，提升了用户体验。

### 服务器管理器

- [mcp-get](https://github.com/michaellatman/mcp-get) - 用于安装和管理 MCP 服务器的命令行工具。简化了为 Claude Desktop 安装和配置服务器的过程。
  - 支持基于 NPM 的服务器
  - 自动生成配置
  - 简便的服务器管理
- [Remote MCP](https://github.com/ssut/Remote-MCP) - 远程 MCP 通信的解决方案，可实现模型上下文的集中化管理

## 提示和技巧

### 官方提示词关于 LLM 如何使用 MCP

如何让 Claude 回答有关模型上下文协议（MCP）的问题？

创建一个项目，然后将此文件添加到其中：

https://modelcontextprotocol.io/llms-full.txt

这样 Claude 就能回答关于编写 MCP 服务器及其工作原理的问题了

- https://www.reddit.com/r/ClaudeAI/comments/1h3g01r/want_to_ask_claude_about_model_context_protocol/

## 收藏历史

<a href="https://star-history.com/#xlxxcc/awesome-mcp&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=xlxxcc/awesome-mcp&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=xlxxcc/awesome-mcp&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=xlxxcc/awesome-mcp&type=Date" />
 </picture>
</a>
