<div align="center">

# Ebuka Eleogu

### Electrical & Electronics Engineer · Robotics · Defense Systems · Embedded ML

*Building the hardware layer for Africa's next generation of autonomous systems.*

[![GitHub](https://img.shields.io/badge/GITHUB-itsebuka-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/itsebuka)
[![X](https://img.shields.io/badge/X-@jociefer-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/jociefer)
[![Website](https://img.shields.io/badge/WEBSITE-ebukaeleogu.vercel.app-1a1a1a?style=for-the-badge&logo=vercel&logoColor=white)](https://ebukaeleogu.vercel.app/)
[![Hanuman Labs](https://img.shields.io/badge/HANUMAN_LABS-conglomerate-1a1a1a?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAyTDIgN2wxMCA1IDEwLTV6Ii8+PC9zdmc+)](https://github.com/itsebuka)

</div>

<br>

## About

Third-year Electrical & Electronics Engineering student at Pan-Atlantic University, Lagos (Class of 2028). I design and build hardware: PCBs, embedded sensor systems, and applied ML pipelines, with a focus on defense electronics and autonomous perimeter security.

Founder of **Hanuman Labs**, a Nigerian venture aimed at becoming a multi-sector deep-tech conglomerate, starting with dual-use defense and security hardware and scaling into robotics and industrial electronics. Currently interning in Network Planning & Optimization at **Ikeja Electric**.

```
hardware   ->  embedded systems / PCB design (KiCad) / sensor integration / STM32
software   ->  Python / C++ / computer vision (YOLOv8) / RAG pipelines / Fusion 360 / STM32CubeIDE
domains    ->  defense hardware & electronics / electrical engineering / applied ML
```

<br>

## Current Build Focus: Heimdall

**Heimdall** is a modular perimeter intrusion detection system built for high-risk Nigerian environments, developed for the **Africa Deep Tech Challenge**. It combines a multi-sensor directional network with edge-based threat classification.

**Architecture:**
- **Power distribution board:** three switching regulators (2× LM2596S-5, 1× TPS54560), TVS/polyfuse protection stage, fully routed in KiCad
- **Directional sensor boards (N/S/E/W):** PIR, 24GHz Doppler radar, seismic, ultrasonic, and tamper microswitch, each with a local STM32 reporting over MQTT
- **CV/threat-scoring layer:** YOLOv8 on a Raspberry Pi / Jetson SBC for on-device threat classification
- **Gimbal tracking node:** 2-axis pan-tilt mechanism, STM32 PWM control, Python/OpenCV target tracking

| Repository | Covers |
|---|---|
| [`Heimdall`](https://github.com/itsebuka/Heimdall) | System overview, integration, main sensor-fusion firmware |
| [`Heimdall-Node-Telemetry`](https://github.com/itsebuka/Heimdall-Node-Telemetry) | KiCad schematics, 3D enclosures (Fusion 360), STM32 firmware for the sensor node |
| [`Heimdall-CV-Gimbal-tracker`](https://github.com/itsebuka/Heimdall-CV-Gimbal-tracker) | Pan-tilt gimbal control + CV target tracking |

<br>

## My Stack

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

</div>

<br>

## Featured Projects

### [Heimdall](https://github.com/itsebuka/Heimdall)
Modular perimeter defense & recon system: STM32 sensor node → MQTT → YOLOv8 threat-scoring dashboard. Built for high-risk Nigerian environments. *Africa Deep Tech Challenge 2026 entry.*

### [3-DOF Robotic Arm](https://github.com/itsebuka/3-DOF-Robotic-Arm)
Fully engineered, 3D-printable robotic arm designed from scratch in Autodesk Fusion 360, with full mechanical and control design included in-repo.

### [PCB-Design-Core](https://github.com/itsebuka/PCB-Design-Core)
Every PCB I've designed, primarily in KiCad and EasyEDA, ranging from a 4-bit magnitude comparator (74LS85) to the multi-board Heimdall power and sensor stack.

### [STM32-embedded-core](https://github.com/itsebuka/STM32-embedded-core)
Every embedded systems project on my path to STM32 mastery: firmware, drivers, and sensor integration code.

### [Hanuman MedBot](https://github.com/itsebuka/Apollo-Medical-bot)
Flask-based medical chatbot using local LLMs and a RAG pipeline over medical literature, built to test retrieval accuracy and grounding on clinical queries.

<br>

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=itsebuka&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=itsebuka&layout=compact&theme=dark&hide_border=true&bg_color=0d1117" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=itsebuka&theme=dark&hide_border=true&background=0D1117" />

</div>

<br>

<div align="center">

*Fortis Fortuna Adiuvat. Fortune favors the brave.*

</div>
