<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Yun%20Su%20Hyun&fontSize=90" />
  
  **안녕하세요! 제 깃허브를 방문해 주셔서 감사합니다.** 👋
  
  **"꾸준히 답을 찾고, 시스템 타이밍을 개선하는 것을 좋아합니다."**

  <br>

  <a href="mailto:suhyunyun08@gmail.com">
    <img src="https://img.shields.io/badge/Email-suhyunyun08@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</div>

---

## 🚀 About Me
- ⚡ **RTL 설계 및 검증**: FPGA 기반 프로세서(RISC-V, MicroBlaze) 및 통신 IP(SPI, I2C, UART) 설계 경험
- ⚙️ **Firmware & Embedded**: STM32 펌웨어 개발, 하드웨어 타이밍(Slack) 최적화 및 모터 제어(PWM) 프로파일링
- 🧠 **On-Device AI 경험**: YOLO 비전 모델 및 LLM 최적화 배포
- 🛠 **하드웨어 검증 학습**: UVM을 활용한 검증 및 Timing/Power 분석

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
| **Robotics & System Integration**<br>*(로봇 및 시스템 통합)* | **[Smart Factory Logistics with Autonomous AMR & Vision AI](https://github.com/yunsuhyun-vlog/Smart_Factory_with_AMR.git)** | - LiDAR SLAM 기반 자율주행로봇과 로봇팔을 연동한 스마트 물류 자동화 시스템을 구축.<br>- FPGA 하드웨어 영상 처리(HSV) 및 Jetson Nano 기반 AI 비전(CNN) 파이프라인을 구현하여 실시간 객체 추적. | `C / C++`<br>`Python (TensorRT)`<br>`SystemVerilog`<br>`Jetson / FPGA` |
| **Embedded Systems & Firmware**<br>*(임베디드 및 모터제어)* | **[FPGA & STM32 기반 RC카 모션 제어 시스템](https://github.com/yunsuhyun-vlog)** *(링크 업데이트 필요)* | - L298N BJT 스위칭 특성을 분석하여 PWM 주파수를 1kHz로 튜닝, 데드존(Deadzone) 최소화.<br>- UART 파싱 시 발생하는 하드웨어 타이밍 에러(Negative Slack)를 시프트 연산 및 16진수 비트 슬라이싱으로 최적화.<br>- STM32 Input Capture 인터럽트를 활용한 단일 채널(A상) 엔코더 방향 판별 로직 구현. | `STM32 (C)`<br>`SystemVerilog`<br>`PWM / UART`<br>`Encoder` |
| **CPU & SoC Architecture**<br>*(하드웨어 설계)* | **[RISC-V 32-bit Multicycle CPU with APB SoC](https://github.com/yunsuhyun-vlog/RISCV-Multicycle)** | - Multi-cycle FSM을 통해 Single-cycle 대비 Dynamic Power 68% 감소.<br>- 타이밍 분석을 통한 Setup Timing(WNS) 개선. | `RISC-V (RV32I)`<br>`Multi-cycle FSM`<br>`APB Protocol`<br>`Memory Mapped I/O` |
| | **[RISC-V RV32I Single-Cycle Processor](https://github.com/yunsuhyun-vlog/RISCV_Single-cycle)** | - Harvard Architecture 기반 CPU 데이터패스와 제어 장치 설계.<br>- C 코드를 활용한 누적 합 연산으로 소프트웨어 동작 검증 완료. | `RISC-V (RV32I)`<br>`Verilog` |
| | **[AXI4-Lite 기반 통신 IP 설계 및 SW 검증](https://github.com/yunsuhyun-vlog/Microblaze_spi)** | - MicroBlaze 코어와 커스텀 SPI 기기를 AXI4-Lite 버스로 연동.<br>- Vitis 환경에서 4-Layered SW 아키텍처를 구성하여 동작 검증. | `MicroBlaze`<br>`AXI4-Lite`<br>`Vitis` |
| **Hardware IP & Verification**<br>*(통신 및 검증)* | **[SPI & I2C Protocol Implementation & UVM Verification](https://github.com/yunsuhyun-vlog/SPI_I2C)** | - SPI 및 I2C Master/Slave의 RTL 설계 완료.<br>- UVM 환경에서 검증 시나리오 작성하여 Full-path 검증. | `SPI/I2C`<br>`SystemVerilog`<br>`UVM` |
| | **[UART 기반 센서 및 시계/스톱워치 컨트롤러](https://github.com/yunsuhyun-vlog/UART-Sensor-Stopwatch-Controller)** | - Synchronous FIFO를 활용하여 통신 속도 차이로 인한 병목 현상 개선.<br>- 2-Stage Synchronizer를 통한 비동기 신호의 Metastability 개선. | `UART`<br>`FIFO`<br>`Synchronizer` |
| **On-Device AI & Vision**<br>*(인공지능)* | **[On-Device AI Navigation Guide System](https://github.com/yunsuhyun-vlog/Navigation_Guide)** | - 4개의 YOLO 모델 동시 추론 파이프라인 구축.<br>- 경량 LLM(Qwen2) 교체 및 프롬프트 튜닝으로 지연 시간 3.93초에서 0.94초로 단축. | `YOLO11`<br>`Ollama(Qwen2)`<br>`Multi-threading`<br>`Data Imbalance` |

---

## GitHub

<div align="center">

<img src="./profile-3d-contrib/profile-night-rainbow.svg" width="100%" alt="3D Contribution Calendar" />

</div>

<!-- 이 이미지는 .github/workflows/profile-3d.yml 이 매일 자동 생성해 저장소에 커밋

     테마를 바꾸려면 위 경로의 파일명만 교체하세요:
       profile-night-rainbow.svg      ← 현재 (야경 + 무지개 그라데이션)
       profile-night-view.svg          야경
       profile-night-green.svg         야경 + 초록
       profile-gitblock.svg            블록형
       profile-green.svg  /  profile-green-animate.svg
       profile-season.svg /  profile-season-animate.svg   (북반구 계절색)
     ※ -animate 가 붙은 애니메이션 버전은 green / season 계열
-->

---

<div align="center">
<sub>Built with SystemVerilog, coffee, and a lot of waveform staring.</sub>
</div>
