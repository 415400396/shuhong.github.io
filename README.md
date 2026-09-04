<div align="center">

# 陆书鸿 · Shuhong Lu

### AI Application / Agent Engineer · Applied Machine Learning · Generative AI

将机器学习与大模型能力落地为可评估、可观测、可持续迭代的生产系统

[![Email](https://img.shields.io/badge/Email-415400396%40qq.com-1f6feb?style=flat-square&logo=maildotru&logoColor=white)](mailto:415400396@qq.com)
[![GitHub](https://img.shields.io/badge/GitHub-415400396-181717?style=flat-square&logo=github)](https://github.com/415400396)
[![Location](https://img.shields.io/badge/Location-Hangzhou%2C%20China-2ea44f?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

## 👋 关于我 / About Me

我是一名具有计算机视觉研究背景的 **AI 应用与算法工程师**，目前主要关注 **Agent 工程、RAG、Context Engineering、机器学习系统和大模型应用落地**。

我的经历横跨学术研究与工业生产：早期从事动作生成、语音驱动手势合成与离散扩散模型研究；进入工业界后，先后参与深度学习框架、大模型推理、医疗与心理咨询 Agent 等项目，目前负责两轮车换电场景中的预测模型与智能决策工具。

相比单纯训练模型，我更关注如何把模型真正接入业务：从问题定义、数据与特征、模型选择，到 API 服务、规则约束、人工审批、效果评估、线上监控和持续迭代。

> **Current focus:** Agent Runtime · RAG & Evaluation · Structured Output · Human-in-the-loop · Production ML

---

## 💼 工作经历 / Experience

### 滴滴出行 · 杭州青桔科技有限公司

**高级算法工程师｜两轮车业务线 · 用户保障策略组**  
`2025.09 – Present · Hangzhou`

- 负责电单车换电核心业务中的预测模型、策略工具与 AI 应用建设，覆盖全国多城市生产场景。
- 迭代换电工单时长预测模型，将 XGBoost 模型从 V2 升级至 V3/V4，完成数据构建、特征工程、损失设计、离线评估、版本兼容与线上监控。
- 建设城市诊断与异动分析 Agent，综合历史趋势、天气、运维资源和业务规则进行异常排查，并给出可解释的阈值调整建议。
- 建设基于 LLM 与 RAG 的换电阈值修改工具，将自然语言请求转换为结构化配置，结合规则校验、预览执行、人工/Agent 审批及审计链路实现生产闭环。
- 参与高频在线阈值服务和策略保障，关注服务稳定性、模型效果、异常回退与线上可观测性。

### 中国电子科技南湖研究院（中电海康）

**算法工程师**  
`2024.05 – 2025.08 · Hangzhou`

- 构建面向 CBT 心理咨询的多智能体原型，设计用户分析、咨询专家与 CBT 顾问之间的协作流程。
- 基于脱敏咨询流程数据进行数据合成、知识库构建与轻量 SFT，使用 Unsloth 完成 Qwen 系列模型微调实验。
- 探索混合检索、反思式 RAG、结构化输出和多轮对话追踪，提升专业知识问答的一致性。
- 参与 Qwen MoE 架构重构与动态专家路由实验，并使用 CUDA/Triton 优化关键算子。
- 基于 JAX 开发和迁移深度学习模型，参与 LLaMA、YOLO 等模型的转换、部署与性能优化。

### USC Institute for Creative Technologies

**Full-time Researcher**  
`2023.01 – 2024.02 · Los Angeles`

- 研究基于 VQ-VAE、Residual Quantization 与 Diffusion Model 的语音驱动手势生成和文本动作生成。
- 参与 GENEA Challenge 2022/2023，并围绕离散动作表征与扩散生成发表 IROS、BMVC、ICMI 等论文。
- 开发研究评估平台并组织用户研究，完成从模型训练、指标评估到主观实验的完整研究流程。
- 参与监控视频中的群体活动识别，探索 RGB、Skeleton 与 Cross-Attention 多模态建模。

---

## 🚀 代表项目 / Featured Projects

| 方向 | 项目 | 关键工作 |
|---|---|---|
| **Production ML** | 电单车换电时长预测 | XGBoost、时间与业务特征、长尾样本加权、版本迭代、离线/线上评估、灰度与监控 |
| **Agent Engineering** | 城市诊断与异动分析 Agent | 多源 Context、指标查询、异常下钻、规则约束、可解释建议、Badcase 迭代 |
| **LLM Application** | 换电阈值智能修改工具 | RAG、Structured Output、Schema 校验、Human-in-the-loop、审批与审计 |
| **Multi-Agent** | CBT 心理咨询系统 | 角色协作、路由与任务分发、知识库、合成数据、Unsloth SFT、多轮对话 |
| **LLM Inference** | Qwen MoE 重构 | 动态专家路由、SNN 路由实验、CUDA/Triton 算子与 vLLM 推理优化 |
| **Generative AI** | Co-speech Gesture & Text-to-Motion | VQ-VAE、Residual Quantization、Discrete Diffusion、用户研究与生成评估 |

### 当前重点：生产级 Agent 系统

我目前重点积累以下工程能力：

- **Agent Workflow：** Router、Planning、Tool Calling、Reflection 与确定性流程协作。
- **Context & RAG：** 文档解析、混合检索、Rerank、业务规则注入和上下文管理。
- **可靠性：** Structured Output、参数验证、权限控制、幂等、超时、重试和降级。
- **Evaluation：** 任务成功率、工具选择准确率、参数正确率、延迟、成本和 Badcase 回流。
- **Productionization：** API、数据库、日志追踪、审批链路、可观测性与持续迭代。

---

## 📚 论文 / Publications

1. **Co-Speech Gesture Synthesis using Discrete Gesture Token Learning**  
   *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2023* · **First Author**  
   [Paper](https://doi.org/10.48550/arXiv.2303.12822)

2. **Text-to-Motion Synthesis using Discrete Diffusion Model**  
   *British Machine Vision Conference (BMVC), 2023*  
   [Paper](https://proceedings.bmvc2023.org/624/)

3. **Discrete Diffusion for Co-Speech Gesture Synthesis**  
   *ACM International Conference on Multimodal Interaction (ICMI), 2023*  
   [Paper](https://doi.org/10.1145/3610661.3616556)

4. **The DeepMotion Entry to the GENEA Challenge 2022**  
   *ACM International Conference on Multimodal Interaction (ICMI), 2022*  
   [Paper](https://doi.org/10.1145/3536221.3558059)

---

## 🧰 技术栈 / Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### AI / Machine Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-5A29E4?style=flat-square&logo=google&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square&logo=python&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-5B45FF?style=flat-square&logo=lightning&logoColor=white)

### Engineering & Data

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 🎓 教育背景 / Education

- **University of Southern California** — M.S. in Computer Science, `2020 – 2022`  
  GPA: **3.83/4.0** · Computer Science Master's Student Honors Program

- **University of California, Berkeley** — Exchange Program, `2019`  
  Coursework: Algorithms, Machine Learning, Artificial Intelligence

- **浙江工业大学** — B.E. in Computer Science and Technology, `2016 – 2020`  
  GPA: **4.03/5.0** · Rank: **2/85**

---

## 🏆 荣誉 / Honors

- USC Computer Science Master's Student Honors Program
- 浙江省政府奖学金 × 3（Top 5%）
- 全国大学生数学竞赛浙江赛区二等奖
- GENEA Challenge 2022 / 2023 参赛与获奖经历

---

## 📊 GitHub

<div align="center">

![Shuhong's GitHub stats](https://github-readme-stats.vercel.app/api?username=415400396&show_icons=true&hide_border=true&rank_icon=github&theme=transparent)

</div>

---

## 📫 联系我 / Contact

- **Email:** [415400396@qq.com](mailto:415400396@qq.com)
- **GitHub:** [github.com/415400396](https://github.com/415400396)
- **Location:** Hangzhou, China

如果你正在关注 Agent 工程、RAG、生产级机器学习或生成式动作研究，欢迎交流。

