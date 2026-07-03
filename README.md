# James | 饶小建

<p align="center">
  <a href="README.md">中文</a> · <a href="README_EN.md">English</a>
</p>

你好，我是 James，中文名饶小建，目前就读于深圳大学计算机科学与技术专业。

我关注机器人、具身智能、多模态感知，以及把研究代码落到真实系统中的工程工具。近期工作主要围绕 Vision-Language-Action、真机多模态数据采集、Unitree G1 运动控制和 AI 应用开发展开。

## 当前关注

- 面向机器人操作的 Vision-Language-Action 模型
- RGB-D、触觉/压力、机械臂状态、夹爪状态等真机多模态数据采集与对齐
- Unitree G1 动作回放、MuJoCo 仿真和 sim-to-real 控制流程
- AI 工具、自动化脚本和交互式应用

## 主页 Pinned 仓库

### Robotics & Embodied AI

[**TransVTLA-RealDataCollect**](https://github.com/JamesRaoXiaoJian/TransVTLA-RealDataCollect)

面向真机机械臂实验的多模态数据工程工具链，覆盖双 RealSense RGB-D 采集、触觉/压力传感、机械臂与夹爪状态记录、离线回放、数据审计、清洗、任务划分和 RLDS/TFDS 导出。

[**G1 Motion Player**](https://github.com/JamesRaoXiaoJian/g1_motion_player)

Unitree G1 动作回放工具，围绕 CSV 动作执行链路构建。项目通过 Unitree SDK DDS 话题向 `rt/arm_sdk` 下发动作，提供 FastAPI 回放接口，并加入 nearest-window 入口/退出选择和速度钳位等过渡策略。

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

PyTorch · OpenVLA/MLA · MuJoCo · RLBench · RealSense · RLDS/TFDS · YOLO · Vision-Language Models

**工程工具**

FastAPI · CMake · Linux · Git · data pipelines · model training/evaluation scripts

## 联系

- GitHub: [@JamesRaoXiaoJian](https://github.com/JamesRaoXiaoJian)
- Location: Shenzhen, China

## GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=JamesRaoXiaoJian&show_icons=true&hide_border=true" alt="JamesRaoXiaoJian's GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JamesRaoXiaoJian&layout=compact&hide_border=true" alt="Top languages" />
</p>
