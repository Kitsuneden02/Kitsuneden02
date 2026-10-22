<div align="center">

  # Sebastián Herrera Torres
  **こんにちは！チリ出身のロボティクス・ソフトウェアエンジニア、セバスティアン・エレラです。**  
  *Electrical Engineer (U. de Chile, Highest Honors) · Software Engineer I @ Grupo Lagos*

  [![Email](https://img.shields.io/badge/Email-sebastian.herrera.t%40ug.uchile.cl-0f172a?style=flat-square&logo=gmail&logoColor=38bdf8)](mailto:sebastian.herrera.t@ug.uchile.cl)
  [![Location](https://img.shields.io/badge/Location-Santiago%2C%20Chile-0f172a?style=flat-square&logo=googlemaps&logoColor=2dd4bf)](https://github.com/Kitsuneden02)
  [![Education](https://img.shields.io/badge/U.%20de%20Chile-Electrical%20Engineering%20(Highest%20Honors)-0f172a?style=flat-square&logo=academia&logoColor=38bdf8)](https://fcfm.uchile.cl/)
  [![Languages](https://img.shields.io/badge/Languages-ES%20(Native)%20%C2%B7%20EN%20(B2%20TOEFL%20597)%20%C2%B7%20JA%20(JLPT%20N5)-0f172a?style=flat-square&logo=translate&logoColor=818cf8)](https://github.com/Kitsuneden02)
</div>

---

### About Me

I am **Sebastián Herrera**, an Electrical Engineer (graduated with **Highest Honors, 6.7/7.0**, and a **7.0/7.0** engineering thesis grade from the **University of Chile**) and Software Engineer based in Santiago, Chile.

My core work bridges **robotics perception, state estimation, and production software engineering**. Over the past years, I have designed and deployed multi-sensor fusion pipelines and ROS 2 drivers for underwater remotely operated vehicles (ROVs) in real hydroelectric infrastructure inspections, while also building full-stack software systems.

- **Current Role:** Software Engineer I at **Grupo Lagos** (full-stack Python/React architecture and mathematical optimization systems).
- **Previous R&D Experience:** Robotics Software Engineer & Researcher at **Maquintel** (16 months developing ROV software architectures, acoustic 3D mapping pipelines, and field operations in Guatemala).
- **Research Focus:** Lightweight multi-sensor fusion (LiDAR-Camera-IMU and acoustic-inertial), state estimation (EKF/UKF, factor graphs), 3D point cloud registration, and SLAM for infrastructure inspection.

---

### Featured Research & Robotics Engineering

#### Real-Time 3D Underwater Tunnel Reconstruction via Multi-Sensor Fusion *(Engineering Thesis, Oct 2026)*
> **Title:** *Algorithms for Point Cloud Fusion and Registration in Underwater Environments Based on Low-Sampling-Rate Acoustic Sensors*  
> **Institution:** Department of Electrical Engineering, Universidad de Chile · **Grade:** 7.0 / 7.0 (Maximum Distinction)

- **Architecture:** Asynchronous multi-sensor state estimation and 3D registration pipeline in **ROS 2 Jazzy** and **Gazebo Harmonic**, fusing a **WaterLinked A50 DVL**, **dual IMUs**, a **barometric depth sensor**, and a mechanical **Imagenex 831A profiling sonar** using **EKF/UKF** filters and **Open3D**.
- **Key Results:** Engineered a **3-tier contingency state estimation architecture** that bounds localization drift during DVL dropouts and corrects helical scan distortion, achieving a **20x increase in 3D profiling density** and detecting **2 previously unknown structural anomalies** during field deployment at the Renace Hydroelectric Project (Guatemala).
- **Custom ROS 2 Driver:** Developed a standalone **ROS 2 Jazzy (`rclpy`)** driver for the **Imagenex 831A** profiling sonar over RS-485/Serial (`115200` baud) with vectorized `sensor_msgs/PointCloud2` publishing and runtime `rqt` parameter reconfiguration.

---

### Selected Public Repositories

| Repository | Domain | Tech Stack | Highlights |
| :--- | :--- | :--- | :--- |
| **[`el7009_2d_exploration`](https://github.com/Kitsuneden02/el7009_2d_exploration)** | Mobile Robotics & Autonomous Exploration | `ROS 2 Jazzy` `Python` `Nav2` `slam_toolbox` `Gazebo` | Frontier-based autonomous exploration and 2D SLAM in unknown environments for differential-drive robots. |
| **[`liquiverde`](https://github.com/Kitsuneden02/liquiverde)** | Full-Stack & Mathematical Optimization | `Python` `FastAPI` `React` `Docker` `Pytest` | Multi-objective knapsack optimization engine and lifecycle sustainability scoring platform with 44 automated tests and Open Food Facts integration. |
| **[`gia-trainer`](https://github.com/Kitsuneden02/gia-trainer)** | Web Engineering & Cognitive Simulation | `JavaScript` `HTML5` `CSS3` | Open-source cognitive speed and psychometric assessment simulator built with zero-dependency vanilla web technologies. |

---

### Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **Robotics & Simulation** | ![ROS 2](https://img.shields.io/badge/ROS_2_Jazzy-22314E?style=flat-square&logo=ros&logoColor=white) ![ROS 1](https://img.shields.io/badge/ROS_1-22314E?style=flat-square&logo=ros&logoColor=white) ![Gazebo](https://img.shields.io/badge/Gazebo_Harmonic-FF6600?style=flat-square&logo=gazebo&logoColor=white) ![Nav2](https://img.shields.io/badge/Nav2_%2F_slam__toolbox-1e293b?style=flat-square) ![RViz2](https://img.shields.io/badge/RViz2-0f172a?style=flat-square) |
| **Perception & State Estimation** | ![Open3D](https://img.shields.io/badge/Open3D-0f172a?style=flat-square) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![EKF / UKF](https://img.shields.io/badge/EKF_%2F_UKF_Sensor_Fusion-0f766e?style=flat-square) ![3D Point Clouds](https://img.shields.io/badge/PointCloud2_%2F_3D_Registration-0369a1?style=flat-square) |
| **Languages & Frameworks** | ![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![PyQt5](https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) |
| **Systems, Embedded & DevOps** | ![Ubuntu](https://img.shields.io/badge/Ubuntu_24.04_%2F_WSL2-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |

---

### Experience & Academic Trajectory

| Period | Role & Organization | Key Focus |
| :--- | :--- | :--- |
| **Oct 2026 - Present** | **Software Engineer I** · *Grupo Lagos* | Full-stack engineering, backend optimization services, and scalable web architectures. |
| **2025 - Sep 2026** | **Robotics Software Engineer & Researcher** · *Maquintel* | ROV software architecture, multi-sensor fusion (DVL/IMU/Sonar), 3D point cloud reconstruction, and field inspections in Guatemala. |
| **2022 - 2025** | **Teaching Assistant & Robotics Researcher** · *Universidad de Chile (FCFM)* | TA for *EL7009 Mobile Robotics* and *Computational Intelligence & Robotics Lab*. Member of **UChile Homebreakers** (RoboCup@Home). |
| **2018 - 2025** | **International Robotics Competitions & STEM Mentorship** | Competitor in **World Robot Summit (Tokyo, 2018)**, **Robo-One (Yokohama, 2023)**, and China (2025). Robotics mentor for high-school teams (RoboCup Junior Rescue Line & RoboRAVE). |
