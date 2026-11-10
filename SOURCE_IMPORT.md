# DoVideoAI 源码导入记录

- 上游项目：https://github.com/Xiaoc7r/DOVideo-AI
- 固定上游版本：421dcd2e70e5298ff4d719d2ac8cc4f7c063785b
- 导入日期：2026-11-10
- 当前学习仓库：https://github.com/JYHzz1/DoVideoAI
- 保留上游 MIT LICENSE、作者署名、原始 README 和代码。

本次完成源码克隆、静态核查和学习仓库同步，没有更改业务实现，也没有运行视频解析或调用付费模型。源码已有功能不代表本次导入者独立实现或完成运行验收。

当前上游已经从视频上传与总结扩展为 Video Agent：包含 RocketMQ 异步任务、分片续传、Redisson 任务锁、ASR/OCR 上下文、证据检索、AgentLoop、Checkpoint 与 SSE 阶段事件。具体环境要求、配置方法及上游能力说明见 README.md。当前后端要求 Java 21；请勿直接沿用其他项目的 Java 8/17 环境。

本地保留上游 Git 历史。GitHub 连接用于导入当前源码快照，远端初始提交历史与上游历史不同；后续二次开发应明确记录个人变更，不将上游架构包装成个人原创。
