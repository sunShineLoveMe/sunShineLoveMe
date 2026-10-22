<p align="center">
  <img src="./assets/chris-3d-banner.jpg" alt="Chris — AI Application Developer. 3D chrome and blue glass artwork. LLM, RAG, Agents and Voice." width="100%" />
</p>

# Chris · AI 应用开发者

把大模型接入具体业务，做出能操作、能验证的应用。从文档与知识检索、Agent 工作流，到语音交互和业务工作台，主要使用 **Python + TypeScript** 完成前后端开发与模型集成。

<p>
  <a href="#selected-projects">代表项目</a> ·
  <a href="#engineering">技术与工程</a> ·
  <a href="#more-work">更多作品</a>
</p>

<a id="selected-projects"></a>

## Selected Projects / 代表项目

<table>
<tr>
<td width="50%" valign="top">

### [电力 AI 标书系统](https://github.com/sunShineLoveMe/ai_bidding_power_grid)

从招标文件到可编辑标书：要求解析、企业知识检索、章节编写、响应检查与 Word 导出。

**企业文档智能应用**  
<sub>Python · Flask · React · PostgreSQL / pgvector</sub>

[功能与本地运行 →](https://github.com/sunShineLoveMe/ai_bidding_power_grid#readme)

</td>
<td width="50%" valign="top">

### [Local RAG × Dify](https://github.com/sunShineLoveMe/local-rag-bge3-chroma-dify)

将本地 PDF / Excel 转成可检索的知识片段，通过 API 接入 Dify 外部知识库。

**本地知识检索示例**  
<sub>Ollama · BGE-M3 · Chroma · FastAPI</sub>

[文档入库与接口接入 →](https://github.com/sunShineLoveMe/local-rag-bge3-chroma-dify#readme)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AnyLLM × LangGraph](https://github.com/sunShineLoveMe/anyllm-fullstack-langgraph-quickstart)

生成查询、搜索、反思信息缺口，再组织回答；在页面中观察 Agent 的执行过程。

**基于开源示例改造的研究工作流**  
<sub>LangGraph · OpenAI-compatible API · React</sub>

[工作流、搜索模式与启动 →](https://github.com/sunShineLoveMe/anyllm-fullstack-langgraph-quickstart#readme)

</td>
<td width="50%" valign="top">

### [Voicerly](https://github.com/sunShineLoveMe/Voicerly)

围绕参考音频和目标文本构建语音生成体验，提供参数控制、试听与下载。

**连接独立 VoxCPM 后端的语音应用**  
<sub>Next.js · TypeScript · Gradio Client · Supabase</sub>

[应用配置与服务依赖 →](https://github.com/sunShineLoveMe/Voicerly#readme)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [异构 AI 算力平台](https://github.com/sunShineLoveMe/heterogeneous-ai-compute)

演示多集群资源管理、调度评分、推理路由、告警与故障后的服务重建。

**固定数据基线的本地仿真演示**  
<sub>Next.js · TypeScript · ECharts · SSE · Vitest</sub>

[启动与完整演示路径 →](https://github.com/sunShineLoveMe/heterogeneous-ai-compute#readme)

</td>
<td width="50%" valign="top">

### [Argus AI · 订单分析](https://github.com/sunShineLoveMe/order-monitor-panel)

把订单、库存与异常分析放进同一个工作台，连接模型服务和 n8n 工作流。

**包含真实接口与演示数据的业务原型**  
<sub>Next.js · Supabase · n8n · Recharts</sub>

[实现范围与集成步骤 →](https://github.com/sunShineLoveMe/order-monitor-panel#readme)

</td>
</tr>
</table>

<a id="engineering"></a>

## 技术与工程

| 层次 | 常用技术与关注点 |
| --- | --- |
| 模型与知识 | OpenAI 兼容接口、Ollama、LangGraph、Embedding / Rerank、向量检索 |
| 应用开发 | Python、Flask / FastAPI、TypeScript、React / Next.js、音频与流式交互 |
| 数据与交付 | PostgreSQL / pgvector、Chroma、Supabase、Docker、n8n、测试与部署文档 |

我关心模型接入后的完整使用过程：材料怎么进来、结果如何核对、调用失败如何反馈，以及别人能否照着文档运行。各仓库 README 列出了配置、启动方式和当前实现范围。

<a id="more-work"></a>

## 更多作品与开源协作

- **交互与可视化**：[Three.js 全息标识](https://github.com/sunShineLoveMe/three.js-holographic-logo) · [声音传播演示](https://github.com/sunShineLoveMe/voice-experiment) · [WebAR](https://github.com/sunShineLoveMe/WebAR)
- **基于开源项目的改造**：[房间布局工具](https://github.com/sunShineLoveMe/floorplan-3d) · [纸上突围中文版](https://github.com/sunShineLoveMe/ballpoint-breach)
- **Fork 与贡献分支**：[VoxCPM 定制](https://github.com/sunShineLoveMe/VoxCPM-ZHIYUN) · [水利标书系统](https://github.com/sunShineLoveMe/ai_bidding_hubei) · [Jev 聊天助手](https://github.com/sunShineLoveMe/jev-chat-jarvis)
- **公司网站项目**：[上海栉云科技](https://github.com/sunShineLoveMe/zhiyun-tech-website)

欢迎通过相关项目的 **Issues** 交流使用问题、复现反馈与集成思路。开源改造项目的上游来源与修改范围见各仓库说明。
