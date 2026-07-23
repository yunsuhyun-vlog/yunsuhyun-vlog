<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Yun%20Su%20Hyun&fontSize=90" />
  
  # 👨‍💻 하드웨어와 AI의 경계를 허무는 엔지니어
  
  **"탄탄한 RTL 설계 역량을 바탕으로, On-Device AI 시스템까지 아우르는 융합형 엔지니어"**
</div>

---

## 🚀 About Me
- ⚡ **RTL 설계 및 검증**: FPGA 기반 프로세서(RISC-V, MicroBlaze) 및 통신 IP(SPI, I2C, UART) 설계
- 🧠 **On-Device AI 최적화**: 엣지(Edge) 환경에서의 YOLO 비전 모델 및 LLM 최적화 배포
- 🛠 **하드웨어 검증 전문가**: UVM(Universal Verification Methodology)을 활용한 Full-path 검증 및 Timing/Power 분석
- 🎯 **문제 해결 중심**: 문제의 근본 원인을 분석하고 시스템의 병목 현상을 해결하는 과정을 즐깁니다.

---

## 🛠️ Tech Stack

- **Hardware Design** : <img src="https://img.shields.io/badge/Verilog-000000?style=flat-square&logo=verilog&logoColor=white"/> <img src="https://img.shields.io/badge/SystemVerilog-000000?style=flat-square&logo=verilog&logoColor=white"/>
- **Verification** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: <img src="https://img.shields.io/badge/UVM-FF7F00?style=flat-square&logoColor=white"/>
- **Software & AI** &nbsp;&nbsp;&nbsp;: <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=YOLO&logoColor=black"/> <img src="https://img.shields.io/badge/Ollama(LLM)-FFFFFF?style=flat-square&logo=Ollama&logoColor=black"/>
- **Tools** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: <img src="https://img.shields.io/badge/Vivado-D32126?style=flat-square&logo=amd&logoColor=white"/> <img src="https://img.shields.io/badge/VCS-000000?style=flat-square"/> <img src="https://img.shields.io/badge/Verdi-1E1E1E?style=flat-square"/> 
- **Boards** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: <img src="https://img.shields.io/badge/Basys_3-007ACC?style=flat-square"/> <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/> <img src="https://img.shields.io/badge/Jetson_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white"/>

---

## 💻 Key Projects (주요 프로젝트)

| 분야 (Category) | 프로젝트 명 (Project) | 핵심 성과 (Key Impact & Achievements) | 주요 기술 (Tech Stack) |
| :---: | --- | --- | --- |
| **CPU & SoC Architecture**<br>*(하드웨어 아키텍처 및 시스템 설계)* | **[RISC-V 32-bit Multicycle CPU with APB SoC](https://github.com/yunsuhyun-vlog/RISCV-Multicycle)** | Single-cycle 대비 Dynamic Power **68% 감소**(0.072W ➔ 0.023W), Setup Timing 완벽 충족(WNS 개선) | `RISC-V (RV32I)`, `Multi-cycle FSM`, `APB Protocol`, `Memory Mapped I/O` |
| | **[RISC-V RV32I Single-Cycle Processor](https://github.com/yunsuhyun-vlog/RISCV_Single-cycle)** | Harvard Architecture 기반 CPU 데이터패스 및 제어 장치 직접 설계, 누적 합(C Code) 소프트웨어 검증 완료 | `RISC-V (RV32I)`, `Verilog` |
| | **[AXI4-Lite 기반 통신 IP 설계 및 SW 검증](https://github.com/yunsuhyun-vlog/Microblaze_spi)** | MicroBlaze 소프트 코어와 커스텀 SPI IP를 AXI4-Lite 버스로 연동. 4-Layered SW 아키텍처(Vitis)로 검증 수행 | `MicroBlaze`, `AXI4-Lite`, `Vitis` |
| **Hardware IP & Verification**<br>*(통신 인터페이스 및 UVM 검증)* | **[SPI & I2C Protocol Implementation & UVM Verification](https://github.com/yunsuhyun-vlog/SPI_I2C)** | SPI/I2C Master/Slave RTL 설계 및 UVM(Universal Verification Methodology)을 적용한 Full-path 커버리지 100% 달성 | `SPI/I2C`, `SystemVerilog`, `UVM` |
| | **[UART 기반 센서 및 시계/스톱워치 컨트롤러](https://github.com/yunsuhyun-vlog/UART-Sensor-Stopwatch-Controller)** | Synchronous FIFO를 통한 통신 병목 해소, 2-Stage Synchronizer를 이용한 Metastability(Setup/Hold 위반) 완벽 방지 설계 | `UART`, `FIFO`, `Synchronizer` |
| **On-Device AI & Vision**<br>*(인공지능 및 엣지 컴퓨팅)* | **[On-Device AI Navigation Guide System](https://github.com/yunsuhyun-vlog/Navigation_Guide)** | 4개의 YOLO 모델 동시 추론. LLM 모델 교체 및 프롬프트 튜닝으로 지연 시간(Latency) **2.99초 단축**(3.93s ➔ 0.94s) 및 5배 빠른 토큰 생성(18.7 token/s) 달성 | `YOLO11`, `Ollama(Qwen2)`, `Multi-threading`, `Data Imbalance 최적화` |

---

## 📈 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yunsuhyun-vlog&show_icons=true&theme=radium" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yunsuhyun-vlog&layout=compact&theme=radium" width="48%" />
</div>

<br>

<div align="center">
  <i>"끊임없이 탐구하고, 집요하게 병목을 해결하는 엔지니어가 되겠습니다."</i>
</div>
