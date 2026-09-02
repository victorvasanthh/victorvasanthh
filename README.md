<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Madana%20Victor%20Vasanth&fontColor=ffffff&fontSize=42&fontAlignY=34&desc=Embedded%20Systems%20%7C%20FPGA%20%7C%20Edge%20AI&descAlignY=54&descSize=16" width="100%" alt="banner"/>

<a href="https://linkedin.com/in/madana-victor-vasanth">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:victorvasanthh@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<img src="https://img.shields.io/badge/Hyderabad,%20India-2C5364?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location"/>
<img src="https://komarev.com/ghpvc/?username=victorvasanthh&style=for-the-badge&color=203a43&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

---

## `~/whoami`

```c
#include <embedded.h>

typedef struct {
    char *name;
    char *role;
    char *education;
    char *domains[5];
    char *silicon[6];
} engineer_t;

const engineer_t me = {
    .name      = "Madana Victor Vasanth",
    .role      = "Embedded Systems & Machine Learning Engineer",
    .education = "M.Tech, Embedded & ML Systems - NIT Warangal",
    .domains   = { "Firmware", "Board Bring-up", "Hardware Validation",
                   "FPGA Design", "Edge AI" },
    .silicon   = { "STM32", "ESP32", "TI Tiva-C", "Raspberry Pi",
                   "Jetson Nano", "Xilinx Zynq-7010" },
};

int main(void) {
    while (1) {
        build();      /* firmware, RTL, inference pipelines */
        measure();    /* scope, logic analyzer, UART traces */
        optimize();   /* latency, power, silicon area       */
    }
}
```

I build software that lives close to the metal — Embedded C firmware, Verilog RTL,
and AI inference pipelines that have to fit inside real timing, memory, and power
budgets. Most of my work sits at the seam where hardware meets machine learning:
bringing up a board, validating it, then making a model run fast enough on it to be
useful in the field.

---

## `~/stack`

**Languages**

![Embedded C](https://img.shields.io/badge/Embedded%20C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-1A1A1A?style=flat-square&logo=v&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Silicon & Boards**

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![TI Tiva-C](https://img.shields.io/badge/TI%20Tiva--C-CC0000?style=flat-square&logo=texasinstruments&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Jetson Nano](https://img.shields.io/badge/Jetson%20Nano-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Xilinx Zynq](https://img.shields.io/badge/Xilinx%20Zynq--7010-E01F27?style=flat-square&logo=xilinx&logoColor=white)

**Hardware & Validation**

![Board Bring-up](https://img.shields.io/badge/Board%20Bring--up-2C5364?style=flat-square)
![Hardware Validation](https://img.shields.io/badge/Hardware%20Validation-2C5364?style=flat-square)
![Functional Testing](https://img.shields.io/badge/Functional%20Testing-2C5364?style=flat-square)
![PCB Integration](https://img.shields.io/badge/PCB%20Integration-2C5364?style=flat-square)
![Device Drivers](https://img.shields.io/badge/Device%20Drivers-2C5364?style=flat-square)
![UART](https://img.shields.io/badge/UART-203A43?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-203A43?style=flat-square)

**Tools & Environment**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Keil](https://img.shields.io/badge/Keil%20uVision-1C1C1C?style=flat-square&logo=arm&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-FF6F00?style=flat-square&logo=mathworks&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-0B5FA5?style=flat-square)
![Embedded Linux](https://img.shields.io/badge/Embedded%20Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Blynk IoT](https://img.shields.io/badge/Blynk%20IoT-2AC08A?style=flat-square&logo=blueprint&logoColor=white)

---

## `~/projects`

<table>
<tr>
<td width="50%" valign="top">

### 🌱 IoT Renewable Energy Microgrid
`ESP32` · `Embedded C` · `Blynk`

ESP32-based microgrid integrating solar panels, batteries, relay modules,
and driver ICs. Firmware written in Embedded C with real-time telemetry
and control through the Blynk IoT platform.

</td>
<td width="50%" valign="top">

### 📏 UART Distance Sensing System
`STM32` · `TI Tiva-C` · `UART`

Ultrasonic ranging system across STM32 and Tiva-C targets, with real-time
UART transport and functional validation of the measurement path from
sensor to host.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ FPGA-Accelerated KNN Architecture
`Verilog` · `Xilinx Zynq` · `RTL Verification`

Hardware KNN accelerator designed and verified on a Zynq FPGA, delivering
substantial gains in classification throughput and energy efficiency over
the software baseline.

</td>
<td width="50%" valign="top">

### 🌾 Real-Time FPGA Pipeline for Agricultural AI
`FPGA` · `Edge AI` · `Computer Vision`

Real-time embedded inference pipeline for crop disease detection, built and
validated against practical timing and on-chip resource constraints.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🩸 Hybrid Deep Learning for Blood Cell Classification
`Jetson Nano` · `ResNet-18` · `MobileNetV2`

ResNet-18 and MobileNetV2 deployed and benchmarked on NVIDIA Jetson Nano
for efficient edge inference on medical imagery.

</td>
<td width="50%" valign="top">

### 🤝 Project Dynamo & Team Development
`Git` · `CI/CD` · `Code Review`

Collaborative engineering across distributed teams — pull requests, issue
tracking, CI/CD workflows, debugging, and peer code review.

</td>
</tr>
</table>

---

## `~/research`

| Venue | Contribution |
| :--- | :--- |
| **IEEE ICCIKE 2025** | An Optimized End-to-End AI Pipeline for Dyslexia-Assistive Handwriting Analysis on Raspberry Pi 4 |
| **IEEE SILCON 2025** | Real-Time Driver Drowsiness Detection for Road Safety using Hybrid YOLOv8 and CNN Approach |
| **IEEE INDISCON 2025** | Technical Reviewer — Embedded & VLSI domain |

---

## `~/education`

| Degree | Institution | Field | CGPA |
| :--- | :--- | :--- | :--- |
| **M.Tech** | NIT Warangal | Embedded and Machine Learning Systems | 7.72 / 10 |
| **B.Tech** | TKR College of Engineering and Technology | Electronics and Communication Engineering | 7.39 / 10 |

---

## `~/stats`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=victorvasanthh&show_icons=true&hide_border=true&theme=tokyonight&count_private=true&include_all_commits=true"/>
  <img src="https://github-readme-stats.vercel.app/api?username=victorvasanthh&show_icons=true&hide_border=true&count_private=true&include_all_commits=true" height="165" alt="GitHub stats"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=victorvasanthh&layout=compact&hide_border=true&theme=tokyonight&langs_count=8"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=victorvasanthh&layout=compact&hide_border=true&langs_count=8" height="165" alt="Top languages"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=victorvasanthh&hide_border=true&theme=tokyonight"/>
  <img src="https://streak-stats.demolab.com?user=victorvasanthh&hide_border=true" height="165" alt="Contribution streak"/>
</picture>

<img src="https://github-profile-trophy.vercel.app/?username=victorvasanthh&theme=nord&no-frame=true&no-bg=true&margin-w=6&row=1&column=7" alt="Trophies"/>

</div>

---

## `~/now`

```bash
$ cat ~/.learning
Semiconductor Validation
VLSI Design
Embedded Linux
High-Speed Interface Validation
FPGA Design & Timing Closure
Hardware Debugging
```

---

<div align="center">

### `~/contact`

Open to collaborating on **embedded firmware**, **FPGA / RTL**, **edge AI**, and **open source**.

<a href="https://linkedin.com/in/madana-victor-vasanth">
  <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:victorvasanthh@gmail.com">
  <img src="https://img.shields.io/badge/Say%20Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

<br><br>

<sub>⭐ Thanks for stopping by — let's build something that ships.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" alt="footer"/>

</div>
