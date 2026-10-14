<div align="center">

<img src="assets/banner.svg" alt="Awesome Robotics Deployment Banner" width="100%" />

# 🤖 Awesome Robotics Deployment

### 🚀 Top SaaS Platforms & Open-Source Fleet Orchestration Ecosystem

[![Awesome](https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)
<a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
<a href="https://github.com/ishandutta2007/Awesome-Robotics-Deployment/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Robotics-Deployment?style=flat-square&color=gold" alt="GitHub Stars"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Robotics-Deployment/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Robotics-Deployment?style=flat-square&color=blue" alt="GitHub Forks"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Robotics-Deployment/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/></a>
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

**A community-curated collection of commercial SaaS platforms, RobOps infrastructure, and open-source projects for deploying, monitoring, and orchestrating heterogeneous robot fleets at scale.**

*Focusing on Fleet Orchestration, Edge Deployment, Robot Operations (RobOps), OTA Updates & Real-Time Observability.*

---

</div>

## 📑 Table of Contents

- [🌐 Overview](#-overview)
- [📈 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS & Hosted Fleet Platforms](#-saas--hosted-fleet-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🏗️ Recommended Architectural Blueprints](#️-recommended-architectural-blueprints)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Community](#-support--community)
- [⭐ Star History](#-star-history)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🌐 Overview

Deploying robotics in production requires vastly different infrastructure than traditional web applications. Robotics teams face harsh edge computing environments, intermittent connectivity, hardware-level safety constraints, heterogeneous device fleets (AMRs, quadrupeds, robotic arms, drones), and massive sensor bandwidth (LiDAR, point clouds, video streams). 

This repository tracks the leading **SaaS platforms** and **open-source ecosystems** that solve these challenges — handling:
- 🛰️ **Fleet Orchestration & Traffic Scheduling:** Multi-robot coordination across facilities, dynamic task assignment, and obstacle conflict management.
- ⚡ **Robot Operations (RobOps) & Diagnostics:** Remote teleoperation, health telemetry, diagnostics, and incident response.
- 🔄 **Edge Deployment & OTA Runtime:** Containerized Over-the-Air updates, firmware rollouts, and deterministic offline autonomy.
- 📊 **Multimodal Observability:** Time-series telemetry, MCAP sensor logs, rosbag capture, and Grafana-based monitoring.

---

## 📈 Sector Overview & Market Dynamics

The dedicated **robot fleet management and RobOps software market** is estimated at **$1.6B to $2.1B** in 2025–2026 and is projected to reach **$2.9B+ by 2027**, growing at a rapid CAGR of **~18%** within the broader **$20B+ logistics and autonomous robotics deployment ecosystem**. 

The sector is **heavily fragmented** rather than a winner-take-all market. Modern enterprise facilities deploy diverse, multi-vendor fleets combining AMRs, robotic arms, quadrupeds, and AGVs across competing hardware OEMs (such as KUKA, Boston Dynamics, Clearpath, Addverb, and Omron). Consequently, deployment orchestration requires hardware-agnostic middleware, open interoperability standards (such as ROS 2 and Open-RMF), and hybrid edge-to-cloud architectures, preventing single-vendor monopolization and fueling a vibrant ecosystem of specialized SaaS and self-hosted solutions.

---

## 🏢 SaaS & Hosted Fleet Platforms

The table below lists the category-leading commercial SaaS platforms for robot operations, fleet management, and edge deployment, sorted by **Company Size / Valuation (descending)**:

| Platform / Product | Company Size & Valuation | Starting Pricing Tier | Free Tier Limits | Key Focus & Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[DroneDeploy (Ground / Rocos)](https://www.dronedeploy.com/)** | **Valuation: ~$500M+**<br>• Total Funding: $157M+<br>• ARR: ~$55M+ | **$159 / month**<br>*(Ag Lite / Core annual plan; Ground Robotics fleet starts at ~$250/robot/mo)* | **14-day free trial**<br>• Full platform & Ground fleet features<br>• Up to 10 project uploads/maps<br>• No credit card required | Unified aerial drone and ground robot fleet orchestration (Spot quadrupeds, AMRs, 360 cameras), autonomous reality capture, site intelligence, and remote inspection. |
| **[Apex.AI](https://www.apex.ai/)** | **Valuation: ~$200M**<br>• Total Funding: $75M<br>• Est. Revenue: ~$12M+ | **~$1,500 / month**<br>*(Developer seat & evaluation tier license)* | **30-day evaluation trial**<br>• Access to Apex.OS & Apex.Grace SDKs<br>• Simulation testing for up to 3 engineers<br>• Technical support onboarding | Functional safety-certified (ISO 26262 ASIL D) robotics middleware and automotive operating system based on ROS 2 for mission-critical software-defined vehicles and autonomous systems. |
| **[Foxglove](https://foxglove.dev/)** | **Valuation: ~$180M**<br>• Total Funding: $58.7M<br>• ARR: ~$4M+ | **$20 / month**<br>*(Pro Plan: 3 dev seats, 1 TB cloud storage; unlimited free basic seats)* | **Free forever ($0/mo)**<br>• 3 developer seats<br>• 10 GB cloud storage<br>• 5 connected fleet devices | Robotics data platform and visualization suite; centralizes temporal multi-modal telemetry (LiDAR, point clouds, images, ROS/ROS 2 logs), MCAP recording, and remote debugging. |
| **[SVT Robotics](https://svtrobotics.com/)** | **Valuation: ~$100M**<br>• Total Funding: $36.5M<br>• Est. Revenue: ~$9M+ | **~$1,250 / month**<br>*(SOFTBOT Connector subscription per site)* | **30-day guided pilot trial**<br>• Virtual SOFTBOT Connector Studio access<br>• Simulation integration sandbox for 1 site<br>• Pre-deployment consultation | Enterprise Integration Platform-as-a-Service (iPaaS) connecting warehouse management systems (WMS, ERP) with heterogeneous AMR fleets and automated storage retrieval systems (ASRS). |
| **[RGo Robotics](https://www.rgorobotics.com/)** | **Valuation: ~$75M**<br>• Total Funding: $21.5M<br>• $10M+ OEM Design Wins | **~$850 / month**<br>*(Evaluation development kit & software license)* | **30-day OEM evaluation trial**<br>• Perception Engine SDK & runtime<br>• Virtual robot simulation testing<br>• Validated for up to 2 evaluation units | AI-powered artificial perception engine for mobile robots and AGVs; provides centimeter-level indoor/outdoor localization, sensor fusion, and plug-and-play perception hardware reference designs. |
| **[Formant](https://formant.io/)** | **Valuation: ~$60M**<br>• Total Funding: $45M<br>• Est. Revenue: ~$6M+ | **$0 / month** *(Developer)*<br>**~$250 / robot / month** *(Commercial fleet)* | **Free forever ($0/mo)**<br>• 1 developer device<br>• Live ROS telemetry streaming<br>• Full remote teleoperation & SSH | Cloud RobOps platform providing multi-device telemetry dashboards, live video streaming, low-latency teleoperation, bulk device provisioning, custom alerting, and uptime analytics. |
| **[InOrbit](https://www.inorbit.ai/)** | **Valuation: ~$37M**<br>• Total Funding: $12.75M<br>• Est. Revenue: ~$3M+ | **$0 / month** *(Free Edition)*<br>**$50 / robot / month** *(Standard Edition based on MAR)* | **Free forever ($0/mo)**<br>• Unlimited connected robots<br>• Core InOrbit Agent & diagnostics<br>• Basic 2D map tracking & incidents | Hardware-agnostic robot operations (RobOps) platform supporting ROS 1, ROS 2, and custom fleets; features adaptive diagnostics, Time Capsule incident playback, and Open-RMF traffic bridges. |
| **[MOV.AI](https://www.mov.ai/)** | **Valuation: ~$35M**<br>• Total Funding: $18.4M<br>• Est. Revenue: ~$4.7M+ | **~$500 / robot / month**<br>*(Robotics Engine Platform licensing)* | **30-day developer evaluation**<br>• Full MOV.AI Flow visual IDE access<br>• AMR navigation & fleet simulation<br>• 1 virtual AMR deployment instance | End-to-end Robotics Engine Platform for Autonomous Mobile Robots (AMRs); visual ROS-based drag-and-drop development IDE, simulation testing, and multi-robot fleet dispatching. |
| **[Freedom Robotics](https://www.freedomrobotics.ai/)** | **Valuation: ~$25M**<br>• Total Funding: $17M<br>• Est. Revenue: ~$2M+ | **$75 / robot / month**<br>*(Standard Tier starting rate)* | **14-day full-featured trial**<br>• Up to 3 connected robots<br>• Real-time teleoperation & controls<br>• Sensor stream recording & alerts | Edge agent and cloud management platform for remote robot control, real-time video streaming, health monitoring, and automated alerts for autonomous systems. |
| **[Cogniteam (Nimbus)](https://www.cogniteam.com/)** | **Valuation: ~$20M**<br>• Total Funding: $9.9M<br>• Est. Revenue: ~$3.8M+ | **$5 / user / month** *(Starter)*<br>**$30 / robot / month** *(Device Agent)* | **14-day free trial**<br>• Full Nimbus cloud workspace access<br>• Simulation package execution<br>• Up to 2 connected test devices | Low-code cloud robotics development and fleet deployment suite; features drag-and-drop ROS/ROS 2 component blocks, containerized edge deployment, and cloud simulation. |

---

## 💻 Open-Source GitHub Projects

Open-source tooling empowers robotics teams to build custom fleet management, self-host operations, maintain absolute data ownership, and avoid proprietary vendor lock-in.

The list below features the top active open-source robotics deployment and infrastructure repositories, sorted by **GitHub Stars (descending)**:

1. **[LeRobot](https://github.com/huggingface/lerobot)** [![GitHub stars](https://img.shields.io/github/stars/huggingface/lerobot?style=social&color=white)](https://github.com/huggingface/lerobot/stargazers)  
   Hugging Face's state-of-the-art machine learning library for real-world robotics in PyTorch. Includes pretrained models, standardized imitation learning datasets, hardware-accelerated training utilities, and production pipelines for deploying Vision-Language-Action (VLA) models on real edge robots.

2. **[Autoware](https://github.com/autowarefoundation/autoware)** [![GitHub stars](https://img.shields.io/github/stars/autowarefoundation/autoware?style=social&color=white)](https://github.com/autowarefoundation/autoware/stargazers)  
   The world's leading open-source software stack for autonomous driving and mobile robot fleet deployment. Built natively on ROS 2 with complete, production-ready modules for high-precision 3D localization, perception, path planning, and vehicle drive-by-wire control.

3. **[KubeEdge](https://github.com/kubeedge/kubeedge)** [![GitHub stars](https://img.shields.io/github/stars/kubeedge/kubeedge?style=social&color=white)](https://github.com/kubeedge/kubeedge/stargazers)  
   CNCF incubating Kubernetes Native Edge Computing Framework. Extends native containerized orchestration to robotics edge devices, delivering bidirectional edge-cloud messaging, MQTT device twins, zero-downtime application deployment, and continuous offline autonomous operation during network dropouts.

4. **[ROS 2](https://github.com/ros2/ros2)** [![GitHub stars](https://img.shields.io/github/stars/ros2/ros2?style=social&color=white)](https://github.com/ros2/ros2/stargazers)  
   The industry-standard Robot Operating System middleware. Powers modern commercial robot fleets with DDS-based inter-process communication, real-time safety lifecycles, cross-platform hardware support (Linux, Windows, macOS, RTOS), and modular package deployment.

5. **[Nav2 (Navigation 2)](https://github.com/ros-navigation/navigation2)** [![GitHub stars](https://img.shields.io/github/stars/ros-navigation/navigation2?style=social&color=white)](https://github.com/ros-navigation/navigation2/stargazers)  
   The de facto autonomous navigation, path planning, and fleet execution framework for ROS 2. Enables Autonomous Mobile Robots (AMRs) to navigate dynamic warehouse, logistics, and hospital environments with sophisticated behavioral trees, costmap 2D/3D layers, and collision avoidance.

6. **[Dora (dora-rs)](https://github.com/dora-rs/dora)** [![GitHub stars](https://img.shields.io/github/stars/dora-rs/dora?style=social&color=white)](https://github.com/dora-rs/dora/stargazers)  
   Ultra-fast, low-latency robotics dataflow framework and distributed edge orchestrator written in Rust. Features zero-copy shared-memory transport and Apache Arrow columnar memory formats with polyglot node support across Rust, Python, C, and C++ for high-performance edge AI pipelines.

7. **[Zenoh](https://github.com/eclipse-zenoh/zenoh)** [![GitHub stars](https://img.shields.io/github/stars/eclipse-zenoh/zenoh?style=social&color=white)](https://github.com/eclipse-zenoh/zenoh/stargazers)  
   Zero-overhead pub/sub, shared memory, and distributed storage protocol purpose-built for robotics and edge computing. Delivers sub-microsecond latencies, native ROS 2 bridges (`rmw_zenoh`), and ultra-low bandwidth consumption across noisy industrial Wi-Fi and 5G connections.

8. **[Iceoryx](https://github.com/eclipse-iceoryx/iceoryx)** [![GitHub stars](https://img.shields.io/github/stars/eclipse-iceoryx/iceoryx?style=social&color=white)](https://github.com/eclipse-iceoryx/iceoryx/stargazers)  
   Eclipse Foundation's true zero-copy inter-process communication (IPC) middleware designed for safety-critical autonomous systems. Enables deterministic, zero-copy payload transmission for high-throughput robotic sensor deployments (high-res cameras, LiDAR, and radar).

9. **[Awesome Robotics](https://github.com/ahundt/awesome-robotics)** [![GitHub stars](https://img.shields.io/github/stars/ahundt/awesome-robotics?style=social&color=white)](https://github.com/ahundt/awesome-robotics/stargazers)  
   Extensive, established curated list of robotics software libraries, perception algorithms, simulators, learning resources, and academic tools across robotics domains.

10. **[open-balena](https://github.com/balena-io/open-balena)** [![GitHub stars](https://img.shields.io/github/stars/balena-io/open-balena?style=social&color=white)](https://github.com/balena-io/open-balena/stargazers)  
    Open-source platform for deploying and managing connected IoT and robotics edge devices. Enables container-based over-the-air (OTA) updates, secure remote SSH tunneling, environment variable management, and centralized fleet rollouts for embedded Linux robots.

11. **[Lichtblick](https://github.com/lichtblick-suite/lichtblick)** [![GitHub stars](https://img.shields.io/github/stars/lichtblick-suite/lichtblick?style=social&color=white)](https://github.com/lichtblick-suite/lichtblick/stargazers)  
    BMW-maintained open-source visualization and robotics data inspection suite for ROS and ROS 2. Provides desktop and web interfaces for inspecting real-time sensor streams, point clouds, TF transforms, and diagnostics.

12. **[MCAP](https://github.com/foxglove/mcap)** [![GitHub stars](https://img.shields.io/github/stars/foxglove/mcap?style=social&color=white)](https://github.com/foxglove/mcap/stargazers)  
    Modular, high-performance container file format for robotics and multimodal temporal data. Designed for zero-copy streaming, fast indexing, self-contained schemas (Protobuf, ROS msg, JSON Schema), and robust write-throughput on edge robot hardware without data corruption.

13. **[openTCS](https://github.com/openTCS/opentcs)** [![GitHub stars](https://img.shields.io/github/stars/openTCS/opentcs?style=social&color=white)](https://github.com/openTCS/opentcs/stargazers)  
    Open-source Transport Control System for coordinating fleets of automated guided vehicles (AGVs) and AMRs in factories and logistics facilities. Provides vehicle routing, collision-free traffic scheduling, order dispatching, and hardware communication abstractions.

14. **[Micro-ROS Arduino](https://github.com/micro-ROS/micro_ros_arduino)** [![GitHub stars](https://img.shields.io/github/stars/micro-ROS/micro_ros_arduino?style=social&color=white)](https://github.com/micro-ROS/micro_ros_arduino/stargazers)  
    Pre-compiled micro-ROS client library for microcontrollers (ESP32, Teensy, STM32, Arduino). Enables resource-constrained edge sensor nodes and motor controllers to participate natively as first-class ROS 2 nodes.

15. **[Open-RMF](https://github.com/open-rmf/rmf)** [![GitHub stars](https://img.shields.io/github/stars/open-rmf/rmf?style=social&color=white)](https://github.com/open-rmf/rmf/stargazers)  
    Open Robot Management Framework by Open Robotics. Standardized multi-fleet traffic scheduling, task allocation, building infrastructure integration (elevators, automatic doors), and vendor-neutral interoperability for fleets operating in shared spaces (airports, hospitals, warehouses).

16. **[Awesome Open Source Robots](https://github.com/stephane-caron/awesome-open-source-robots)** [![GitHub stars](https://img.shields.io/github/stars/stephane-caron/awesome-open-source-robots?style=social&color=white)](https://github.com/stephane-caron/awesome-open-source-robots/stargazers)  
    Comprehensive curated collection of open-source robot hardware, arms, mobile manipulators, quadrupeds, humanoids, and bipedal platforms with full mechanical blueprints and open firmware.

17. **[Micro-ROS Agent](https://github.com/micro-ROS/micro-ROS-Agent)** [![GitHub stars](https://img.shields.io/github/stars/micro-ROS/micro-ROS-Agent?style=social&color=white)](https://github.com/micro-ROS/micro-ROS-Agent/stargazers)  
    Middleware gateway bridging resource-constrained micro-ROS microcontrollers into standard ROS 2 DDS networks across Serial, UDP, and TCP edge interfaces.

18. **[Transitive](https://github.com/transitiverobotics/transitive)** [![GitHub stars](https://img.shields.io/github/stars/transitiverobotics/transitive?style=social&color=white)](https://github.com/transitiverobotics/transitive/stargazers)  
    Full-stack open-source robotics framework with fine-grained access control. Integrates ClickHouse for historical time-series data, Grafana for visual dashboards, Alertmanager for alerting, and full-stack reactive device management on self-hosted Docker Compose.

19. **[Foxglove WebSocket Protocol](https://github.com/foxglove/ws-protocol)** [![GitHub stars](https://img.shields.io/github/stars/foxglove/ws-protocol?style=social&color=white)](https://github.com/foxglove/ws-protocol/stargazers)  
    Lightweight, high-speed binary WebSocket communication protocol for streaming ROS 1, ROS 2, and custom robot telemetry directly to web dashboards, visualization apps, and operator teleoperation clients.

20. **[Open-RAIL](https://github.com/CMCC-TAO/open-rail)** [![GitHub stars](https://img.shields.io/github/stars/CMCC-TAO/open-rail?style=social&color=white)](https://github.com/CMCC-TAO/open-rail/stargazers)  
    Middleware from China Mobile linking Vision-Language-Action (VLA) and World-Action Models (WAM) to physical robot actuators via a 3-thread asynchronous pipeline (observation, inference, control) with real-time online smoothing.

21. **[SONNY OS](https://github.com/JackTrainer/Sonny)** [![GitHub stars](https://img.shields.io/github/stars/JackTrainer/Sonny?style=social&color=white)](https://github.com/JackTrainer/Sonny/stargazers)  
    Ultra-lightweight microkernel built in Rust and Zenoh for robotic hardware abstraction. Features WebAssembly (WASM) sandboxing for hot-swappable skill execution and real-time hardware watchdog monitors.

22. **[Trillium](https://github.com/RobotnikAutomation/trillium)** [![GitHub stars](https://img.shields.io/github/stars/RobotnikAutomation/trillium?style=social&color=white)](https://github.com/RobotnikAutomation/trillium/stargazers)  
    Free, open-source web and desktop robotics visualization and control app by Robotnik. Fork of Foxglove Studio v1.87.0 featuring a 40% smaller web app and 23% smaller desktop binary footprint.

### 🌟 Specialized & Emerging RobOps Frameworks

- **[OpenRobOps (ORO)](https://www.inorbit.ai/)** — InOrbit's open-source robot operations and fleet management layer, designed to provide a self-hostable fleet manager for ROS developers and native Open-RMF coordination.
- **[NexusOS](https://pypi.org/project/nexusos-robotics/)** — Universal OS and fleet middleware for heterogeneous robots, providing zero-dependency hardware abstraction, Protobuf/gRPC transports, and glassmorphic 2D pose teleoperation dashboards.
- **[Canonical Observability Stack (COS)](https://ubuntu.com/blog/roscon-2025)** — Fully open-source observability infrastructure for ROS 2 devices using Ubuntu, Grafana, Prometheus, and Loki for remote ros2bag logging, device telemetry, and automated fleet alerts.

---

## 🏗️ Recommended Architectural Blueprints

For engineering teams building a robust, self-hosted robotics deployment platform, we recommend composing the following proven open-source stack:

```mermaid
flowchart TD
    subgraph CloudLayer["☁️ Cloud & Fleet Management"]
        ORMF["Open-RMF / openTCS\n(Multi-Fleet Traffic & Dispatch)"]
        COS["Canonical Observability Stack\n(Grafana + Prometheus + Loki)"]
        BALENA["open-balena\n(OTA Updates & Device Management)"]
    end

    subgraph EdgeLayer["🤖 Robot Edge Runtime"]
        K8S["KubeEdge / MicroK8s\n(Container Runtime)"]
        ROS2["ROS 2 + Nav2\n(Navigation & Core Autonomy)"]
        DORA["Dora / Zenoh\n(Low-Latency Edge AI & Zero-Copy IPC)"]
        MICROROS["Micro-ROS Agent\n(Actuator & Sensor Bridging)"]
    end

    subgraph OperatorLayer["🖥️ Operations & Visualization"]
        VIS["Foxglove / Trillium / Lichtblick\n(Real-Time Studio & Teleop)"]
    end

    CloudLayer <--> |"Zenoh / WebSockets"| EdgeLayer
    EdgeLayer <--> |"MCAP / WebSockets"| OperatorLayer
```

- **Fleet Orchestration:** Use **Open-RMF** or **openTCS** for vendor-neutral traffic scheduling and building automation (elevators/doors).
- **Edge Deployment & OTA:** Use **open-balena** or **KubeEdge** for containerized OTA releases and fail-safe firmware rollouts.
- **Communication & IPC:** Use **Zenoh** for low-bandwidth edge-to-cloud telemetry and **Iceoryx** for on-device zero-copy sensor pipelines.
- **Observability & Diagnostics:** Combine **MCAP** file recording with **Canonical Observability Stack** (Grafana/Loki/Prometheus) and **Foxglove/Lichtblick/Trillium** for visualization.

---

## 🤝 How to Contribute

Contributions from the robotics community are warmly welcome!

1. 🍴 **Fork the repository**.
2. 🌿 **Create a feature branch**: `git checkout -b add-tool-name`.
3. 📝 **Add or update entries**: Follow the established table or list format with factual, neutral descriptions, links, and pricing details.
4. 📬 **Submit a Pull Request**: Include a brief rationale and links to official documentation or source code.

Please ensure all product details remain factual, concise, and linked to canonical sources.

---

## 💖 Support & Community

Thank you for visiting **Awesome Robotics Deployment**! If you find this curated ecosystem directory helpful for your robotics architecture, RobOps initiatives, or research:

- ⭐ **Star this repository** to help other robotics engineers and operators discover it.
- 🍴 **Fork and contribute** your favorite robotics deployment tools and updates.
- 📢 **Share it** across robotics forums, ROS meetups, and LinkedIn.
- ☕ **Support the maintainer**: If you would like to support ongoing maintenance and curation of open-source robotics resources, please consider buying a coffee via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007). Your support is greatly appreciated!

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Robotics-Deployment&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Robotics-Deployment&type=date&legend=top-left)

---

## ⚖️ Disclaimer

- This is an independent, community-curated list and does not constitute an endorsement of any commercial platform or open-source software.
- Production robotics deployments involve safety-critical operations, functional safety standards (e.g., ISO 13849, ISO 26262), and regulatory compliance. Always test deployment, fail-safe, and OTA mechanisms thoroughly in hardware-in-the-loop (HIL) environments prior to live facility operation.
- Self-hosted open-source software requires dedicated infrastructure management, hardening, and network security.
