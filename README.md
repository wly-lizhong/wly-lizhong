# 你好，我是王露苑 👋

**医疗影像算法 × 大模型应用 × 工程落地** — Medical AI × LLM Applications × Deployment

- 🎓 成都东软学院 · 人工智能专业 · 2026 届（专业排名前 5%）
- 🏥 三年聚焦医疗 AI 一条主线：临床试验智能化（企业实习）→ 记忆辅助产品（落地服务 100+ 老人）→ 医疗影像与检测
- 🏆 国家级奖项 19 项 · EI 会议论文 2 篇 · 软件著作权 7 项 · 华为云开发者认证
- 📫 联系我：**2014626566@qq.com**

---

## 🖼️ 项目实拍 · 一眼看到我做的东西

### 系统架构

<table>
<tr>
<td align="center" width="50%">
<a href="https://github.com/wly-lizhong/clinical-ai-agent-platform"><img src="shots/arch-clinical.jpg" width="440"></a><br>
<sub><b>临床试验 AI 智能体平台</b> · 企业实习主项目</sub>
</td>
<td align="center" width="50%">
<a href="https://github.com/wly-lizhong/yiwang-memory-assistant"><img src="shots/arch-yiwang.jpg" width="440"></a><br>
<sub><b>忆望 · 记忆辅助软件</b> · 商用落地服务 100+ 老人</sub>
</td>
</tr>
</table>

### 项目界面实拍

<table>
<tr>
<td align="center" width="33%"><img src="shots/care-dashboard.jpg" width="290"><br><sub>智能护理数据中心 · 可视化大屏</sub></td>
<td align="center" width="33%"><img src="shots/heart-knowledge-graph.jpg" width="290"><br><sub>心脏病辅助决策 · 医疗知识图谱</sub></td>
<td align="center" width="33%"><img src="shots/heart-qa-answer.jpg" width="290"><br><sub>知识图谱 + RAG 问答（带引用溯源）</sub></td>
</tr>
<tr>
<td align="center" width="33%"><img src="shots/follicle-detect.jpg" width="290"><br><sub>毛囊显微图像检测（YOLO）· 企业项目</sub></td>
<td align="center" width="33%"><img src="shots/hand-yolo.jpg" width="290"><br><sub>YOLO 手部关键点检测 + 手势音量控制</sub></td>
<td align="center" width="33%"><img src="shots/voice-ui.jpg" width="290"><br><sub>多语种语音识别 / 声音克隆界面</sub></td>
</tr>
</table>

> 更多截图见各项目仓库；毛囊显微检测、临床平台等企业/竞赛项目代码不开源，界面与技术细节可在面试展示。

---

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

### 🎮 LLM Agent 综合实践

[sidu-chishui-wargame](https://github.com/wly-lizhong/sidu-chishui-wargame) — 《四渡赤水·统帅席》2.5D 军事沙盘网页游戏：LLM 将领 Agent 会回电、建议、争论、抗命，**规则引擎是唯一裁判、LLM 只输出 JSON 意图**；append-only 事件流可确定性重放；mock 模式零 key 完整运行（FastAPI / Celery / PostgreSQL + React / PixiJS，40+ 测试文件、18 篇设计文档）

### 🎓 更多项目

| 仓库 | 一句话 |
|---|---|
| [ai-avatar-video-pipeline](https://github.com/wly-lizhong/ai-avatar-video-pipeline) | AI 数字人口播视频生产管线：声音克隆 TTS → 换口型/数字人驱动 → FFmpeg 去 AI 感（6 家云服务插拔编排） |
| [green-charity-h5](https://github.com/wly-lizhong/green-charity-h5) | 手写 React 移动端 H5：无限无缝轮播 + 无限滚动/懒加载全原生实现（不套任何组件库） |
| [heart-disease-decision-support](https://github.com/wly-lizhong/heart-disease-decision-support) | 知识图谱 + 检索 + LLM 的心脏病辅助决策应用（带界面截图） |
| [kaiwu-rl-target-dqn](https://github.com/wly-lizhong/kaiwu-rl-target-dqn) | 腾讯开悟强化学习竞赛 target-DQN，奖励函数三轮迭代设计 |

> 简历中的毛囊显微检测（TPH-YOLO）、无人机检测、语音等项目属企业/竞赛资产，无公开代码，面试时可展示架构与技术细节。

---

## 🏆 荣誉墙 · 代表性奖项

<table>
<tr>
<td align="center" width="33%"><img src="honors/sw-adni.jpg" height="150"><br><sub><b>软件著作权</b><br>基于 ADNI 和 3D-CNN 的 AD 智能诊断系统</sub></td>
<td align="center" width="33%"><img src="honors/paper-ei.jpg" height="150"><br><sub><b>EI 会议论文录用</b><br>ICCTDA 2025 · AI 智能工程系统</sub></td>
<td align="center" width="33%"><img src="honors/huawei-euler.jpg" height="150"><br><sub><b>华为云开发者认证</b><br>HCCDA · Huawei Cloud EulerOS</sub></td>
</tr>
<tr>
<td align="center" width="33%"><img src="honors/jingkaibei-p1.jpg" height="150"><br><sub><b>省级一等奖</b><br>经开杯全国大学生创新创业大赛</sub></td>
<td align="center" width="33%"><img src="honors/robot-n2.jpg" height="150"><br><sub><b>全国二等奖</b><br>中国机器人及人工智能大赛 · AI 创新赛</sub></td>
<td align="center" width="33%"><img src="honors/challenge-p3.jpg" height="150"><br><sub><b>省级奖项</b><br>“挑战杯”大学生创业计划竞赛</sub></td>
</tr>
<tr>
<td align="center" width="33%"><img src="honors/sc-smart-med.jpg" height="150"><br><sub><b>四川省智能医学创新设计大赛</b></sub></td>
<td align="center" width="33%"><img src="honors/ai-intl-p2.jpg" height="150"><br><sub><b>省级二等奖</b><br>国际人工智能大赛</sub></td>
<td align="center" width="33%"><img src="honors/lanqiaobei.jpg" height="150"><br><sub><b>蓝桥杯</b> 全国软件和信息技术专业人才大赛</sub></td>
</tr>
</table>

<details>
<summary><b>📜 展开查看全部证书（软著 / 论文 / 竞赛 / 认证共 50+ 项）</b></summary>

### 学术成果 · 软件著作权 + 论文

<table>
<tr>
<td align="center" width="25%"><img src="honors/sw-adni.jpg" height="120"><br><sub>软著·AD 智能诊断系统</sub></td>
<td align="center" width="25%"><img src="honors/sw-chatglm.jpg" height="120"><br><sub>软著·ChatGLM 中文医疗问询系统</sub></td>
<td align="center" width="25%"><img src="honors/sw-01.jpg" height="120"><br><sub>软著·登记证书</sub></td>
<td align="center" width="25%"><img src="honors/sw-novel.jpg" height="120"><br><sub>软著·登记证书</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/sw-law.jpg" height="120"><br><sub>软著·登记证书</sub></td>
<td align="center" width="25%"><img src="honors/paper-ei.jpg" height="120"><br><sub>EI 会议论文录用通知</sub></td>
<td align="center" width="25%"></td>
<td align="center" width="25%"></td>
</tr>
</table>

### 科技 · 创新 · AI 竞赛

<table>
<tr>
<td align="center" width="25%"><img src="honors/jingkaibei-p1.jpg" height="115"><br><sub>经开杯双创·省一等奖</sub></td>
<td align="center" width="25%"><img src="honors/challenge-p3.jpg" height="115"><br><sub>挑战杯·省级</sub></td>
<td align="center" width="25%"><img src="honors/challenge-s1.jpg" height="115"><br><sub>挑战杯·校级一等奖</sub></td>
<td align="center" width="25%"><img src="honors/cicc.jpg" height="115"><br><sub>中国国际大学生创新大赛</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/robot-n2.jpg" height="115"><br><sub>机器人及 AI 大赛·全国二等奖</sub></td>
<td align="center" width="25%"><img src="honors/robot-p2.jpg" height="115"><br><sub>机器人及 AI 大赛·省二等奖</sub></td>
<td align="center" width="25%"><img src="honors/ai-intl-p2.jpg" height="115"><br><sub>国际人工智能大赛·省二</sub></td>
<td align="center" width="25%"><img src="honors/ai-6th.jpg" height="115"><br><sub>人工智能大赛</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/sc-smart-med.jpg" height="115"><br><sub>四川省智能医学创新设计</sub></td>
<td align="center" width="25%"><img src="honors/sc-biomed.jpg" height="115"><br><sub>四川省生物医学工程创新设计</sub></td>
<td align="center" width="25%"><img src="honors/smart-med-p3.jpg" height="115"><br><sub>智慧医疗创新大赛·省级</sub></td>
<td align="center" width="25%"><img src="honors/intl-sw-design.jpg" height="115"><br><sub>国际软件设计应用大赛</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/sw-design-p3.jpg" height="115"><br><sub>全国软件设计创新大赛·省级</sub></td>
<td align="center" width="25%"><img src="honors/lanqiaobei.jpg" height="115"><br><sub>蓝桥杯</sub></td>
<td align="center" width="25%"><img src="honors/cc-design.jpg" height="115"><br><sub>计算机设计大赛</sub></td>
<td align="center" width="25%"><img src="honors/kepu-n3.jpg" height="115"><br><sub>全国青年科普创新·国三</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/ican.jpg" height="115"><br><sub>iCAN 创新创业大赛·优胜</sub></td>
<td align="center" width="25%"><img src="honors/chuangyi-gold.jpg" height="115"><br><sub>创祎杯·金奖</sub></td>
<td align="center" width="25%"><img src="honors/chuangyi-silver.jpg" height="115"><br><sub>创祎杯·银奖</sub></td>
<td align="center" width="25%"><img src="honors/chuangyi-bronze.jpg" height="115"><br><sub>创祎杯·铜奖</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/shangzheng-p3.jpg" height="115"><br><sub>上证杯双创·省级</sub></td>
<td align="center" width="25%"><img src="honors/shumei-p3.jpg" height="115"><br><sub>数字媒体省赛·三等奖</sub></td>
<td align="center" width="25%"><img src="honors/sanchuang.jpg" height="115"><br><sub>三创赛</sub></td>
<td align="center" width="25%"><img src="honors/shuxingbei.jpg" height="115"><br><sub>数型杯</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/duzhebei.jpg" height="115"><br><sub>读者杯</sub></td>
<td align="center" width="25%"><img src="honors/baimo.jpg" height="115"><br><sub>百模论剑</sub></td>
<td align="center" width="25%"><img src="honors/shuzibaijing.jpg" height="115"><br><sub>数字百景奖</sub></td>
<td align="center" width="25%"><img src="honors/chuangxiang.jpg" height="115"><br><sub>创想中国</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/intl-youth-2.jpg" height="115"><br><sub>国际青年总决赛·国际二等奖</sub></td>
<td align="center" width="25%"><img src="honors/un-cert.jpg" height="115"><br><sub>联合国证书</sub></td>
<td align="center" width="25%"><img src="honors/cada2025.jpg" height="115"><br><sub>2025 CADA</sub></td>
<td align="center" width="25%"><img src="honors/fire-p1.jpg" height="115"><br><sub>全民消防科普·省一等奖</sub></td>
</tr>
</table>

### 职业认证

<table>
<tr>
<td align="center" width="25%"><img src="honors/huawei-euler.jpg" height="115"><br><sub>华为云开发者认证 HCCDA</sub></td>
<td align="center" width="25%"><img src="honors/huawei-appdev.jpg" height="115"><br><sub>华为应用开发者认证</sub></td>
<td align="center" width="25%"><img src="honors/mandarin.jpg" height="115"><br><sub>普通话水平测试</sub></td>
<td align="center" width="25%"></td>
</tr>
</table>

### 作品存证 · 综合素质

<table>
<tr>
<td align="center" width="25%"><img src="honors/deposit-yiwang.jpg" height="110"><br><sub>作品存证·忆路相随</sub></td>
<td align="center" width="25%"><img src="honors/deposit-zhiji.jpg" height="110"><br><sub>作品存证·智迹通途</sub></td>
<td align="center" width="25%"><img src="honors/aigc-1.jpg" height="110"><br><sub>AIGC 存证</sub></td>
<td align="center" width="25%"><img src="honors/aigc-2.jpg" height="110"><br><sub>AIGC 存证</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/scholarship.jpg" height="110"><br><sub>励志奖学金</sub></td>
<td align="center" width="25%"><img src="honors/project-final.jpg" height="110"><br><sub>大创项目结项</sub></td>
<td align="center" width="25%"><img src="honors/school-1.jpg" height="110"><br><sub>校赛一等奖</sub></td>
<td align="center" width="25%"><img src="honors/school-2.jpg" height="110"><br><sub>校赛二等奖</sub></td>
</tr>
<tr>
<td align="center" width="25%"><img src="honors/kepu-vol.jpg" height="110"><br><sub>科普志愿</sub></td>
<td align="center" width="25%"><img src="honors/volunteer.jpg" height="110"><br><sub>志愿服务</sub></td>
<td align="center" width="25%"><img src="honors/marathon-full.jpg" height="110"><br><sub>成都双遗马拉松·全马完赛</sub></td>
<td align="center" width="25%"><img src="honors/marathon-vol.jpg" height="110"><br><sub>马拉松志愿者</sub></td>
</tr>
</table>

</details>

---

## 技能

| 方向 | 内容 |
|---|---|
| 深度学习 / CV | PyTorch · YOLO 系目标检测 · U-Net 分割 · 3D-CNN · OpenCV |
| 大模型应用 | RAG（LlamaIndex / LangChain）· Agent 工具调用 · QLoRA 微调 · Prompt 工程 · 多模态视觉模型应用 |
| 工程化 | Python · FastAPI · Docker · Git · MySQL / Redis 基础 |
| 模型部署 | ONNX 导出与精度对齐 · onnxruntime 推理 · PTQ 量化入门（TensorRT 系统学习中） |

## 我在找什么

2026 届校招 / 实习转正机会：**AI 应用工程师 / 算法工程师**（医疗 AI、大模型应用方向尤佳），坐标不限，即时到岗。
