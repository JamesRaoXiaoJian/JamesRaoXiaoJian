# James | Rao Xiaojian (饶小建)

<p align="center">
  <a href="#中文">中文</a> · <a href="#english">English</a>
</p>

## 中文

你好，我是 James，中文名饶小建，目前就读于深圳大学计算机科学与技术专业。

我关注机器人、具身智能、多模态感知，以及把研究代码落到真实系统中的工程工具。近期工作主要围绕 Vision-Language-Action、真机多模态数据采集、Unitree G1 运动控制和 AI 应用开发展开。

### 当前关注

- 面向机器人操作的 Vision-Language-Action 模型
- RGB-D、触觉/压力、机械臂状态、夹爪状态等真机多模态数据采集与对齐
- Unitree G1 动作回放、MuJoCo 仿真和 sim-to-real 控制流程
- AI 工具、自动化脚本和交互式应用

### 代表项目

#### Robotics & Embodied AI

**TransVTLA**

一个持续推进中的透明/触觉 Vision-Language-Action 研究项目。项目探索如何将 2D 图像、3D 点云、触觉信号、机器人状态和语言指令统一融合到机器人动作模型中，涉及 MLA/OpenVLA 风格模型改造、扩散/自回归动作预测、多模态对齐、未来感知预测，以及面向训练的数据管线。

[**TransVTLA-RealDataCollect**](https://github.com/JamesRaoXiaoJian/TransVTLA-RealDataCollect)

面向真机机械臂实验的多模态数据工程工具链，覆盖双 RealSense RGB-D 采集、触觉/压力传感、机械臂与夹爪状态记录、离线回放、数据审计、清洗、任务划分和 RLDS/TFDS 导出。

[**G1 Motion Player**](https://github.com/JamesRaoXiaoJian/g1_motion_player)

Unitree G1 动作回放工具，围绕 CSV 动作执行链路构建。项目通过 Unitree SDK DDS 话题向 `rt/arm_sdk` 下发动作，提供 FastAPI 回放接口，并加入 nearest-window 入口/退出选择和速度钳位等过渡策略。

[**unitree_mujoco**](https://github.com/JamesRaoXiaoJian/unitree_mujoco)

基于 MuJoCo 与 Unitree SDK2 的仿真环境，用于低层控制验证和 sim-to-real 开发。我围绕这一技术栈进行 G1 运动实验、SDK 集成和机器人调试流程建设。

#### Multimodal AI & Interactive Systems

[**SafeSentinel**](https://github.com/JamesRaoXiaoJian/safesentinel)

一个面向校园安全场景的智能多模态 AI 系统，结合人员检测、多目标跟踪、动作识别和视觉语言风险分析。技术栈包括 YOLO11、BoT-SORT/ByteTrack、S3D 动作识别、PyTorch Lightning 和 Qwen 风格 VLM 分析。

[**SV_Soul**](https://github.com/JamesRaoXiaoJian/SV_Soul)

面向《星露谷物语》的 AI NPC 系统，围绕角色人设、长期记忆、实时游戏上下文和自然对话体验构建。

#### Web & Practical Tools

[**FRPWatch**](https://github.com/JamesRaoXiaoJian/FRPWatch)

一个轻量级 FRP 节点监控工具，定期检查代理节点在线状态，并在节点离线时发送邮件告警。

[**Flexible-Electronics-Cup**](https://github.com/JamesRaoXiaoJian/Flexible-Electronics-Cup)

柔性电子杯官网界面项目。

[**volunteer-hours-ranking**](https://github.com/JamesRaoXiaoJian/volunteer-hours-ranking)

一个用于志愿时长排行和展示的小型 JavaScript 项目。

### 技术栈

**编程语言**

Python · C++ · C# · JavaScript · HTML/CSS

**AI & Robotics**

PyTorch · OpenVLA/MLA · MuJoCo · RLBench · RealSense · RLDS/TFDS · YOLO · Vision-Language Models

**工程工具**

FastAPI · CMake · Linux · Git · data pipelines · model training/evaluation scripts

### 联系

- GitHub: [@JamesRaoXiaoJian](https://github.com/JamesRaoXiaoJian)
- Location: Shenzhen, China

---

## English

Hi, I'm James. My Chinese name is Rao Xiaojian (饶小建), and I am studying Computer Science and Technology at Shenzhen University.

I work on robotics, embodied AI, multimodal perception, and engineering tools that connect research code with real-world systems. My recent work focuses on Vision-Language-Action models, real-robot multimodal data collection, Unitree G1 motion control, and AI applications.

### Current Focus

- Vision-Language-Action models for robotic manipulation
- Real-world multimodal data collection with RGB-D, tactile/pressure, robot state, and gripper signals
- Unitree G1 motion playback, MuJoCo simulation, and sim-to-real control workflows
- AI tools, automation scripts, and interactive applications

### Featured Work

#### Robotics & Embodied AI

**TransVTLA**

An ongoing research project for transparent and tactile Vision-Language-Action learning. It explores how 2D vision, 3D point clouds, tactile signals, robot states, and language instructions can be fused into a unified action model for robotic manipulation, including MLA/OpenVLA-style model adaptation, diffusion and autoregressive action prediction, multimodal alignment, future perception prediction, and training data pipelines.

[**TransVTLA-RealDataCollect**](https://github.com/JamesRaoXiaoJian/TransVTLA-RealDataCollect)

A real-robot multimodal data engineering toolkit for robotic arm experiments. It covers dual RealSense RGB-D capture, tactile/pressure sensing, robot and gripper state logging, offline replay, dataset auditing, cleaning, task splitting, and RLDS/TFDS export.

[**G1 Motion Player**](https://github.com/JamesRaoXiaoJian/g1_motion_player)

A Unitree G1 motion replay tool built around CSV motion execution. It uses Unitree SDK DDS topics for `rt/arm_sdk` control, includes a FastAPI replay interface, and adds transition logic such as nearest-window entry/exit selection and velocity clamping.

[**unitree_mujoco**](https://github.com/JamesRaoXiaoJian/unitree_mujoco)

A MuJoCo + Unitree SDK2 simulation environment for low-level robot control verification and sim-to-real development. My work around this stack focuses on G1 motion experiments, SDK integration, and practical debugging workflows.

#### Multimodal AI & Interactive Systems

[**SafeSentinel**](https://github.com/JamesRaoXiaoJian/safesentinel)

An intelligent campus safety monitoring system combining person detection, multi-object tracking, action recognition, and vision-language risk analysis. The stack includes YOLO11, BoT-SORT/ByteTrack, S3D action recognition, PyTorch Lightning, and Qwen-style VLM analysis.

[**SV_Soul**](https://github.com/JamesRaoXiaoJian/SV_Soul)

An AI-powered NPC system for Stardew Valley, designed around character personas, persistent memory, real-time game context, and more natural in-game dialogue.

#### Web & Practical Tools

[**FRPWatch**](https://github.com/JamesRaoXiaoJian/FRPWatch)

A lightweight monitoring tool for FRP proxy nodes, with regular status checks and email alerts when a node goes offline.

[**Flexible-Electronics-Cup**](https://github.com/JamesRaoXiaoJian/Flexible-Electronics-Cup)

A website interface for the Flexible Electronics Cup.

[**volunteer-hours-ranking**](https://github.com/JamesRaoXiaoJian/volunteer-hours-ranking)

A small JavaScript project for volunteer-hours ranking and display.

### Tech Stack

**Languages**

Python · C++ · C# · JavaScript · HTML/CSS

**AI & Robotics**

PyTorch · OpenVLA/MLA · MuJoCo · RLBench · RealSense · RLDS/TFDS · YOLO · Vision-Language Models

**Engineering**

FastAPI · CMake · Linux · Git · data pipelines · model training/evaluation scripts

### Connect

- GitHub: [@JamesRaoXiaoJian](https://github.com/JamesRaoXiaoJian)
- Location: Shenzhen, China

---

## GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=JamesRaoXiaoJian&show_icons=true&hide_border=true" alt="JamesRaoXiaoJian's GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JamesRaoXiaoJian&layout=compact&hide_border=true" alt="Top languages" />
</p>
