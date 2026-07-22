# 👨‍💻 안녕하세요! 하드웨어와 AI의 경계를 허무는 엔지니어, 윤수현입니다.

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Yun%20Su%20Hyun&fontSize=90" />
</div>

> **"탄탄한 RTL 설계 역량을 바탕으로, On-Device AI 시스템까지 아우르는 융합형 엔지니어"**

FPGA 기반의 프로세서 및 통신 IP(RTL) 설계부터, 엣지(Edge) 환경에서의 AI 모델 최적화 및 배포까지 하드웨어와 소프트웨어를 넘나드는 최적화에 강점을 가지고 있습니다. 문제의 근본 원인을 분석(Timing/Power Report 분석, UVM 검증)하고 병목을 해결하는 과정을 즐깁니다.

## 🛠️ Tech Stack
- **Hardware Design**: <img src="https://img.shields.io/badge/Verilog-000000?style=flat-square&logo=verilog&logoColor=white"/> <img src="https://img.shields.io/badge/SystemVerilog-000000?style=flat-square&logo=verilog&logoColor=white"/> <img src="https://img.shields.io/badge/FPGA_Vivado-blue?style=flat-square"/>
- **Verification**: `UVM (Universal Verification Methodology)`
- **Software & AI**: <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=YOLO&logoColor=black"/> <img src="https://img.shields.io/badge/Ollama(LLM)-FFFFFF?style=flat-square&logo=Ollama&logoColor=black"/>

---

## 🚀 Key Projects (주요 프로젝트)

### 🖥️ CPU & SoC Architecture (하드웨어 아키텍처 및 시스템 설계)
기업의 핵심인 프로세서 구조에 대한 깊은 이해를 바탕으로 설계 및 전력/타이밍 최적화를 수행했습니다.
* **[RISC-V 32-bit Multicycle CPU with APB SoC](https://github.com/yunsuhyun-vlog/RISCV-Multicycle)**
  * **핵심 성과**: Single-cycle 대비 Dynamic Power **68% 감소**(0.072W ➔ 0.023W), Setup Timing 완벽 충족(WNS 개선)
  * **기술 스택**: `RISC-V (RV32I)`, `Multi-cycle FSM`, `APB Protocol`, `Memory Mapped I/O`
* **[RISC-V RV32I Single-Cycle Processor](https://github.com/yunsuhyun-vlog/RISCV_Single-cycle)**
  * **핵심 성과**: Harvard Architecture 기반 CPU 데이터패스 및 제어 장치 직접 설계, 누적 합(C Code) 소프트웨어 검증 완료
* **[AXI4-Lite 기반 통신 IP 설계 및 SW 검증](https://github.com/yunsuhyun-vlog/Microblaze_spi)**
  * **핵심 성과**: MicroBlaze 소프트 코어와 커스텀 SPI IP를 AXI4-Lite 버스로 연동. 4-Layered SW 아키텍처(Vitis)로 검증 수행

### 🔌 Hardware IP & Verification (통신 인터페이스 및 UVM 검증)
다양한 통신 프로토콜 및 주변 장치를 제어하고, UVM(SystemVerilog) 기반의 꼼꼼한 검증 방법론을 적용합니다.
* **[SPI & I2C Protocol Implementation & UVM Verification](https://github.com/yunsuhyun-vlog/SPI_I2C)**
  * **핵심 성과**: SPI/I2C Master/Slave RTL 설계 및 UVM(Universal Verification Methodology)을 적용한 Full-path 커버리지 100% 달성
* **[UART 기반 센서 및 시계/스톱워치 컨트롤러](https://github.com/yunsuhyun-vlog/UART-Sensor-Stopwatch-Controller)**
  * **핵심 성과**: Synchronous FIFO를 통한 통신 병목 해소, 2-Stage Synchronizer를 이용한 Metastability(Setup/Hold 위반) 완벽 방지 설계

### 🤖 On-Device AI & Vision (인공지능 및 엣지 컴퓨팅)
AI 모델을 최적화하여 엣지 디바이스에 올리고, 다중 모델 병렬 처리를 구현한 융합 프로젝트입니다.
* **[On-Device AI Navigation Guide System](https://github.com/yunsuhyun-vlog/Navigation_Guide)**
  * **핵심 성과**: 4개의 YOLO 모델 동시 추론 파이프라인 최적화. LLM 모델 교체 및 프롬프트 튜닝으로 지연 시간(Latency) **2.99초 단축**(3.93s ➔ 0.94s) 및 5배 빠른 토큰 생성(18.7 token/s) 달성
  * **기술 스택**: `YOLO11`, `Ollama(Qwen2)`, `Multi-threading`, `Data Imbalance 최적화`

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
