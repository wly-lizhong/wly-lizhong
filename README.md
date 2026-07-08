# 你好，我是王露苑 👋

**医疗影像算法 × 大模型应用 × 工程落地** — Medical AI × LLM Applications × Deployment

- 🎓 成都东软学院 · 人工智能专业 · 2026 届（专业排名前 5%）
- 🏥 三年聚焦医疗 AI 一条主线：临床试验智能化（企业实习）→ 记忆辅助产品（落地服务 100+ 老人）→ 医疗影像与检测
- 🏆 国家级奖项 19 项 · EI 会议论文 2 篇 · 软件著作权 7 项
- 📫 联系我：**2014626566@qq.com**

## 简历项目 ↔ 代码仓对照

### 🏥 临床试验 AI 智能体平台（企业实习 · 简历主项目）

平台整体介绍见 [clinical-ai-agent-platform](https://github.com/wly-lizhong/clinical-ai-agent-platform)（公司项目代码不开源，该仓为架构图 + 职责说明）。**简历上的每个能力点，都有我写的可运行同类实现**：

| 简历上的能力 | 可运行代码 | 说明 |
|---|---|---|
| **自动打码脱敏**（正则+LLM 双通道，召回优先） | [pii-masking-pipeline](https://github.com/wly-lizhong/pii-masking-pipeline) | 中文敏感信息脱敏通用实现：双通道识别 + 区间合并 + P/R 评测 |
| **知识库问答**（1000+ 文档 RAG，引用溯源控幻觉） | [medical-rag](https://github.com/wly-lizhong/medical-rag) | 语料构建 → 向量索引 → 多租户检索问答全链路 |
| **智能客服**（意图识别 + 结构化输出保障机制） | [service-desk-agent](https://github.com/wly-lizhong/service-desk-agent) | 意图识别 + FAQ 检索 + JSON Schema 校验失败自动重试/降级 |
| **智能审核 / SDV 源数据核查** | [clinical-ai-agent-platform](https://github.com/wly-lizhong/clinical-ai-agent-platform) | 涉公司专家规则与业务流程，仅 Showcase 说明 |

### 🧓 忆望 · 记忆辅助软件（商用落地，服务 100+ 老人）

[yiwang-memory-assistant](https://github.com/wly-lizhong/yiwang-memory-assistant) — 医嘱文本 → 结构化服药计划 FastAPI 服务 + 视觉大模型药片计数（真代码，可直接跑）

### 🚀 模型部署

[onnx-deploy-playground](https://github.com/wly-lizhong/onnx-deploy-playground) — PyTorch → ONNX 导出 / 精度对齐 / 延迟基准 / PTQ 量化，README 所有数字均为实测

### 🎓 更多项目

| 仓库 | 一句话 |
|---|---|
| [heart-disease-decision-support](https://github.com/wly-lizhong/heart-disease-decision-support) | 知识图谱 + 检索 + LLM 的心脏病辅助决策应用（带界面截图） |
| [kaiwu-rl-target-dqn](https://github.com/wly-lizhong/kaiwu-rl-target-dqn) | 腾讯开悟强化学习竞赛 target-DQN，奖励函数三轮迭代设计 |

> 简历中的毛囊显微检测（TPH-YOLO）、无人机检测、语音等项目属企业/竞赛资产，无公开代码，面试时可展示架构与技术细节。

## 技能

| 方向 | 内容 |
|---|---|
| 深度学习 / CV | PyTorch · YOLO 系目标检测 · U-Net 分割 · 3D-CNN · OpenCV |
| 大模型应用 | RAG（LlamaIndex / LangChain）· Agent 工具调用 · QLoRA 微调 · Prompt 工程 · 多模态视觉模型应用 |
| 工程化 | Python · FastAPI · Docker · Git · MySQL / Redis 基础 |
| 模型部署 | ONNX 导出与精度对齐 · onnxruntime 推理 · PTQ 量化入门（TensorRT 系统学习中） |

## 我在找什么

2026 届校招 / 实习转正机会：**AI 应用工程师 / 算法工程师**（医疗 AI、大模型应用方向尤佳），坐标不限，即时到岗。
