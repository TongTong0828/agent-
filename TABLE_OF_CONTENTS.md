# RAG Agent 面试八股文目录

正文入口：[README.md](README.md)  
PDF 文件：[rag_agent_interview_guide.pdf](rag_agent_interview_guide.pdf)

## 阅读路径

这份资料可以按三种方式阅读：

- 快速面试准备：先看第 1-2 节、第 24-28 节、第 31-32 节。
- 技术体系学习：按第 3-23 节顺序阅读，建立完整 RAG Agent 工程知识框架。
- 系统设计准备：重点看第 24-27 节，练习技术点深挖、系统设计和追问链路。

## 完整目录

1. RAG 到底解决什么问题？
2. 一句话讲清楚 RAG 项目
3. Chunk 为什么重要？
4. Embedding 和向量数据库怎么讲？
5. Dense Retrieval、Sparse Retrieval 和 Hybrid Retrieval
6. RRF 是什么？
7. Rerank 为什么必要？
8. Query Rewrite 和 HyDE 怎么讲？
9. Agentic RAG 和普通 RAG 的区别
10. Memory 在 RAG 里怎么用？
11. 为什么要做拒答？
12. Citation Validation 为什么重要？
13. 多模态 RAG 怎么讲？
14. RAG 评测应该怎么做？
15. Golden Set 怎么设计？
16. 如何判断一次 RAG 优化是否有效？
17. Agent 工程化应该关注什么？
18. Agent Tool 封装怎么讲？
19. Skill、Tool、Subagent 有什么区别？
20. Agent Runtime 和 Middleware 怎么讲？
21. Agent 工作台和产品闭环怎么讲？
22. 从 RAG 到 Agent 答复应该怎么评测？
23. 生产化 RAG/Agent 要考虑什么？

## 详细拆解章节

24. 核心技术点详细拆解

- 24.1 Chunk 设计
- 24.2 Hybrid Retrieval
- 24.3 RRF 融合
- 24.4 Rerank 精排
- 24.5 Query Rewrite 和 HyDE
- 24.6 Abstain 拒答
- 24.7 Citation Validation
- 24.8 多模态 RAG
- 24.9 RAG Eval

25. Agent 工程详细拆解

- 25.1 Tool 设计范式
- 25.2 Skill 为什么不是更长的 Prompt
- 25.3 Subagent 怎么拆职责
- 25.4 Tool Routing 怎么做
- 25.5 Runtime / Gateway / Workspace 的边界
- 25.6 Middleware 为什么比 Prompt 可靠

26. 系统设计题详解

- 26.1 设计一个企业知识库 RAG
- 26.2 设计一个论文阅读 Agent
- 26.3 设计一个多文档报告生成 Agent
- 26.4 设计 RAG 评测体系
- 26.5 设计 Agent 权限和审计系统

27. 面试追问链路

- 27.1 从“为什么用向量库”追到完整检索链路
- 27.2 从“为什么做 chunk”追到证据质量
- 27.3 从“为什么 Agentic”追到可控 Agent
- 27.4 从“为什么需要 tool”追到 Agent 平台工程
- 27.5 从“如何防幻觉”追到引用和拒答
- 27.6 从“怎么上线”追到生产化边界

## 复习与表达章节

28. 高频面试问答 70 题

- 1-18：RAG 基础、检索、评测、debug
- 19-22：Agentic RAG、多轮对话、memory
- 23-25：多模态、图表、表格
- 26-38：prompt、安全、权限、成本、fallback、评测
- 39-50：知识图谱、workflow、简历表达、项目亮点和不足
- 51-70：tool、skill、subagent、runtime、gateway、工作台、端到端评测

29. 简历表达模板
30. 面试避坑回答
31. 自测清单
32. 最后总结

## 推荐复习顺序

1. 先读第 1-2 节，准备 30 秒和 3 分钟项目表达。
2. 再读第 3-16 节，补齐 RAG 基础链路。
3. 再读第 17-23 节，补齐 Agent 工程和生产化视角。
4. 重点读第 24-27 节，练习面试官深挖。
5. 最后用第 28-32 节做快速复盘和自测。
