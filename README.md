👨‍🎓 计算机专业在读学生 | 主攻云原生 + AI Agent 方向实践  
💻 核心技术栈：Golang 1.24、Kubernetes 1.32、Ollama（Qwen 2.5-7B）、Prometheus、MySQL、MCP协议、Argo CD、OpenEBS、SSE/JSON-RPC 2.0  

### 实践项目
#### 🛠️ K8s SRE 智能运维助手
- 目标：让K8s集群能**自动发现并修复故障**（Pod崩溃）
- 核心技术栈：Kubernetes、Prometheus（监控）、Ollama（AI决策）、Golang（核心代理）、Argo CD（GitOps部署）
- 简单实现：Prometheus监测到故障 → Go Agent收集Pod日志 → Ollama生成重启决策 → 调用K8s API自动修复，全程用Argo CD实现自动化部署

#### 🤖 MCP 企业级 AI 智能体平台
- 目标：让大模型安全访问企业内部数据库，实现「自然语言查HR数据」
- 核心技术栈：Golang、MCP协议、Kubernetes、Ollama（Qwen 2.5-7B）、MySQL、OpenEBS（存储）、SSE/JSON-RPC 2.0（通信）
- 简单实现：基于MCP协议解耦AI推理和数据库操作，用户提问后，AI自主生成并执行SQL，通过SSE异步返回结果，MySQL数据依托OpenEBS实现持久化

📚 还在持续学习云原生与AI Agent融合技术，欢迎交流学习心得～
