# Important

OpenClaw 是一款本地优先、高权限、可自主执行系统操作的开源 AI 智能体，核心优势是能直接替你完成电脑操作

但也正因如此，**隐私与安全风险极高**

- 为维护网络安全与利益，**请保持高度警惕**


## Openclaw本质：



### Orchestrator（大脑层）

- 理解意图、拆解任务、规划执行步骤
- Invoke large models (GPT/Claude/local models) for execution
- 维护持久记忆（本地向量库），上下推理

### Gateway（协议桥）

- input bin ：HTTP、WebSocket、RPC、IM 机器人适配器
- 做权限校验、指令路由、日志记录，连接大脑与执行端
- Pipeline
