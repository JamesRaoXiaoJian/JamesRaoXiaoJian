# James | Rao Xiaojian

<p align="center">
  <a href="README.md">中文</a> · <a href="README_EN.md">English</a>
</p>

Hi, I'm James. My Chinese name is Rao Xiaojian (饶小建), and I am studying Computer Science and Technology at Shenzhen University.

I work on robotics, embodied AI, and multimodal perception, with a particular interest in deploying policy models reliably on real robots. My recent work focuses on Unitree G1, Piper-X, dexterous-hand motion retargeting, real-robot data engineering, and simulation-to-real evaluation of Vision-Language-Action policies.

`Human motion / RGB-D / robot state → retargeting and datasets → ACT / SmolVLA / π0.5 → simulation evaluation → real Piper-X / Unitree G1`

## Current Focus

- 28-DoF policy inference and safety-aware real-robot evaluation for Unitree G1 arms and dexterous hands
- Dual-RGB-D data collection, safe replay, LeRobot v3 conversion, and real-time π0.5 inference for Piper-X
- Human-motion retargeting and imitation learning for LEAP Hand and Allegro Hand
- Real-world multimodal data collection with RGB-D, tactile/pressure, robot state, and gripper signals
- Sim-to-real tooling built around MuJoCo, Isaac Lab, ROS 2, and Unitree SDK2

## Recent Projects

[**sim2real_g1**](https://github.com/JamesRaoXiaoJian/sim2real_g1) · Active development

A self-contained Sim2Real inference and evaluation pipeline for Unitree G1, with unified 28-DoF arm and dexterous-hand control for ACT, SmolVLA, and π0.5. It supports simulation-only, real-only, simulation-to-real, and real-to-simulation modes, backed by a safety bridge with velocity limits, tracking-error checks, gradual weight handoff, and controlled return-to-ready behavior.

**sim2real_piper** · Private repository · Active development

A real-robot data collection, replay, and policy-deployment workspace for the six-axis Piper-X arm. It unifies ROS 2 Humble and CAN control, main-view and wrist-mounted Orbbec DaBai DC1 RGB-D cameras, rosbag2/H.265/LeRobot v3 data pipelines, safety-checked trajectory replay, and real-time π0.5 inference.

[**LEAP-DexRetarget**](https://github.com/JamesRaoXiaoJian/LEAP-DexRetarget) · Phase 0

A human-hand motion retargeting and imitation-learning project for LEAP Hand. The planned pipeline spans human keypoints, dex-retargeting, joint targets, simulation replay, episode data, and ACT training and evaluation. Phase 0 has verified MuJoCo, CUDA/PyTorch, the LEAP/Allegro models, and vector-retargeting joint mappings.

## Pinned Repositories

### Robotics & Embodied AI

[**TransVTLA-RealDataCollect**](https://github.com/JamesRaoXiaoJian/TransVTLA-RealDataCollect)

A real-robot multimodal data engineering toolkit for robotic arm experiments. It covers dual RealSense RGB-D capture, tactile/pressure sensing, robot and gripper state logging, offline replay, dataset auditing, cleaning, task splitting, and RLDS/TFDS export.

[**G1 Motion Player**](https://github.com/JamesRaoXiaoJian/g1_motion_player)

A Unitree G1 CSV motion replay tool with three entry points: ROS 2 Foxy in Docker, native Unitree SDK2 C++, and FastAPI. The ROS 2 path adds runtime checks for state freshness, joint tracking error, duplicate publishers, and control-loop timeouts, while retaining nearest-window entry/exit selection and velocity-clamped transitions.

[**g1_mujoco_sim**](https://github.com/JamesRaoXiaoJian/g1_mujoco_sim)

A lightweight Unitree G1 MuJoCo motion preview tool for replaying LAFAN1-retargeted CSV joint trajectories before real-robot execution, with position replay, PD torque mode, speed scaling, looping, and lower-body locking.

[**unitree_mujoco**](https://github.com/JamesRaoXiaoJian/unitree_mujoco)

A MuJoCo + Unitree SDK2 simulation environment for low-level robot control verification and sim-to-real development. This fork adds G1 low-level simulation, `rt/secondary_imu`, `rt/arm_sdk` weight blending, and G1 keyframe playback utilities.

### Multimodal AI & Interactive Systems

[**SafeSentinel**](https://github.com/JamesRaoXiaoJian/safesentinel)

An intelligent campus safety monitoring system combining person detection, multi-object tracking, action recognition, and vision-language risk analysis. The stack includes YOLO11, BoT-SORT/ByteTrack, S3D action recognition, PyTorch Lightning, and Qwen-style VLM analysis.

[**SV_Soul**](https://github.com/JamesRaoXiaoJian/SV_Soul)

An AI-powered NPC system for Stardew Valley, designed around character personas, persistent memory, real-time game context, and more natural in-game dialogue.

## Other Work

**TransVTLA**

An ongoing research project for transparent and tactile Vision-Language-Action learning. It explores how 2D vision, 3D point clouds, tactile signals, robot states, and language instructions can be fused into a unified action model for robotic manipulation, including MLA/OpenVLA-style model adaptation, diffusion and autoregressive action prediction, multimodal alignment, future perception prediction, and training data pipelines.

### Web & Practical Tools

[**FRPWatch**](https://github.com/JamesRaoXiaoJian/FRPWatch)

A lightweight monitoring tool for FRP proxy nodes, with regular status checks and email alerts when a node goes offline.

[**Flexible-Electronics-Cup**](https://github.com/JamesRaoXiaoJian/Flexible-Electronics-Cup)

A website interface for the Flexible Electronics Cup.

[**volunteer-hours-ranking**](https://github.com/JamesRaoXiaoJian/volunteer-hours-ranking)

A small JavaScript project for volunteer-hours ranking and display.

## Tech Stack

**Languages**

Python · C++ · C# · JavaScript · HTML/CSS

**AI & Robotics**

PyTorch · ACT · SmolVLA · π0.5 · OpenVLA/MLA · MuJoCo · Isaac Lab/Isaac Sim · LeRobot · dex-retargeting · RealSense · Orbbec RGB-D · RLDS/TFDS · YOLO

**Engineering**

ROS 2 · Unitree SDK2 · DDS · ZMQ · SocketCAN · rosbag2 · FastAPI · Docker · CMake · Linux · Git · data pipelines · model training/evaluation scripts

## Connect

- GitHub: [@JamesRaoXiaoJian](https://github.com/JamesRaoXiaoJian)
- Location: Shenzhen, China

## GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=JamesRaoXiaoJian&show_icons=true&hide_border=true" alt="JamesRaoXiaoJian's GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JamesRaoXiaoJian&layout=compact&hide_border=true" alt="Top languages" />
</p>
