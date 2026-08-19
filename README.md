# James | 饶小建

<p align="center">
  <a href="README.md">中文</a> · <a href="README_EN.md">English</a>
</p>

你好，我是 James，中文名饶小建，目前就读于深圳大学计算机科学与技术专业。

我关注机器人、具身智能与多模态感知，尤其是如何把策略模型可靠地部署到真实机器人上。近期工作主要围绕 Unitree G1、Piper-X、灵巧手运动重定向、真机数据工程，以及 Vision-Language-Action 策略的仿真与实机评估展开。

`人手 / RGB-D / 机器人状态 → 重定向与数据集 → ACT / SmolVLA / π0.5 → 仿真评估 → Piper-X / Unitree G1 真机`

## 当前关注

- Unitree G1 机械臂与灵巧手的 28-DoF 策略推理和安全实机评估
- Piper-X 双 RGB-D 数据采集、安全回放、LeRobot v3 转换与 π0.5 实时推理
- 基于人手输入的 LEAP Hand / Allegro Hand 运动重定向与模仿学习
- RGB-D、触觉/压力、机械臂状态和夹爪状态等真机多模态数据采集与对齐
- MuJoCo、Isaac Lab、ROS 2 与 Unitree SDK2 驱动的 sim-to-real 工具链

## 最近项目

[**sim2real_g1**](https://github.com/JamesRaoXiaoJian/sim2real_g1) · 持续开发

面向 Unitree G1 的自包含 Sim2Real 推理与评估流水线，统一支持 ACT、SmolVLA 和 π0.5 的 28-DoF 双臂与灵巧手控制。项目覆盖纯仿真、纯真机、仿真驱真机和真机驱仿真四种模式，并提供带速度限制、跟踪误差检测、渐进权重加载和安全回位的实机控制桥。

**sim2real_piper** · 私有仓库 · 持续开发

面向 Piper-X 六轴机械臂的真机数据采集、回放与策略部署工作区，统一管理 ROS 2 Humble / CAN 控制服务、主视角与腕部双 Orbbec DaBai DC1 RGB-D、rosbag2 / H.265 / LeRobot v3 数据链路、安全轨迹回放和 π0.5 实时推理。

[**LEAP-DexRetarget**](https://github.com/JamesRaoXiaoJian/LEAP-DexRetarget) · Phase 0

面向 LEAP Hand 的人手运动重定向与模仿学习项目，计划打通“人手关键点 → dex-retargeting → 关节目标 → 仿真回放 → episode 数据 → ACT 训练与评估”的完整闭环。当前已完成 MuJoCo、CUDA/PyTorch、LEAP/Allegro 模型和 vector retargeting 关节映射的基础环境验证。

## 主页 Pinned 仓库

### Robotics & Embodied AI

[**TransVTLA-RealDataCollect**](https://github.com/JamesRaoXiaoJian/TransVTLA-RealDataCollect)

面向真机机械臂实验的多模态数据工程工具链，覆盖双 RealSense RGB-D 采集、触觉/压力传感、机械臂与夹爪状态记录、离线回放、数据审计、清洗、任务划分和 RLDS/TFDS 导出。

[**G1 Motion Player**](https://github.com/JamesRaoXiaoJian/g1_motion_player)

Unitree G1 CSV 动作回放工具，提供 ROS 2 Foxy Docker、原生 Unitree SDK2 C++ 和 FastAPI 三种入口。ROS 2 执行链加入状态新鲜度、关节跟踪误差、重复 publisher 与控制周期超时等运行时安全监测，并保留 nearest-window 入口/退出选择和速度钳位等过渡策略。

[**g1_mujoco_sim**](https://github.com/JamesRaoXiaoJian/g1_mujoco_sim)

轻量级 Unitree G1 MuJoCo 动作预览工具，用于在真机执行前离线回放 LAFAN1 retargeting CSV 关节轨迹，支持位置控制、PD 力矩模式、倍速、循环和下肢锁定。

[**unitree_mujoco**](https://github.com/JamesRaoXiaoJian/unitree_mujoco)

基于 MuJoCo 与 Unitree SDK2 的仿真环境，用于低层控制验证和 sim-to-real 开发。这个 fork 补充了 G1 低层仿真、`rt/secondary_imu`、`rt/arm_sdk` weight 机制和 G1 关键帧播放工具。

### Multimodal AI & Interactive Systems

[**SafeSentinel**](https://github.com/JamesRaoXiaoJian/safesentinel)

一个面向校园安全场景的智能多模态 AI 系统，结合人员检测、多目标跟踪、动作识别和视觉语言风险分析。技术栈包括 YOLO11、BoT-SORT/ByteTrack、S3D 动作识别、PyTorch Lightning 和 Qwen 风格 VLM 分析。

[**SV_Soul**](https://github.com/JamesRaoXiaoJian/SV_Soul)

面向《星露谷物语》的 AI NPC 系统，围绕角色人设、长期记忆、实时游戏上下文和自然对话体验构建。

## 其他项目

**TransVTLA**

一个持续推进中的透明/触觉 Vision-Language-Action 研究项目。项目探索如何将 2D 图像、3D 点云、触觉信号、机器人状态和语言指令统一融合到机器人动作模型中，涉及 MLA/OpenVLA 风格模型改造、扩散/自回归动作预测、多模态对齐、未来感知预测，以及面向训练的数据管线。

### Web & Practical Tools

[**FRPWatch**](https://github.com/JamesRaoXiaoJian/FRPWatch)

一个轻量级 FRP 节点监控工具，定期检查代理节点在线状态，并在节点离线时发送邮件告警。

[**Flexible-Electronics-Cup**](https://github.com/JamesRaoXiaoJian/Flexible-Electronics-Cup)

柔性电子杯官网界面项目。

[**volunteer-hours-ranking**](https://github.com/JamesRaoXiaoJian/volunteer-hours-ranking)

一个用于志愿时长排行和展示的小型 JavaScript 项目。

## 技术栈

**编程语言**

Python · C++ · C# · JavaScript · HTML/CSS

**AI & Robotics**

PyTorch · ACT · SmolVLA · π0.5 · OpenVLA/MLA · MuJoCo · Isaac Lab/Isaac Sim · LeRobot · dex-retargeting · RealSense · Orbbec RGB-D · RLDS/TFDS · YOLO

**工程工具**

ROS 2 · Unitree SDK2 · DDS · ZMQ · SocketCAN · rosbag2 · FastAPI · Docker · CMake · Linux · Git · data pipelines · model training/evaluation scripts

## 联系

- GitHub: [@JamesRaoXiaoJian](https://github.com/JamesRaoXiaoJian)
- Location: Shenzhen, China

## GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=JamesRaoXiaoJian&show_icons=true&hide_border=true" alt="JamesRaoXiaoJian's GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JamesRaoXiaoJian&layout=compact&hide_border=true" alt="Top languages" />
</p>
