<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Yun%20Su%20Hyun&fontSize=90" />
  
  **안녕하세요! 제 깃허브를 방문해 주셔서 감사합니다.** 👋
  
  # 👨‍💻 하드웨어와 AI를 탐구하는 엔지니어
  
  **"RTL 설계부터 On-Device AI까지, 하드웨어와 소프트웨어를 아우르는 엔지니어를 꿈꿉니다."**
</div>

---

## 🚀 About Me
- ⚡ **RTL 설계 및 검증**: FPGA 기반 프로세서(RISC-V, MicroBlaze) 및 통신 IP(SPI, I2C, UART) 설계 경험
- 🧠 **On-Device AI 경험**: 엣지(Edge) 환경에서의 YOLO 비전 모델 및 LLM 최적화 배포
- 🛠 **하드웨어 검증 학습**: UVM(Universal Verification Methodology)을 활용한 검증 및 Timing/Power 분석
- 🎯 **꾸준한 문제 해결**: 문제의 근본 원인을 찾고, 시스템의 병목 현상을 개선해 나가는 과정을 좋아합니다.

---

## 🛠️ Tech Stack

- **Hardware Design** : <img src="https://img.shields.io/badge/Verilog-000000?style=flat-square&logo=verilog&logoColor=white"/> <img src="https://img.shields.io/badge/SystemVerilog-000000?style=flat-square&logo=verilog&logoColor=white"/>
- **Verification** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: <img src="https://img.shields.io/badge/UVM-FF7F00?style=flat-square&logoColor=white"/>
- **Software & AI** &nbsp;&nbsp;&nbsp;: <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=YOLO&logoColor=black"/> <img src="https://img.shields.io/badge/Ollama(LLM)-FFFFFF?style=flat-square&logo=Ollama&logoColor=black"/>
- **Tools** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: <img src="https://img.shields.io/badge/Vivado-D32126?style=flat-square&logo=amd&logoColor=white"/> <img src="https://img.shields.io/badge/VCS-000000?style=flat-square"/> <img src="https://img.shields.io/badge/Verdi-1E1E1E?style=flat-square"/> 
- **Boards** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: <img src="https://img.shields.io/badge/Basys_3-007ACC?style=flat-square"/> <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/> <img src="https://img.shields.io/badge/Jetson_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white"/>

---

## 💻 Key Projects (주요 프로젝트)

| 분야 (Category) | 프로젝트 명 (Project) | 핵심 내용 (Key Details) | 주요 기술 (Tech Stack) |
| :---: | --- | --- | --- |
| **CPU & SoC Architecture**<br>*(하드웨어 설계)* | **[RISC-V 32-bit Multicycle CPU with APB SoC](https://github.com/yunsuhyun-vlog/RISCV-Multicycle)** | - Multi-cycle FSM을 도입해 Single-cycle 대비 Dynamic Power를 68% 감소시켰습니다.<br>- 타이밍 분석을 통해 Setup Timing(WNS)을 개선했습니다. | `RISC-V (RV32I)`<br>`Multi-cycle FSM`<br>`APB Protocol`<br>`Memory Mapped I/O` |
| | **[RISC-V RV32I Single-Cycle Processor](https://github.com/yunsuhyun-vlog/RISCV_Single-cycle)** | - Harvard Architecture 기반의 CPU 데이터패스와 제어 장치를 직접 설계했습니다.<br>- C 코드를 활용한 누적 합 연산으로 소프트웨어 동작 검증을 완료했습니다. | `RISC-V (RV32I)`<br>`Verilog` |
| | **[AXI4-Lite 기반 통신 IP 설계 및 SW 검증](https://github.com/yunsuhyun-vlog/Microblaze_spi)** | - MicroBlaze 코어와 커스텀 SPI IP를 AXI4-Lite 버스로 연동했습니다.<br>- Vitis 환경에서 4-Layered SW 아키텍처를 구성하여 검증을 수행했습니다. | `MicroBlaze`<br>`AXI4-Lite`<br>`Vitis` |
| **Hardware IP & Verification**<br>*(통신 및 검증)* | **[SPI & I2C Protocol Implementation & UVM Verification](https://github.com/yunsuhyun-vlog/SPI_I2C)** | - SPI 및 I2C Master/Slave의 RTL 설계를 진행했습니다.<br>- UVM 환경에서 검증 시나리오를 작성하여 Full-path 커버리지 100%를 달성했습니다. | `SPI/I2C`<br>`SystemVerilog`<br>`UVM` |
| | **[UART 기반 센서 및 시계/스톱워치 컨트롤러](https://github.com/yunsuhyun-vlog/UART-Sensor-Stopwatch-Controller)** | - Synchronous FIFO를 설계하여 통신 속도 차이로 인한 병목 현상을 해소했습니다.<br>- 2-Stage Synchronizer를 도입해 비동기 신호의 Metastability를 방지했습니다. | `UART`<br>`FIFO`<br>`Synchronizer` |
| **On-Device AI & Vision**<br>*(인공지능)* | **[On-Device AI Navigation Guide System](https://github.com/yunsuhyun-vlog/Navigation_Guide)** | - 4개의 YOLO 모델 동시 추론 파이프라인을 구축하고 최적화했습니다.<br>- 경량 LLM(Qwen2) 교체 및 튜닝으로 지연 시간(Latency)을 3.93초에서 0.94초로 단축했습니다. | `YOLO11`<br>`Ollama(Qwen2)`<br>`Multi-threading`<br>`Data Imbalance` |

---

## 📈 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yunsuhyun-vlog&show_icons=true&theme=radium" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yunsuhyun-vlog&layout=compact&theme=radium" width="48%" />
</div>

<br>

<div align="center">
  <i>"겸손한 자세로 끊임없이 배우고 성장하는 엔지니어가 되겠습니다."</i>
</div>
