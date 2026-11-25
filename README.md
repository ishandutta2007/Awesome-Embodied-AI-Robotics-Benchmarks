# Awesome-Embodied-AI-Robotics-Benchmarks

<p align="center">

  <img src="./assets/banner.svg" alt="Top Embodied AI & Robotics Benchmarks" width="100%" />

</p>



<p align="center">

  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>

  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>

  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>

</p>



# 🤖 Top Embodied AI & Robotics Benchmarks



**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  

*Focused on Embodied AI Benchmarks, GPU-Accelerated Physics Simulators, Manipulation/Locomotion Suites & Vision-Language-Action (VLA) Evaluation*  

**Last updated: November 2026**



This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Embodied AI & Robotics Benchmarks**. These tools power high-speed GPU physics simulation, humanoid locomotion and dexterous manipulation evaluation, Vision-Language-Action (VLA) benchmark suites, household navigation challenges, and cloud robotics simulation fleets for AI researchers, robotics engineers, and sim-to-real labs.



**Examples** include NVIDIA Isaac Sim / Omniverse Cloud, AWS RoboMaker, AI Habitat (Meta Cloud/Research), MuJoCo (Google DeepMind), Gazebo Cloud (Open Robotics), Webots Cloud (Cyberbotics), CoppeliaSim Pro, Genesis Simulation, PyBullet Cloud, and Project Chrono (the category leaders).



**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for embodied AI evaluation benchmarks (`embodied-first-exam`, `LIBERO`, `SIMPLER`, `RLBench`, `BEHAVIOR-1K`, `CALVIN`, `HumanoidBench`), GPU-accelerated physics simulators (`Isaac Lab`, `MuJoCo / MJX`, `Genesis`, `ManiSkill`, `Brax`), and photorealistic 3D household engines (`Habitat-Sim`, `AI2-THOR`, `SAPIEN`, `Gazebo`) — ideal for robotics researchers, RL/VLA practitioners, and sim-to-real engineers.



🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)

- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)

- [💻 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#️-how-to-contribute)

- [⚠️ Disclaimer](#️-disclaimer)

- [💖 Support & Thank You](#-support--thank-you)



## 📊 Sector Overview & Market Dynamics



The global Robotics Simulation & Embodied AI Software market is valued at approximately **$2.4B–$3.2B+ in 2026** (within the broader **$45B+ robotics and physical AI ecosystem**), expanding at a ~16%–22% CAGR driven by humanoid robotics, foundation Vision-Language-Action (VLA) models, and synthetic sim-to-real data generation. The cloud infrastructure and GPU compute layer exhibits **strong winner-take-most consolidation** around NVIDIA (Omniverse/Isaac) and hyperscalers (AWS/GCP), while the physics engine and benchmark evaluation layer is **moderately fragmented across open-source academic and industry consortiums** (MuJoCo, Genesis, Habitat, LIBERO, Isaac Lab).



## ☁️ SaaS/Hosted & Commercial Platforms



*Sorted descending by company valuation / annual revenue scale.*



| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |

| :--- | :--- | :--- | :--- | :--- |

| **[NVIDIA Isaac Sim / Omniverse Cloud](https://nvidia.com)** | GPU-accelerated photorealistic robotics simulator and synthetic data generation platform built on Omniverse PhysX and OpenUSD. | **Part of NVIDIA Corp.** (~$130B+ annual revenue; ~$3T+ market cap) | **$0 / Free Local Workstation Download** (Omniverse Cloud GPU streams from **~$4.50/hr** via cloud partners) | **100% Free Local Individual License** (Unlimited local Isaac Sim & Isaac Lab usage on NVIDIA RTX GPUs; cloud trial credits via NVIDIA LaunchPad) |

| **[AWS RoboMaker](https://amazon.com)** | Cloud-based robotics simulation service running parallel Gazebo and ROS/ROS 2 batch worlds for automated regression and RL benchmarking. | **Part of Amazon / AWS** (~$115B+ AWS annual revenue; ~$2T+ parent market cap) | **$0.40 / Simulation Unit (SU) hour** (Pay-as-you-go vCPU/RAM simulation compute) | **12-Month AWS Free Tier** (25 Simulation Unit hours per month free for the first 12 months on new AWS accounts) |

| **[MuJoCo (Google DeepMind Hosted / Cloud)](https://mujoco.org)** | High-precision multi-joint contact physics engine used globally as the gold-standard benchmark backend for RL, locomotion, and dexterous manipulation. | **Backed by Google DeepMind / Alphabet** (~$350B+ Alphabet revenue; ~$2T+ market cap) | **$0 / Free Open-Source Engine** (Cloud GPU benchmarking billed via GCP Vertex AI / Colab Pro at **$9.99/mo+**) | **100% Free Forever** (Apache-2.0 engine + free Google Colab T4/TPU runtimes for cloud MJX benchmarks) |

| **[AI Habitat (Meta Research / Cloud)](https://aihabitat.org)** | High-speed photorealistic 3D simulation platform for training and benchmarking embodied agents in indoor Matterport3D/HM3D environments. | **Backed by Meta Platforms** (~$160B+ Meta revenue; ~$1.5T+ market cap) | **$0 / Free Open-Source Platform** (Cloud evaluation runs on user-provided AWS/GCP/Slurm GPU clusters) | **100% Free Forever** (Full Habitat-Sim, Habitat-Lab, and public leaderboard evaluation submissions at zero software cost) |

| **[Gazebo Cloud (Open Robotics / Intrinsic)](https://gazebosim.org)** | Cloud-hosted and containerized ROS 2 robotics simulation ecosystem supporting physics-accurate sensor suites and Fuel model libraries. | **Part of Intrinsic (Alphabet) / Open Source Robotics Foundation** | **$0 / Free Open-Source** (Hosted Fuel model registry free; cloud CI simulation via AWS/GCP compute) | **100% Free Forever** (Unlimited Gazebo Sim worlds, SDF models, and Fuel cloud asset hosting) |

| **[CoppeliaSim (Coppelia Robotics)](https://coppeliarobotics.com)** | Versatile cross-platform robot simulator featuring multiple physics engines (MuJoCo, Bullet, ODE, Vortex), inverse kinematics, and Python/ROS APIs. | **~$5M–$15M Est. Scale** (Established Swiss robotics simulation vendor) | **~$1,990 – $4,990 one-time / floating commercial license** (CoppeliaSim Pro) | **Forever Free Educational Version** (CoppeliaSim Edu is **100% free forever** for students, teachers, and academic research with full feature parity) |

| **[Webots Cloud (Cyberbotics)](https://webots.cloud)** | Browser-accessible cloud robotics simulation and benchmark hosting platform powered by Cyberbotics' Webots engine for competitions and education. | **~$2M–$8M Est. Scale** (Established Swiss robotics simulation company) | **$0 / Free Open-Source** (Commercial custom simulation services & private enterprise hosting available) | **100% Free Forever** (Unlimited open-source desktop simulations and public browser-hosted Webots.cloud benchmark worlds) |

| **[Genesis Simulation (Genesis Embodied AI)](https://github.io)** | Ultra-fast generative physics engine simulating rigid bodies, soft robotics, fluids, and photorealistic ray-tracing at up to 430,000x real-time. | **Academic & Open-Source Consortium** (Multi-university & embodied AI lab collaboration) | **$0 / Free Open-Source** (Cloud GPU execution via standard user cloud providers) | **100% Free Forever** (Apache-2.0 physics engine, generative 4D world builder, and robotics benchmark suite free) |

| **[PyBullet Cloud (Bullet Physics)](https://pybullet.org)** | Widely adopted Python physics simulation and robotics RL environment frequently deployed on Google Colab and cloud CPU/GPU clusters. | **Community / Academic Ecosystem** (Erwin Coumans / Bullet Physics) | **$0 / Free Open-Source** (Cloud execution free on Google Colab / Kaggle kernels) | **100% Free Forever** (Full PyBullet URDF/SDF physics, inverse kinematics, and classic Gym robotics benchmarks free) |

| **[Project Chrono (U. Wisconsin / U. Parma)](https://projectchrono.org)** | High-fidelity multi-physics simulation engine specializing in wheeled/tracked off-road autonomous vehicles, deformable terrain, and granular dynamics. | **Academic Research Consortium** (NSF / DoD / University-backed open-source) | **$0 / Free Open-Source** (BSD-3-Clause; commercial engineering consulting available) | **100% Free Forever** (Unlimited C++/Python Chrono::Vehicle, Chrono::Sensor, and terrain benchmark simulations) |



## 💻 Open-Source GitHub Projects



| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |

| :--- | :--- | :--- | :--- |

| **[Embodied First Exam (`mll-lab-nu/embodied-first-exam`)](https://github.com)** | **Open-Source** ($0 benchmark & evaluation suite) | **100% Free forever** (Unlimited model evaluations across embodied reasoning, spatial perception, and planning tasks) | Comprehensive embodied AI benchmark evaluating foundation models on foundational spatial reasoning, affordance understanding, and physical interaction tasks. |
