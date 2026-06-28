# Mandar Deshmukh

### Robotics Software Engineer • Computer Vision • Machine Learning • Embodied AI

## About Me

I'm an M.S. Computer Science graduate from the University of Colorado Boulder, where I worked at the HIRO Lab building full-stack robotics software — perception, control, and learning systems — for a 14-DoF robotic platform. My work sits at the intersection of robotics, computer vision, and machine learning: systems that perceive, reason about, and act in the physical world.

Currently building real-time robotics infrastructure in C++ and Python — from production-grade ROS2 middleware to vision-based teleoperation systems for robot learning data collection.

Actively seeking full-time roles in Robotics Software Engineering, ML Engineering, and Autonomous Systems. Available to join June 2026.

## What I Work On

- **Robot learning & manipulation:** Visuomotor policy training via imitation learning and reinforcement learning, deployed on real 14-DoF hardware with sub-10ms inference latency (CUDA, TensorRT)
- **Real-time systems:** Production-grade ROS2 middleware in C++20 — lock-free data structures, custom real-time executors, POSIX scheduling
- **Perception & SLAM:** Visual SLAM, sensor fusion (camera, LiDAR, IMU), 3D object detection and tracking
- **Simulation & sim-to-real:** MuJoCo, Isaac Sim, Gazebo — environment design, domain randomization, and sim-to-real transfer validation

I'm interested in collaborating on robot learning, perception systems, and real-time robotics infrastructure.

## Tech Stack

**Languages:** Python · C++ (17/20) · Bash · SQL

**Robotics & Manipulation:** ROS2 · MoveIt 2 · ros2_control · URDF/Xacro · Inverse Kinematics · Sensor Fusion · Visual SLAM (ORB-SLAM3)

**Simulation:** MuJoCo · NVIDIA Isaac Sim · Gazebo · PyBullet · Sim-to-Real Transfer

**Computer Vision & ML:** PyTorch · TensorFlow · YOLOv8 · DeepSORT · Vision Transformers · Imitation Learning · Reinforcement Learning (PPO, SAC)

**Systems:** Lock-Free Data Structures · Real-Time Execution (SCHED_FIFO) · CUDA · TensorRT · gtest

**MLOps & Infrastructure:** Docker · MLflow · Weights & Biases · AWS · GCP · Git/CI-CD

## Featured Projects

**Custom Real-Time ROS2 Middleware (C++20)**
Production-grade real-time executor for ROS2 Humble — lock-free SPSC ring buffer, ABA-safe memory pool, POSIX SCHED_FIFO scheduling with CPU affinity. Benchmarked across three transport modes at up to 1kHz over 95,951 samples, achieving p99 scheduling jitter ≤11µs with zero missed deadlines. 29 gtest unit tests, GitHub Actions CI.

**Dual-Arm Hand Teleoperation System (ROS2 + MoveIt 2)**
Real-time dual-arm teleoperation using only a USB webcam — MediaPipe hand tracking with One Euro adaptive filtering, MoveIt 2 collision-aware inverse kinematics, and FollowJointTrajectory execution on ros2_control. Custom URDF/Xacro robot model built from scratch. Sub-50ms pixel-to-joint latency.

**Visual SLAM with Object-Aware Mapping**
Integrated ORB-SLAM3 with YOLOv8-seg for real-time semantic mapping and localization, achieving 3–5cm localization error at 18 FPS on KITTI and TUM datasets.

**3D Object Detection & Tracking for Autonomous Vehicles**
Real-time perception pipeline combining YOLOv8 and stereo vision, achieving 89.9% mAP on KITTI and 72.3% MOTA for multi-object tracking. Integrated NeRF-based synthetic data generation for robustness under varied conditions.

**RL Locomotion Control**
Trained a Soft Actor-Critic agent on MuJoCo HalfCheetah-v5, achieving mean reward 7,648 with 85%+ success rate over 1M timesteps. Deployed trained policy with sub-10ms GPU inference latency.

## Contact

[LinkedIn](https://www.linkedin.com/in/mandardeshmukh117) · MandarMahesh.Deshmukh@colorado.edu

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=Mandar117&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Mandar117&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---

[![](https://visitcount.itsvg.in/api?id=Mandar117&icon=0&color=0)](https://visitcount.itsvg.in)
