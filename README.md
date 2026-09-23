# 你好，我是叶立恒 👋

**Agent 应用开发方向 · GitHub @yeliheng-010 · 诉说晚秋**

我在做基于 LangGraph 的 AI 应用，关注工作流编排、工具调用、上下文与检索，以及模型调用的可靠性。希望把从问题复现、代码修复到测试和部署的过程，沉淀为可运行的项目和可核验的开源贡献。

[个人博客](https://blog.miansu.eu.cc) · [技术文章](https://blog.miansu.eu.cc/archive/) · [我的开源 PR](https://github.com/pulls?q=is%3Apr+author%3Ayeliheng-010)

## 项目实践

| 项目 | 我在实践什么 | 技术栈 |
| --- | --- | --- |
| [AI Interview Studio](https://github.com/yeliheng-010/ai-interview-studio) | 把简历分析、面试规划、问题生成、修复与回答评价建模为显式工作流，结合结构化校验与业务数据持久化 | Python · FastAPI · LangGraph · PostgreSQL · Next.js |
| [CodeRag](https://github.com/yeliheng-010/CodeRag) | 面向代码仓库的 Agentic GraphRAG：混合检索、符号图扩展、调用路径工具，以及可追踪的执行过程和引用 | LangGraph · Tree-sitter · KuzuDB · Chroma · BM25 · React |

## 开源贡献

围绕真实问题提交补丁，并记录复现、测试、维护者反馈和后续修正。以下状态核查于 **2026-09-23**，四个 PR 均尚未合并；最新状态以链接中的上游记录为准。

| 项目 / PR | 贡献内容 | 当前进展 | 技术复盘 |
| --- | --- | --- | --- |
| [WeKnora #3548](https://github.com/Tencent/WeKnora/pull/3548) | 文档切片类型筛选，补齐 OCR / 图片描述的展示与重载状态 | 已响应维护者反馈，待后续审核 | [切片展示与状态一致性](https://blog.miansu.eu.cc/posts/weknora-chunk-type-filter/) |
| [WeKnora #3620](https://github.com/Tencent/WeKnora/pull/3620) | 补充 Docker Compose 下的 Swagger 访问与排障文档 | 待审核，远端扫描有失败项 | [HTTP 200 背后的服务路由](https://blog.miansu.eu.cc/posts/weknora-swagger-docker/) |
| [WeKnora #3624](https://github.com/Tencent/WeKnora/pull/3624) | 修复 GitLab 项目资源发现的分页遗漏，补充边界回归测试 | 扫描通过，待审核 | [201 个项目为何只返回 100 个](https://blog.miansu.eu.cc/posts/weknora-gitlab-pagination/) |
| [LightRAG #4057](https://github.com/HKUDS/LightRAG/pull/4057) | 正确传播 LoLLMs 普通、流式与向量调用的 HTTP 错误 | 已补修 CI 测试兼容问题，待复审及新 CI | [模型服务失败与 CI 补修](https://blog.miansu.eu.cc/posts/lightrag-lollms-http-errors/) |

贡献过程中使用 AI 辅助源码分析、实现和验证；具体改动、测试范围及协作过程见各 PR 与复盘文章。

## 持续学习

- **Agent 工作流**：显式状态、结构化输出、校验与修复循环。
- **工具与上下文**：MCP 工具契约、检索证据、符号图与引用追踪。
- **工程可靠性**：HTTP 错误、流式边界、分页完整性和回归测试。

欢迎通过项目 Issue 交流 Agent 应用与开源实践。
