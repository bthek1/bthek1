<div align="center">

<img src="Logo.svg" width="132" alt="Benedict Thekkel" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Benedict%20Thekkel&fontSize=56&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Full-Stack%20Engineer%20%E2%80%A2%20Robotics%20%E2%80%A2%20ML%2FAI%20%E2%80%A2%20Hardware&descAlignY=60&descSize=17" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=6AD3F7&center=true&vCenter=true&width=640&lines=Building+production+full-stack+systems+end+to+end;Monocular+visual+SLAM+in+C%2B%2B17+on+ROS+2;ML+models+in+the+browser+on+WebGPU;Electrical+engineer+who+ships+software;From+circuit+boards+to+cloud+deployments" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=bthek1&color=6AD3F7&style=flat-square&label=Profile+Views" />
<img src="https://img.shields.io/github/followers/bthek1?label=Followers&style=flat-square&color=6AD3F7" />
<img src="https://img.shields.io/badge/Based_in-Brisbane%2C_Australia-6AD3F7?style=flat-square" />

</div>

---

## 👨‍💻 &nbsp;About Me

```python
class BenedictThekkel:
    role        = "Full-Stack Engineer, Recovery Metrics (healthcare)"
    also        = "ML Engineer, Phisaver (energy IoT), one day a week"
    trained_as  = "Electrical Engineer (BE, UQ 2024)"
    builds      = "complete products end to end, device to model"
    languages   = ["Python", "TypeScript", "C++17", "C", "SQL"]
    backend     = ["Django", "Django REST Framework", "PostgreSQL", "Celery", "Redis"]
    frontend    = ["React", "TypeScript", "Vite"]
    robotics    = ["ROS 2", "OpenCV", "ONNX Runtime + CUDA", "visual SLAM", "TSDF fusion"]
    ml_ai       = ["PyTorch", "computer vision", "LLM agents", "Transformers.js", "WebGPU"]
    infra       = ["AWS", "Pulumi", "Terraform", "Ansible", "Kubernetes (k3s)", "Helm", "CI/CD"]
    hardware    = ["ESP32", "Raspberry Pi", "Arduino", "PCB design", "firmware"]
    philosophy  = "Every number is printed by a script that asserts on it."
```

- 🔭 &nbsp;**Two years owning a production healthcare platform** at Recovery Metrics: Django REST backend, role-based access for sensitive clinical data, AWS infrastructure, and a front end I moved from vanilla JS onto **React + Vite + TypeScript** on the live product, without a rewrite
- 🤖 &nbsp;**Robotics in C++17.** [`ros2_pi`](https://github.com/bthek1/ros2_pi) is monocular visual SLAM on ROS 2: a Raspberry Pi 5 webcam streaming to a GPU box for ORB + PnP odometry, neural depth on CUDA, TSDF fusion, a live triangle mesh, and loop closure over a g2o pose graph
- 🧠 &nbsp;**ML in the browser.** [`model_playground`](https://github.com/bthek1/model_playground) runs around 40 models client-side through ONNX Runtime Web on WebGPU, plus GNN training on hand-written WGSL shaders. Live at [playground.benedictthekkel.com](https://playground.benedictthekkel.com)
- ⚡ &nbsp;**Electrical engineer by training**, comfortable down to firmware and PCBs: I contributed a feature to Phisaver's ESP32 switchbox firmware that now runs across the deployed fleet
- 🧩 &nbsp;Happiest at the **intersection of hardware, software and ML/AI**, where robotics and perception live

---

## 🚀 &nbsp;Featured Projects

| Project | What it is | Built with |
|---------|-----------|------------|
| [**ros2_pi**](https://github.com/bthek1/ros2_pi) | Real-time monocular visual SLAM. About 23k lines of C++17 across 11 ROS 2 packages and ~700 tests. Keyframe ATE **0.12 to 0.15 m with loop closure** against 0.36 to 0.53 m without, on TUM fr1/desk | C++17, ROS 2, OpenCV, ONNX Runtime + CUDA, g2o, GoogleTest |
| [**model_playground**](https://github.com/bthek1/model_playground) | ~42 ML task pages (LLMs, vision, speech, segmentation, depth, GNNs) running entirely on the visitor's GPU. ~3,500 Vitest + ~400 Playwright tests, deployed by Pulumi through GitHub Actions OIDC | TypeScript, React, WebGPU / WGSL, Transformers.js, AWS S3 + CloudFront |
| [**Market_Analyzer**](https://github.com/bthek1/Market_Analyzer) | Full-stack stock market analyser with eleven LLM agent architectures and a self-expanding knowledge graph, behind an enforced 80% coverage gate, with Grafana / Prometheus / Loki observability | Django, DRF, React, PostgreSQL, Celery, Redis, Ollama, Anthropic API |
| [**piros2**](https://github.com/bthek1/piros2) | The Python predecessor to `ros2_pi`: a distributed ROS 2 Jazzy sensor node on a Raspberry Pi 5 with GPU depth inference and point-cloud fusion | Python, ROS 2, rclpy, Open3D, ONNX Runtime |
| [**Knowledge docs**](https://bthek1.github.io/) | My notebooks on ML, deep learning, web, tools and ROS 2, published as one federated nbdev + Quarto site | nbdev, Quarto, Jupyter |

I drive development with Claude Code daily, and the validation is the part I care about: `ros2_pi` closes every performance claim with an integration gate that has an adversarial control run proving the threshold can fail.

---

## 🛠 &nbsp;Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++17](https://img.shields.io/badge/C++17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & Frontend**

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

**Robotics & Perception**

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![WebGPU](https://img.shields.io/badge/WebGPU-005A9C?style=for-the-badge&logo=webgpu&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

**Cloud, DevOps & Observability**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=FF9900)
![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?style=for-the-badge&logo=pulumi&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Hardware & Embedded**

![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Altium](https://img.shields.io/badge/Altium-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)

</div>

---

## 📊 &nbsp;GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bthek1&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=6AD3F7&icon_color=6AD3F7" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bthek1&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&bg_color=0d1117&title_color=6AD3F7" height="165" />

<br/>

<img src="https://streak-stats.demolab.com?user=bthek1&theme=tokyonight-duo&hide_border=true&background=0d1117&stroke=6AD3F7&ring=6AD3F7&fire=FF6B6B&currStreakLabel=6AD3F7" />

</div>

---

## 🐍 &nbsp;Contribution Graph

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bthek1/bthek1/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/bthek1/bthek1/output/github-contribution-grid-snake.svg" />
    <img alt="Snake animation" src="https://raw.githubusercontent.com/bthek1/bthek1/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

## 🤝 &nbsp;Let's Connect

<div align="center">

<a href="https://github.com/bthek1" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="https://www.linkedin.com/in/benedict-thekkel/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="https://bthek1.github.io/bthek1_blog/" target="_blank">
  <img src="https://img.shields.io/badge/Blog-6AD3F7?style=for-the-badge&logo=quarto&logoColor=white" />
</a>
&nbsp;
<a href="https://playground.benedictthekkel.com" target="_blank">
  <img src="https://img.shields.io/badge/Model_Playground-6AD3F7?style=for-the-badge&logo=webgpu&logoColor=white" />
</a>

</div>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=90&section=footer" width="100%" />
