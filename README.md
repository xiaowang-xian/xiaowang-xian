👨‍🎓 计算机专业在读学生 | 主攻云原生 + AI Agent 方向实践  
💻 核心技术栈：Golang 1.24、Kubernetes 1.32、Ollama（Qwen 2.5-7B）、Prometheus、MySQL、MCP协议、Argo CD、OpenEBS、SSE/JSON-RPC 2.0  

### 实践项目
#### 🛠️ K8s SRE 智能运维助手
- 目标：让K8s集群能**自动发现并修复故障**（Pod崩溃）
- 核心技术栈：Kubernetes、Prometheus（监控）、Ollama（AI决策）、Golang（核心代理）、Argo CD（GitOps部署）
- 简单实现：Prometheus监测到故障 → Go Agent收集Pod日志 → Ollama生成重启决策 → 调用K8s API自动修复，全程用Argo CD实现自动化部署

#### 📊 电信计费数据实时分析平台（Hadoop+MySQL）
- 目标：解决传统关系型数据库海量数据分析时效性瓶颈，支撑千万级用户计费数据的实时/离线分析
- 核心技术栈：Hadoop/HBase/Hive、MySQL 5.7（GTID主从）、OGG数据同步、Kubernetes、Shell自动化运维
- 简单实现：通过OGG无侵入同步源端计费数据至HBase存储 → Hive完成离线SQL分析 → 分析结果存入MySQL高可用集群供业务查询，全链路基于K8s部署+Shell脚本实现自动化监控
  
#### 🤖 MCP 企业级 AI 智能体平台
- 目标：让大模型安全访问企业内部数据库，实现「自然语言查HR数据」
- 核心技术栈：Golang、MCP协议、Kubernetes、Ollama（Qwen 2.5-7B）、MySQL、OpenEBS（存储）、SSE/JSON-RPC 2.0（通信）
- 简单实现：基于MCP协议解耦AI推理和数据库操作，用户提问后，AI自主生成并执行SQL，通过SSE异步返回结果，MySQL数据依托OpenEBS实现持久化

📚 还在持续学习云原生与AI Agent融合技术，欢迎交流学习心得～
