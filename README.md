![Yao Song - Multimodal Perception and AI Systems](assets/profile-header.png)

<p align="center"><samp><a href="#en">English</a> · <a href="#cn">中文</a></samp></p>

<a id="en"></a>

# Hi!  👋 I'm Yao Song

Applied AI · Multimodal Learning · Intelligent Systems · Agent

I am an MSc Computer Science student at The University of Hong Kong, with research interests in applied machine learning, multimodal representation learning, and AI for real-world intelligent systems.

I am currently a Research Intern at the Tsinghua Intelligent Connected Vehicle Group (THICV). I also contribute to AI research and engineering at Poxiaoyunyi Technology, a BUPT-affiliated technology team.

Previously, I worked as a Data and AI Intern at Lenovo, supporting data analysis, AI-model prototyping, and product-oriented technical research.


## Selected engineering work

| Project | Engineering focus | Stack |
|---|---|---|
| [**UK Visitor Visa Agent**](https://github.com/YaoSong808/uk-visitor-visa-agent) | Local-first document review agent that checks dates, travel plans, finances and sponsorship evidence, then produces risk flags, checklists and draft explanations. Ships as a web app, Windows desktop release and reusable Codex skill. | TypeScript, Next.js, OpenAI API, Electron |
| [**AI Teaching Agents**](https://github.com/mooooohan/AI_teaching_agents) | Team-built with classmates: a multi-agent teaching system for personalized content, intelligent practice, learning analytics, document processing and session management, with support for OpenAI, DeepSeek, Qwen and custom model providers. | Python, Streamlit, Agno, LLM APIs |
| [**Cantonese Speech Emotion Recognition**](https://github.com/Rudeotaku/Cantonese-SER-model) | Team coursework project for Cantonese speech-emotion recognition; contributed multimodal experiments combining classical and neural baselines with reproducible training pipelines and reports. | Python, PyTorch, librosa, scikit-learn |
| [**Urban Scene Semantic Segmentation**](https://github.com/YaoSong808/urban-scene-semantic-segmentation) | U-Net and DeepLabV3+ pipelines for dense urban-scene understanding. The retained U-Net experiment records **0.6786 mIoU** and **89.42% pixel accuracy** on its validation split. | Python, TensorFlow, PyTorch, OpenCV |
| [**Commerce Operations Platform**](https://github.com/YaoSong808/commerce-operations-platform) | Full-stack operational system spanning product data, marketplace orders, procurement, inventory, warehouse fulfilment, settlement and reconciliation. Published as a sanitized engineering snapshot with no business data or credentials. | Next.js, TypeScript, React, Prisma, SQLite |
| [**CIFAR Robust Training Pipeline**](https://github.com/YaoSong808/cifar-robust-training-pipeline) | Reproducible image-classification workflow covering data materialization, augmentation, robust training, checkpoints and metric-driven evaluation. | Python, PyTorch, torchvision, scikit-learn |
| [**MSc Buddy**](https://github.com/YaoSong808/msc-buddy) | Cross-platform collaboration workspace for team formation, project planning, task ownership and deadline tracking. | Flutter, Dart, Provider |

## Open source contributions

I have **12 merged pull requests in external repositories**, spanning AI-agent infrastructure, security, developer tooling, compliance and data systems. **Cantonese Speech Emotion Recognition is a team engineering project listed above; it is not counted as an external contribution.**

### Merged contributions

| Project | PR | Contribution |
|---|---|---|
| [Prompt Shield](https://github.com/mthamil107/prompt-shield) | [#32](https://github.com/mthamil107/prompt-shield/pull/32) | Added a PydanticAI tool-result guard with model-facing serialization, structure-preserving sanitization and explicit toolset-scope documentation. |
| [Tracekit](https://github.com/Cygnux-Labs/Tracekit) | [#350](https://github.com/Cygnux-Labs/Tracekit/pull/350) | Added OpenCode coding-agent hooks and regression coverage. |
| [MCP Memory Service](https://github.com/doobidoo/mcp-memory-service) | [#1541](https://github.com/doobidoo/mcp-memory-service/pull/1541) | Added an OpenCode inter-agent inbox for scoped message delivery and retrieval. |
| [Xenon](https://github.com/xianyu-sheng/Xenon) | [#142](https://github.com/xianyu-sheng/Xenon/pull/142) | Added provenance markers and advisory detection for untrusted tool output. |
| [Railtracks](https://github.com/RailtownAI/railtracks) | [#1519](https://github.com/RailtownAI/railtracks/pull/1519) | Added cache-aware LLM request-cost regression coverage, including cached input-token accounting. |
| [Pyrite](https://github.com/pyrite-wiki/pyrite) | [#116](https://github.com/pyrite-wiki/pyrite/pull/116) | Rejected nonexistent `kb_link` targets to prevent silent dangling knowledge-base links. |
| [Payband MCP](https://github.com/dheerajjha/payband-mcp) | [#20](https://github.com/dheerajjha/payband-mcp/pull/20) | Added a SmartRecruiters job-board adapter. |
| [LibreDB Studio](https://github.com/libredb/libredb-studio) | [#892](https://github.com/libredb/libredb-studio/pull/892) | Made the Code Generator modal close on an unhandled Escape keypress and added focused regression coverage. |
| [Maven Decoder MCP](https://github.com/salitaba/maven-decoder-mcp) | [#35](https://github.com/salitaba/maven-decoder-mcp/pull/35) | Documented a worked `find_usage_examples` workflow covering filters, test ranking, caller scanning and scan limits. |
| [SafeAI](https://github.com/ikaruscareer/SafeAI) | [#159](https://github.com/ikaruscareer/SafeAI/pull/159) | Added first-class OpenClaw and GitHub Copilot configuration adapters with discovery and compatibility tests. |
| [The PR Agent](https://github.com/The-PR-Agent/pr-agent) | [#2867](https://github.com/The-PR-Agent/pr-agent/pull/2867) | Corrected fallback chunk alignment after a conversion failure and added regression coverage for changed boundaries. |
| [The PR Agent](https://github.com/The-PR-Agent/pr-agent) | [#2863](https://github.com/The-PR-Agent/pr-agent/pull/2863) | Made partial `/improve` analysis visible by reporting incomplete suggestion coverage and testing complete, partial and fallback paths. |

### Active reviews

| Project | PR and status | Contribution |
|---|---|---|
| [Caura](https://github.com/caura-ai/caura-build-fleet) | [#73](https://github.com/caura-ai/caura-build-fleet/pull/73) · **Approved · Awaiting merge** | Adds an Apify actor fallback for stalled Facebook Marketplace browser extraction, with timeout, retry and regression coverage. |
| [RAI Toolkit](https://github.com/wandb/rai-toolkit) | [#20](https://github.com/wandb/rai-toolkit/pull/20) · **Revision pushed · CI awaiting approval** | Adds safe agent tool-use and goal-hijack red-team templates, including multiline action-syntax detection and regression tests that exclude refusal text. |
| [Prowler](https://github.com/prowler-cloud/prowler) | [#12650](https://github.com/prowler-cloud/prowler/pull/12650) · **Review required · CI passing** | Extends Cyber Essentials 3.3 mappings to AWS while preserving Azure mappings, with discovery, reference-integrity and output tests. |

## Research and engineering focus

- Multimodal perception, autonomous systems and sensor fusion
- Semantic segmentation, image classification and signal-based learning
- Reproducible experimentation, evaluation and evidence-backed reporting
- Full-stack operational systems, data workflows and deployment engineering

## Core stack

**ML and vision:** Python, PyTorch, TensorFlow, OpenCV, scikit-learn<br>
**Systems and applications:** TypeScript, Next.js, React, Flutter, Java, C/C++<br>
**Data and operations:** Prisma, SQL, Linux, Nginx, Git

## Additional builds

- [KidsBank](https://github.com/YaoSong808/Software-Engineering-Group-23) - team-built JavaFX financial-literacy application with structured controllers and tests
- [ParkShare](https://github.com/YaoSong808/ParkNLot) - responsive parking-sharing product concept with driver, owner and wallet flows
- [Obstacle-Avoidance Robot](https://github.com/YaoSong808/D-Bproject) - Arduino control system using ultrasonic sensing, motor actuation and an I²C display

Public repositories are curated to keep claims traceable, source readable and private datasets, credentials and operational records out of version control.

---

<a id="cn"></a>

<p align="center"><samp><a href="#en">English</a> · <a href="#cn">中文</a></samp></p>

# 你好！ 👋 我是宋尧

**应用机器学习 · 多模态感知 · AI Agent**

我是香港大学计算机科学硕士研究生，研究方向为应用型机器学习、多模态表征学习，以及面向真实场景的智能系统人工智能技术。

目前任职于清华大学智能网联汽车研究组（THICV）担任研究实习生，从事端到端自动驾驶相关工作。同时，我也在北邮团队破晓云逸科技负责人工智能科研与工程落地工作。

此前，我曾在联想担任数据与人工智能实习生，负责数据分析、AI 模型原型开发以及面向产品的技术调研。



## 代表性工程项目

| 项目 | 工程重点 | 技术栈 |
|---|---|---|
| [**英国访客签证材料助手**](https://github.com/YaoSong808/uk-visitor-visa-agent) | 本地优先的材料审查 Agent，核对日期、行程、资金与担保材料，输出风险提示、材料清单和说明草稿；同时提供 Web 应用、Windows 桌面版本和可复用 Codex skill。 | TypeScript, Next.js, OpenAI API, Electron |
| [**AI Teaching Agents**](https://github.com/mooooohan/AI_teaching_agents) | 与同学共同开发的多 Agent 教学系统，支持个性化内容生成、智能练习、学习分析、文档处理和会话管理，并兼容 OpenAI、DeepSeek、通义千问及自定义模型服务。 | Python, Streamlit, Agno, LLM APIs |
| [**粤语语音情感识别系统**](https://github.com/Rudeotaku/Cantonese-SER-model) | 小组课程项目：本人作为组员参与多模态实验，将经典机器学习与神经网络基线结合，并整理可复现训练流程和实验报告。 | Python, PyTorch, librosa, scikit-learn |
| [**城市街景语义分割**](https://github.com/YaoSong808/urban-scene-semantic-segmentation) | 面向城市街景理解的 U-Net 与 DeepLabV3+ 训练流程；保留的 U-Net 实验在验证集上达到 **0.6786 mIoU** 与 **89.42% 像素准确率**。 | Python, TensorFlow, PyTorch, OpenCV |
| [**电商运营管理平台**](https://github.com/YaoSong808/commerce-operations-platform) | 覆盖商品、平台订单、采购、库存、仓储履约、结算与对账的全栈业务系统；公开版本已移除业务数据和凭据。 | Next.js, TypeScript, React, Prisma, SQLite |
| [**CIFAR 鲁棒训练流程**](https://github.com/YaoSong808/cifar-robust-training-pipeline) | 可复现的图像分类流程，涵盖数据生成、增强、鲁棒训练、检查点管理与指标驱动评估。 | Python, PyTorch, torchvision, scikit-learn |
| [**MSc Buddy**](https://github.com/YaoSong808/msc-buddy) | 面向组队、项目规划、任务归属和截止日期管理的跨平台协作空间。 | Flutter, Dart, Provider |

## 开源贡献

目前共有 **12 个外部仓库 PR 已合并**，覆盖 AI Agent 基础设施、安全、开发者工具、合规与数据系统。**粤语语音情感识别系统属于本人参与的团队工程项目，列在上方“代表性工程项目”中，不计入外部开源 PR 数量。**

### 已合并贡献

| 项目 | PR | 贡献内容 |
|---|---|---|
| [Prompt Shield](https://github.com/mthamil107/prompt-shield) | [#32](https://github.com/mthamil107/prompt-shield/pull/32) | 增加 PydanticAI 工具结果防护层，覆盖面向模型的序列化、保留结构的清理逻辑与 toolset 作用域说明。 |
| [Tracekit](https://github.com/Cygnux-Labs/Tracekit) | [#350](https://github.com/Cygnux-Labs/Tracekit/pull/350) | 增加 OpenCode 编码 Agent hooks 与回归测试。 |
| [MCP Memory Service](https://github.com/doobidoo/mcp-memory-service) | [#1541](https://github.com/doobidoo/mcp-memory-service/pull/1541) | 增加 OpenCode 多 Agent 收件箱，支持带作用域的消息投递与读取。 |
| [Xenon](https://github.com/xianyu-sheng/Xenon) | [#142](https://github.com/xianyu-sheng/Xenon/pull/142) | 为不可信工具输出增加来源标记与风险提示检测。 |
| [Railtracks](https://github.com/RailtownAI/railtracks) | [#1519](https://github.com/RailtownAI/railtracks/pull/1519) | 补充缓存感知的 LLM 请求成本回归测试，覆盖缓存输入 token 计费。 |
| [Pyrite](https://github.com/pyrite-wiki/pyrite) | [#116](https://github.com/pyrite-wiki/pyrite/pull/116) | 拒绝指向不存在目标的 `kb_link`，避免静默产生悬空知识库链接。 |
| [Payband MCP](https://github.com/dheerajjha/payband-mcp) | [#20](https://github.com/dheerajjha/payband-mcp/pull/20) | 增加 SmartRecruiters 招聘网站适配器。 |
| [LibreDB Studio](https://github.com/libredb/libredb-studio) | [#892](https://github.com/libredb/libredb-studio/pull/892) | 支持按 Escape 关闭 Code Generator 弹窗，并补充针对性回归测试。 |
| [Maven Decoder MCP](https://github.com/salitaba/maven-decoder-mcp) | [#35](https://github.com/salitaba/maven-decoder-mcp/pull/35) | 补充 `find_usage_examples` 完整示例，覆盖过滤、测试排序、调用方扫描与扫描上限。 |
| [SafeAI](https://github.com/ikaruscareer/SafeAI) | [#159](https://github.com/ikaruscareer/SafeAI/pull/159) | 增加 OpenClaw 与 GitHub Copilot 配置适配器，以及文件发现和兼容性测试。 |
| [The PR Agent](https://github.com/The-PR-Agent/pr-agent) | [#2867](https://github.com/The-PR-Agent/pr-agent/pull/2867) | 修复转换失败后回退分块的成员与边界错位问题，并补充回归测试。 |
| [The PR Agent](https://github.com/The-PR-Agent/pr-agent) | [#2863](https://github.com/The-PR-Agent/pr-agent/pull/2863) | 让部分 `/improve` 分析的覆盖范围可见，并覆盖完整、部分与回退路径测试。 |

### 进行中的审查

| 项目 | PR 与状态 | 贡献内容 |
|---|---|---|
| [Caura](https://github.com/caura-ai/caura-build-fleet) | [#73](https://github.com/caura-ai/caura-build-fleet/pull/73) · **已批准 · 等待合并** | 为卡住的 Facebook Marketplace 浏览器提取增加 Apify actor 回退机制，并覆盖超时、重试和回归测试。 |
| [RAI Toolkit](https://github.com/wandb/rai-toolkit) | [#20](https://github.com/wandb/rai-toolkit/pull/20) · **已推送修改 · CI 等待批准** | 增加安全的 Agent 工具调用与目标劫持红队模板，覆盖多行调用语法检测，并避免将拒绝文本误判为成功攻击。 |
| [Prowler](https://github.com/prowler-cloud/prowler) | [#12650](https://github.com/prowler-cloud/prowler/pull/12650) · **等待审查 · CI 通过** | 在保留 Azure 映射的基础上，为 Cyber Essentials 3.3 增加 AWS 合规映射及发现、引用完整性与输出测试。 |

## 研究与工程方向

- 多模态感知、自动驾驶系统与传感器融合
- 语义分割、图像分类与信号学习
- 可复现实验、模型评估与证据导向的技术报告
- 全栈业务系统、数据工作流与部署工程

## 核心技术栈

**机器学习与视觉：** Python、PyTorch、TensorFlow、OpenCV、scikit-learn<br>
**系统与应用开发：** TypeScript、Next.js、React、Flutter、Java、C/C++<br>
**数据与运维：** Prisma、SQL、Linux、Nginx、Git

## 其他项目

- [KidsBank](https://github.com/YaoSong808/Software-Engineering-Group-23) - 团队开发的 JavaFX 金融素养应用，包含结构化控制器与测试
- [ParkShare](https://github.com/YaoSong808/ParkNLot) - 响应式停车位共享产品原型，包含车主、驾驶员与钱包流程
- [避障机器人](https://github.com/YaoSong808/D-Bproject) - 基于超声波感知、电机控制与 I²C 显示屏的 Arduino 控制系统

公开仓库经过整理，确保项目描述可追溯、源码可读，同时不会将私有数据、凭据或运营记录提交到版本控制中。
