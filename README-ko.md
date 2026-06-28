<!--lint disable awesome-toc-->
# Awesome Drone Hacking (한국어) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- markdownlint-disable MD033 -->
<p align="center">
  <a href="https://x.com/intent/tweet?text=Awesome%20Drone%20Hacking%20-%20A%20list%20of%20awesome%20drone%20hacking%20tools%20and%20resources.%0Ahttps%3A%2F%2Fgithub.com%2Fnicholasaleks%2FAwesome-Drone-Hacking&hashtags=awesomelists,drone,hacking,cybersecurity,infosec" target="_blank">
    <img src="https://img.shields.io/badge/Tweet--lightgrey?logo=x&style=social" alt="Tweet" height="20"/>
  </a>

  <img alt="Deadlinks Checked" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/deadlinks.yml/badge.svg">
  <img alt="Awesome Lint" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/awesome-lint.yml/badge.svg">
  <img alt="YAML Lint" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/yamllint.yml/badge.svg">
  <img alt="Action Lint" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/actionlint.yml/badge.svg">
  
  <a href="https://github.com/nicholasaleks/Awesome-Drone-Hacking/graphs/contributors">
    <img alt="Contributors" src="https://img.shields.io/github/contributors/nicholasaleks/Awesome-Drone-Hacking.svg">
  </a>
  <a href="https://github.com/nicholasaleks/Awesome-Drone-Hacking/stargazers">
    <img src="https://img.shields.io/github/stars/nicholasaleks/Awesome-Drone-Hacking.svg?style=social" alt="Stars"/>
  </a>
  <a href="https://github.com/nicholasaleks/Awesome-Drone-Hacking/fork">
    <img src="https://img.shields.io/github/forks/nicholasaleks/Awesome-Drone-Hacking.svg?style=social" alt="Forks"/>
  </a>
</p>


<p align="center">
  <strong>멋진 드론 해킹 도구와 자료 모음입니다.</strong><br/>
  <small><a href="README.md">English</a> | <a href="README-ko.md"><b>한국어</b></a></small><br/><br/>

  <img
   src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/blob/main/Awesome-Drone-Hacking-Banner.png?raw=true"
   alt="Awesome Drone Hacking List Logo" />

  이 저장소는 텔레메트리·비행 제어부터 하드웨어·펌웨어·통신 프로토콜까지,
  오픈소스·자율·FPV(1인칭 시점)·독점 드론 시스템 해킹에 관한 도구·기법·연구를 다룹니다.
</p>

*범례*

* 🌟: 특히 추천
* 💰: 유료
* 👻: 구버전/보관됨
<!-- markdownlint-enable MD033 -->

---

## 📚 목차
<!--lint disable awesome-list-item-->
* [🔬 드론 해킹 랩, CTF 및 워크숍](#-drone-hacking-labs-ctfs--workshops)
* [🎤 컨퍼런스 발표 및 영상](#-conference-talks--videos)
* [💿 실시간 운영체제(RTOS)](#-real-time-operating-systems)
  * [퍼징 및 분석 도구](#fuzzing--analysis-tools)
  * [에뮬레이터](#emulators)
* [🔌 비행 제어기 및 임베디드 시스템](#-flight-controller--embedded-systems)
  * [임베디드/하드웨어 해킹 도구](#embedding-hacking-tools)
  * [일반 비행 제어기·임베디드 자료](#common-flight-controller--embedded-system-resources)
* [📻 무선 및 텔레메트리](#-radio--telemetry)
  * [원격 식별 탐지·스푸핑 도구](#remote-identification-discovery--spoofing-tools)
  * [텔레메트리 탐지·도청 도구](#telemetry-detection--eavesdropping-tools)
* [기타 RF 도구](#misc-rf-tools)
  * [일반 텔레메트리 무선](#common-telemetry-radios)
* [📶 Wi‑Fi 통신](#-wi-fi-communications)
  * [Wi‑Fi 탐지·침투 도구](#wi-fi-detection--infiltration-tools)
  * [일반 Wi‑Fi 프로토콜 및 장비](#common-wi-fi-protocols--equipment)
* [📺 FPV 및 페이로드](#-fpv--payloads)
  * [영상 도청](#video-eavesdropping)
* [📡 BVLOS 통신](#-bvlos-communications)
  * [셀룰러 분석·변조 도구](#cellular-analysis--tampering-tools)
  * [일반 BVLOS 장비](#common-bvlos-equipment)
* [🤖 프로토콜 및 미들웨어 도구](#-protocols--middleware-tools)
  * [프로토콜 분석·변조](#protocol-analysis--tampering)
* [💽 자동조종 펌웨어](#-autopilot-firmware)
  * [펌웨어 분석](#firmware-analysis)
  * [펌웨어 추출](#firmware-extraction)
  * [펌웨어 수정](#firmware-modification)
* [🧠 컴패니언 컴퓨터](#-companion-computers)
* [🛫 지상국(GCS)](#-ground-control-stations)
* [📱 모바일 GCS 앱](#-mobile-gcs-apps)
* [🧠 인공지능 라이브러리](#-artifical-intelligence-libraries)
* [🏢 제조사별 연구](#-vendor-specific-research)
  * [DJI](#dji)
  * [Parrot](#parrot)
  * [기타](#misc)
* [📚 연구 논문 및 블로그 글](#-research-papers--blog-articles)
* [🔍 OSINT 및 인텔리전스](#-osint--intelligence)
* [💥 익스플로잇, CVE 및 취약점](#-exploits-cves--vulnerabilities)
* [📣 취약점 공개·신고 프로그램](#-vulnerability-disclosure-programs)
* [🎓 교육 및 훈련](#-training--education)
* [🗣️ 커뮤니티](#-communities)
* [추가 자료](#additional-resources)
* [⚖️ 법적 고지](#-legal-notice)
<!--lint enable awesome-list-item-->

<a id="-drone-hacking-labs-ctfs--workshops"></a>
## 🔬 드론 해킹 랩, CTF 및 워크숍
* [Damn Vulnerable Drone (DVD)](https://github.com/nicholasaleks/Damn-Vulnerable-Drone) - Docker 기반 가상 드론 해킹 시뮬레이터.
* [Hack Our Drone Workshop](https://dronewolf.darkwolf.io/workshop) - Dark Wolf의 Hack Our Drone 워크숍.
* [Drone Wars, BloomCon](https://www.commonwealthu.edu/offices-directory/mathematics-computer-science-and-digital-forensics/drone-wars-competition) - 팀이 Wi‑Fi 드론을 탈취해 장애물 코스를 경주하는 대학 리그 형태의 대회.
* [Hack The Drone](http://hackthedrone.org/eng/index.php) - 국제 드론 해킹 대회, 한국드론보안협회.

<a id="-conference-talks--videos"></a>
## 🎤 컨퍼런스 발표 및 영상
* [WTF WJI, UAV CTF?](https://ftp.fau.de/cdn.media.ccc.de/events/camp2023/h264-hd/camp2023-57063-eng-WTF_DJI_UAV_CTF_hd.mp4) - Felix Domke, cccamp23.
* [Debugging Microcontrollers](https://media.ccc.de/v/camp2023-57321-debugging_microcontrollers) - Niklas Hauser, ccamp23.
* [Demodulating 5GHz analog drone video](https://www.youtube.com/watch?app=desktop&v=rl8ACNnjPFA) - Cemaxecuter, YouTube.
* [Game of Drones](https://www.slideshare.net/slideshow/def-con-25-2017-game-of-drones-brown-latimer-29july2017-slidespdf/250332791) - Bishopfox Dangerdrone.
* [Parrot Drones Hijacking](https://www.youtube.com/watch?v=66z-aXy_1Yo) - RSA2018 Video, Pedro Cabrera, March 2018 (Slides).
* [A Drone Tale, All your drones are belong to us](http://youtube.com/watch?v=aU4ULr3Lwt8) - Paolo Stagno, Hacktivity.
* [All your bebop drones still belong to us](https://www.youtube.com/watch?v=ra0nKHvaXnc) - Pedro Cabrera, Rooted CON, 2016.
* [Shelling out a "smart drone"](https://www.youtube.com/watch?v=IqCz-V6WMVg&t=2875s) - Kevin Finisterre, Derbycon 2015.
* [Drones Hijacking - Multi dimensional attack vectors](https://www.youtube.com/watch?v=DFLofy789ko) - Aaron Luo, DEF CON 24, 2016.
* [Hacking a Professional Drone](https://www.youtube.com/watch?v=JRVb-xE1zTI&t=470s) - Nils Rodday, Black Hat, 2016.
* [Avoiding CounterDrone Systems with NanoDrones](https://www.youtube.com/watch?v=pVmFxJPOu9I) - David Melendez Cano, DEF CON 26, 2018.
* [Game of Drones](https://www.youtube.com/watch?v=iG7hUE2BZZo) - Fran Brown & David Latimer, DEF CON 25, 2017.
* [Spread Spectrum techniques for anti drone evasion](https://www.youtube.com/watch?v=8Ng91UY3D2M) - David Melendez, Gabriela Garcia, DEF CON 31, 2023.
* [Knocking my neighbors kids cruddy drone offline](https://www.youtube.com/watch?v=5CzURm7OpAA) - Michael Robinson, DEF CON 23, 2015.
* [Practical Aerial Hacking & Surveillance](https://www.youtube.com/watch?v=knrvrR-B1ZI) - Glenn Wilkinson, DEF CON 22, 2015.
* [SkyJack - autonomous drone hacking](https://www.youtube.com/watch?v=EHKV01YQX_w) - Samy Kamkar, YouTube, 2013.
* [Icarus - Hacking and hijacking DSMx drones, RC devices](https://www.youtube.com/watch?v=abl6oOxLRXs) - Jonathan Andersson, PACSEC, 2016.

<a id="-real-time-operating-systems"></a>
## 💿 실시간 운영체제(RTOS)

<a id="fuzzing--analysis-tools"></a>
### 퍼징 및 분석 도구
* [Fuzzware](https://github.com/fuzzware-fuzzer/fuzzware) - 임베디드 기기 펌웨어 동적 분석에 초점을 둔 타깃 오케스트레이션 프레임워크.
* [Avatar² Framework](https://github.com/avatartwo/avatar2) - 임베디드 타깃과 펌웨어 이미지에 대한 동적 분석·멀티 타깃 오케스트레이션 프레임워크.
* [American Fuzzy Lop plus plus](https://github.com/AFLplusplus/AFLplusplus) - 커뮤니티 패치, QEMU 5.1 업그레이드, 충돌 없는 커버리지, laf-intel·redqueen 강화, AFLfast++ 파워 스케줄, MOpt 뮤테이터, unicorn_mode 등이 포함된 AFL++.

<a id="emulators"></a>
## 에뮬레이터
* [QEMU](https://www.qemu.org/) - 범용 오픈소스 머신 에뮬레이터 및 가상화 도구.
* [Renode](https://github.com/renode/renode) - 복잡한 임베디드 시스템을 위한 Antmicro의 오픈소스 시뮬레이션·가상 개발 프레임워크. 다수의 [STM32](https://github.com/renode/renode/blob/master/platforms/cpus/stm32f4.repl) 시리즈 칩을 지원.

### 일반적인 RTOS
* [NuttX](https://nuttx.apache.org/) - PX4에서 사용하는 NuttX RTOS.
* [ChibiOS](https://www.chibios.org/dokuwiki/doku.php) - ArduPilot에서 사용하는 ChibiOS RTOS.

<a id="-flight-controller--embedded-systems"></a>
## 🔌 비행 제어기 및 임베디드 시스템

<a id="embedding-hacking-tools"></a>
### 임베디드/하드웨어 해킹 도구
* [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - UART·JTAG 등 하드웨어 디버그 포트를 탐지하고 상호작용.
* [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - UART·JTAG 등 하드웨어 디버그 포트를 탐지하고 상호작용.
* [Tigard](https://www.crowdsupply.com/securinghw/tigard) - FT2232H 기반 오픈소스 다중 프로토콜·다중 전압 하드웨어 해킹 도구.
* [JTAGULATOR](https://grandideastudio.com/portfolio/security/jtagulator/) - JTAG 핀아웃을 빠르게 탐지.
* [Saleae](https://www.saleae.com/) - 다양한 프로토콜을 지원하는 사용하기 쉬운 로직 애널라이저.
* [Ikalogic](https://www.ikalogic.com/sp209-logic-analyzer/) - Saleae 로직 애널라이저 대안.
* [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/?v=0b3b97fa6688) - Bus Pirate와 유사하지만 NFC 기능이 있는 오픈소스 멀티툴 하드웨어.
* [ChipWhisperer](https://www.newae.com/chipwhisperer) - 글리치·부채널 공격 탐지.
* [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) - 다양한 디지털 인터페이스 탐색·디버깅 도구.
* [J-Link](https://www.segger.com/products/debug-probes/j-link/) - 여러 CPU 코어용 USB 전원 JTAG 디버그 프로브.

<a id="common-flight-controller--embedded-system-resources"></a>
### 일반 비행 제어기·임베디드 자료
* [STM32](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html) - 32비트 Arm Cortex MCU.
* [AT32](https://www.arterychip.com/en/product/AT32F425.jsp) - 32비트 Cortex-M4 마이크로컨트롤러(MCU).
* [Pixhawk](https://pixhawk.org/) - 오픈소스 하드웨어 비행 제어기.
* [Cube](https://www.cubepilot.com/#/home) - 모듈형 비행 제어기 하드웨어.
* [DJI A3](https://www.dji.com/ca/a3) - 산업용 멀티로터를 위한 삼중 IMU와 고급 페일세이프를 갖춘 상용급 비행 제어기.
* [DJI N3](https://www.dji.com/ca/n3) - 전문 공중 촬영용으로 설계되었으며 DJI Inspire 2·Lightbridge 2 연동에 최적화된 비행 제어기.
* [CUAV X7 & V5+](https://ardupilot.org/copter/docs/common-cuav-x7-family-overview.html) - 풍부한 I/O와 견고한 센서 이중화를 갖춘 고성능 ArduPilot 비행 제어기.
* [Holybro Kakute F7/H7](https://holybro.com/products/kakute-h7-v2?srsltid=AfmBOorAjpi2nnbfkXOsFjFxvt8UiLFDPlo7vlpXIBhJMvUBZDkQ2fqW) - 레이싱·프리스타일 드론에서 널리 쓰이는 소형 Betaflight 호환 비행 제어기.
* [PX4 Wiring Diagram](https://docs.px4.io/main/en/assembly/quick_start_pixhawk5x.html) - PX4를 구동하는 Pixhawk 5X 비행 제어기 배선 공식 참고 도면.

<a id="-radio--telemetry"></a>
## 📻 무선 및 텔레메트리

<a id="remote-identification-discovery--spoofing-tools"></a>
### 원격 식별(Remote ID) 탐지·스푸핑 도구
* [DragonSync-iOS](https://github.com/Root-Down-Digital/DragonSync-iOS) - iOS/macOS에서 Remote/Drone ID 규격에 맞는 실시간 드론 탐지·모니터링.
* [RemoteID Spoofer](https://github.com/jjshoots/RemoteIDSpoofer) - Red Team 테스트를 위해 Wi‑Fi로 GPS 주변 최대 16대의 가짜 Remote ID 송신 드론을 시뮬레이션하는 ESP8266/NodeMCU 도구.
* [WiFi RID capture](https://github.com/sxjack/unix_rid_capture) - ASTM F3411(Wi‑Fi/Bluetooth) Remote ID 프레임을 수신하고 실제 UAV 위치를 JSON으로 기록하는 Linux 도구.
* [DJI DroneID Detection](https://www.crowdsupply.com/microphase-technology/antsdr-e200/updates/dji-droneid-detection) - ZYNQ·AD936x 칩셋 기반 FPGA SDR.

<a id="telemetry-detection--eavesdropping-tools"></a>
### 텔레메트리 탐지·도청 도구
* [SiKW00F](https://github.com/nicholasaleks/sikw00f) - SiK 무선 탐지 및 MAVLink 텔레메트리 도청 툴킷.
* [SiKening](https://github.com/MAVProxyUser/SiKening) - Meatball Ninja의 3DR Radio SiKening PoC — 3DR NetID 브루트포스 및 홉핑 시퀀스 동기화.

<a id="misc-rf-tools"></a>
## 기타 RF 도구
* [GNURadio](https://github.com/gnuradio/gnuradio) - 자유·오픈 소프트웨어 무선(SDR) 생태계.
* [SigDigger](https://github.com/BatchDrake/SigDigger) - 무료 디지털 신호 분석기.
* [SDRangel](https://github.com/f4exb/sdrangel) - 다양한 하드웨어용 오픈소스 Qt5/OpenGL 3.0+ SDR·신호 분석 프론트엔드.
* [GQRX](https://github.com/gqrx-sdr/gqrx) - GNU Radio와 Qt 기반 SDR 수신기.
* [SDR# (SDRSharp)](https://airspy.com/download/) - 인기 있고 저렴한 SDR(소프트웨어 정의 무선)인 Airspy 관련 다운로드.
* [UberTooth One](https://github.com/greatscottgadgets/ubertooth) - 블루투스 실험에 적합한 오픈소스 2.4 GHz 무선 개발 플랫폼.
* [Bluefruit LE Sniffer](https://www.adafruit.com/product/2269) - 사용하기 쉬운 Bluetooth Low Energy 스니퍼.
* [DragonOS](https://cemaxecuter.com/) - 셀룰러 도구가 미리 설치된 Ubuntu 기반 SDR 배포판.
* [RTL-SDR](https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/) - 입문자에게 저렴한 SDR. 500 kHz~1.75 GHz 대역의 라디오 신호를 수신하는 PC 연동 스캐너.
* [HackRF One](https://github.com/greatscottgadgets/hackrf) - 1 MHz~6 GHz 송수신(반이중)이 가능한 SDR 주변기기.
* [YardStick One](https://greatscottgadgets.com/yardstickone/) - 반이중 1 GHz 미만 무선 송수신기.
* [LimeSDR](https://www.crowdsupply.com/lime-micro/limesdr) - 100 kHz~3.8 GHz 송수신(전이중) SDR 주변기기.
* [BladeRF 2.0](https://www.nuand.com/bladerf-2-0-micro/) - 47 MHz~6 GHz 송수신(전이중) SDR 주변기기.
* [USRP B Series](https://www.ettus.com/product-categories/usrp-bus-series/) - 70 MHz~6 GHz 송수신(전이중) SDR 주변기기.
* [ApiMote](https://apimote.com/) - IEEE 802.15.4/ZigBee 보안 학습·평가용 ZigBee 보안 연구 하드웨어. Killerbee 호환.
* [Killerbee](https://github.com/riverloopsec/killerbee) - ZigBee·IEEE 802.15.4 네트워크 테스트·감사 프레임워크.
* [zigdiggity](https://github.com/BishopFox/zigdiggity) - Bishop Fox의 ZigBee 해킹 툴킷.

<a id="common-telemetry-radios"></a>
### 일반 조종·텔레메트리 무선
* [RFD900X / RFD868X](https://files.rfdesign.com.au/Files/documents/RFD900x%20DataSheet%20V1.2.pdf) - 902–928 MHz 또는 865–870 MHz 대역에서 동작하는 장거리 무선 데이터 모뎀.
* [3DR SiK Radio](https://store.3dr.com/3dr-sik-air-telemetry-radio-kit/) - SIK 에어 텔레메트리 무선 키트.
* [mRo SiK Radios](https://mrobotics.io/docs/mro-sik-telemetry-radio-v2/) - mRo SiK 텔레메트리 무선 V2.
* [Holybro Sik Radios](https://holybro.com/products/sik-telemetry-radio-v3?srsltid=AfmBOorDhmwntjJAQDArI1vKzOLlMTaVHsFBltXve9pSeBN4d9LgGvDA) - SiK 텔레메트리 무선 V3.
* [Microhard Telemetry Radios](https://docs.px4.io/main/en/telemetry/microhard_serial.html) - 900 MHz/840 MHz/410–480 MHz 대역 FHSS 시리얼 무선, 약 60 km, 메시/포인트투포인트.
* [ExpressLRS](https://www.expresslrs.org/) - 10 ms 미만 지연의 양방향 MAVLink 패스스루를 지원하는 오픈소스 RC 링크(FPV 조종사·DIY UAV에 인기).
* [TBS Crossfire](https://www.team-blacksheep.com/products/prod:crossfire_tx?srsltid=AfmBOoqZ42ooZ6riBbs-Dec_6hXpMLN2u2njFGDQ5YWaFtzroDmUrZ0r) - Team Black Sheep Crossfire TX — 장거리 R/C 송신기.

<a id="-wi-fi-communications"></a>
## 📶 Wi‑Fi 통신

<a id="wi-fi-detection--infiltration-tools"></a>
### Wi‑Fi 탐지·침투 도구
* [Aircrack-ng](https://aircrack-ng.org) - 디인증·WPA 크래킹 툴킷.
* [Bettercap](https://github.com/bettercap/bettercap) - 드론 앱 트래픽 탈취용 MITM 프레임워크.
* [WifiPhisher](https://github.com/wifiphisher/wifiphisher) - 드론 앱 자격 증명 피싱용 자동 Evil Twin.
* [DangerDrone](https://resources.bishopfox.com/resources/tools/drones-penetration-testers/attack-tools/) - Black Hat 2016에서 발표된 DIY 침투 테스트 쿼드콥터 플랫폼.
* [WASP](https://www.suasnews.com/2010/08/wi-fi-aerial-surveillance-platform-wasp/) - 무선 공중 감시 플랫폼.
* [Hack-a-drone](https://github.com/Ordina-JTech/hack-a-drone?tab=readme-ov-file) - 앱·키보드로 Wi‑Fi 드론(예: Cheerson CX‑10)을 제어하는 Java 프로젝트로 원격 명령 능력을 시연.

<a id="common-wi-fi-protocols--equipment"></a>
### 일반 Wi‑Fi 프로토콜 및 장비
* [WFB-ng](https://github.com/svpcom/wfb-ng) - FPV 드론용 저지연 UDP Wi‑Fi 브로드캐스트.
* [OpenIPC](https://openipc.org/) - IP 카메라를 저비용 FPV 링크로 바꾸는 오픈 펌웨어.
* [RubyFPV](https://rubyfpv.com/) - Wi‑Fi 동글용 크로스플랫폼 디지털 FPV 스택.
* [RunCam WifiLink](https://shop.runcam.com/runcam-wifilink-based-on-openipc/) - 오픈 프로토콜 문서가 있는 5.8 GHz Wi‑Fi FPV 어댑터.

<a id="-fpv--payloads"></a>
## 📺 FPV 및 페이로드

<a id="video-eavesdropping"></a>
### 영상 탐지·도청
* [FPV DETECTION](https://github.com/Payalo64/FPV_DETECTED_1.2_5.8GHZ) - 최대 약 1.6 km 범위의 Raspberry Pi Pico 기반 FPV 탐지 도구.
* [RX5808 Pro Diversity](https://github.com/sheaivey/rx5808-pro-diversity) - 안테나 다이버시티를 갖춘 DIY 5.8 GHz FPV 영상 수신 스테이션.
* [Meshtastic Detection Node (Drone Detection)](https://www.tindie.com/products/thewolfblitz7/fpv-meshtastic-detection-node-drone-detection/) - 5.8 GHz FPV 아날로그 영상 송신을 탐지·알리는 메시 노드. Meshtastic·시리얼 USB로 알림.
* [TVSharp](https://github.com/linuxuser2064/TVSharper) - RTL-SDR용 아날로그 TV 디코더(개선판).

<a id="video-jamming-spoofing--tampering"></a>
### 영상 재밍·스푸핑·변조
* [HackTV](https://github.com/fsphil/hacktv) - HackRF용 아날로그 TV 송신기.

<a id="-bvlos-communications"></a>
## 📡 BVLOS(시계 외) 통신

<a id="cellular-analysis--tampering-tools"></a>
### 셀룰러 분석·변조 도구
* [LTE-Cell-Scanner](https://github.com/Evrytania/LTE-Cell-Scanner) - LTE 기지국 탐지·분석.
* [gr-gsm](https://github.com/ptrkrysik/gr-gsm) - GNU Radio 기반 GSM 분석.
* [QCSuper](https://github.com/P1sec/QCSuper) - 퀄컴 폰으로 2G–4G 트래픽 캡처.
* [5GBaseChecker](https://github.com/SyNSec-den/5GBaseChecker) - 5G 베이스밴드 구현 취약점 탐지 도구(2024).
* [FALCON LTE](https://github.com/falkenber9/falcon) - 실시간 분석을 위한 LTE 제어 채널 고속 분석.
* [Kalibrate](https://github.com/scateu/kalibrate-hackrf) - GSM 기지국 스캐너 및 주파수 보정 도구.
* [LTE Sniffer](https://github.com/SysSec-KAIST/LTESniffer) - 오픈소스 LTE 다운링크/업링크 도청기.
* [OsmocomBB](https://github.com/korczis/osmocom-bb) - 휴대폰 베이스밴드 프로세서용 자유 펌웨어.
* [Modmobmap](https://github.com/Synacktiv-contrib/Modmobmap) - 모바일 네트워크 매핑.
* [Modmobjam](https://github.com/Synacktiv-contrib/Modmobjam) - 모바일 재밍 연구.

<a id="common-bvlos-equipment"></a>
### 일반 BVLOS 장비
* [CUAV SR 4/5G Link](https://doc.cuav.net/link/lte-link/en/) - CUAV가 독자 지원하는 UAV용 LTE LINK 시리즈 통신 링크.
* [Iridium RockBlock](https://docs.px4.io/main/en/advanced_features/satcom_roadblock.html) - 위성 통신 모듈.
* [Cloud Walker](https://www.cloudwalkerfpv.com/) - 광섬유 디지털 통신 모듈.
* [OpenBTS](https://github.com/PentHertz/OpenBTS) - 최신 UHD 드라이버와 Ubuntu 22.04·24.04 지원으로 2024–2025에 갱신된 GSM+GPRS RAN 노드.
* [LimeNET CrowdCell](https://limemicro.com/) - 소형 셀 구축을 위한 LimeSDR 통합 네트워크 인 어 박스 솔루션.
* [Magma Core Network](https://github.com/magma) - 리눅스 재단 산하로 이전된 Meta의 분산 패킷 코어.

<a id="-protocols--middleware-tools"></a>
## 🤖 프로토콜 및 미들웨어 도구
* [MAVLink](https://github.com/mavlink/mavlink) - 드론용 마샬링·통신 라이브러리.
* [MAVSDK](https://github.com/mavlink/MAVSDK) - C++17로 작성된 MAVLink 호환 시스템용 API·라이브러리.
* [ROS](https://www.ros.org/) - 오픈소스 로봇 운영체제(ROS).
* [MAVROS](https://github.com/mavlink/mavros) - 지상국(GCS)용 프록시가 있는 MAVLink–ROS 게이트웨이.
* [MAVLink Router](https://github.com/mavlink-router/mavlink-router) - 엔드포인트 간 MAVLink 패킷 라우팅.

<a id="protocol-analysis--tampering"></a>
### 프로토콜 분석·변조
* [MAVSploit](https://github.com/Rud3m/MavSploit) - MAVLink 통신 프로토콜 취약점 식별·악용에 특화된 모의 침투 툴킷.
* [MAVLink Wireshark PLugin](https://mavlink.io/en/guide/wireshark.html) - Wireshark에서 MAVLink 메시지 파싱.
* [aztarna](https://github.com/aliasrobotics/aztarna) - ROS 풋프린팅 도구.

<a id="-autopilot-firmware"></a>
## 💽 자동조종 펌웨어
* [ArduPilot](https://ardupilot.org/) - 다양한 기체를 지원하는 신뢰도 높고 범용적인 오픈소스 자동조종 시스템.
* [PX4](https://px4.io/) - 드론 개발자를 위한 오픈소스 자동조종 장치(원문 오타: fro=for).
* [iNav](https://github.com/iNavFlight/inav) - 항법 기능이 있는 비행 제어 소프트웨어.
* [Betaflight](https://github.com/betaflight/betaflight) - FPV 드론용 오픈소스 비행 제어기 펌웨어.

<a id="firmware-analysis"></a>
### 펌웨어 분석
* [Binwalk](https://github.com/ReFirmLabs/binwalk) - 바이너리에서 "흥미로운" 내용을 찾고 임의 파일을 추출.
* Firmware Analysis Toolkit
* [cwe_checker](https://github.com/fkie-cad/cwe_checker) - 바이너리 실행 파일의 취약 패턴 탐지 — x86, ARM, MIPS ELF 지원, 실험적 베어메탈 지원.
* [emba](https://github.com/e-m-b-a/emba) - 임베디드 기기의 리눅스 기반 펌웨어 분석.
* [Firmwalker](https://github.com/craigz28/firmwalker) - 추출된 펌웨어 이미지에서 유용한 파일·정보 검색.
* [Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap) - 콘콜릭 분석·함수 클러스터링으로 펌웨어 취약점 발견.
* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) - 소프트웨어 리버스 엔지니어링 스위트. CPU 아키텍처와 엔디안을 알면 임의 바이너리 처리.
* [Radare2](https://github.com/radareorg/radare2) - 리버스 엔지니어링 프레임워크. 일반 포맷·임의 바이너리 처리, 풍부한 CLI.
* [Trommel](https://github.com/CERTCC/trommel) - 추출된 펌웨어 이미지에서 유용한 파일·정보 검색.
* [JTAGenum](https://github.com/cyphunk/JTAGenum) - 아두이노에 JTAG 기능 추가.
* [OpenOCD](https://openocd.org/) - 자유·오픈 온칩 디버깅, ISP, 경계 스캔 테스트.

<a id="firmware-extraction"></a>
### 펌웨어 추출
* [DJI Firmware Tools](https://github.com/o-gs/dji-firmware-tools) - DJI 드론 펌웨어 모듈 추출·수정·재빌드 유틸리티 — 보정, 파라미터 편집, 분석용 재패키징 포함.
* [FACT Extractor](https://github.com/fkie-cad/fact_extractor) - 컨테이너 포맷을 자동 탐지해 해당 추출 도구 실행.
* [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit) - 여러 컨테이너 포맷 추출 도구.
* [The SRecord package](https://srecord.sourceforge.net/) - EPROM 파일 조작 도구 모음(다양한 바이너리 포맷 변환).
* [Cotopaxi](https://github.com/Samsung/cotopaxi) - 특정 IoT 네트워크 프로토콜을 이용한 사물인터넷 기기 보안 테스트 도구 모음.
* [dumpflash](https://github.com/ohjeongwook/dumpflash) - 저수준 NAND 플래시 덤프·파싱 유틸리티.
* [flashrom](https://github.com/flashrom/flashrom) - 플래시 칩 탐지·읽기·쓰기·검증·삭제 도구.
* [Samsung Firmware Magic](https://github.com/chrivers/samsung-firmware-magic) - 삼성 SSD 펌웨어 업데이트 복호화.

<a id="firmware-modification"></a>
### 펌웨어 수정
* [WAF](https://github.com/ArduPilot/waf) - Python 기반 ArduPilot 펌웨어 컴파일러.
* [DJI FC Patcher](https://github.com/o-gs/DJI_FC_Patcher) - 다양한 DJI 드론용 커스텀 FC 패처 및 플래싱.

<a id="-companion-computers"></a>
## 🧠 컴패니언 컴퓨터

<a id="companion-network-analysis"></a>
### 컴패니언 네트워크 분석
* [Wireshark](https://www.wireshark.org/) - 네트워크 트래픽 분석기.
* [NMAP](https://nmap.org/) - 네트워크 매핑 도구.

<a id="companion-web-application-attacking"></a>
### 컴패니언 웹 애플리케이션 공격
* [BurpSuite](https://portswigger.net/) - 웹 애플리케이션 보안 테스트 도구. 자동 테스트·외부 플러그인 제공.

<a id="-ground-control-stations"></a>
## 🛫 지상국(GCS)
* [QGround Control](https://github.com/mavlink/qgroundcontrol) - 드론용 크로스플랫폼 지상국.
* [Mission Planner](https://ardupilot.org/planner/) - Windows용 GCS 소프트웨어.
* [MAVProxy](https://github.com/ArduPilot/MAVProxy) - CLI 기반 GCS 소프트웨어.

<a id="-mobile-gcs-apps"></a>
## 📱 모바일 GCS 앱
* [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - 자동화된 올인원 모바일 앱 해킹 프레임워크.
* [ADB Toolkit](https://github.com/ASHWIN990/ADB-Toolkit) - 다양한 ADB 기능을 한곳에 모은 ADB-Toolkit V2.
* [Androguard](https://github.com/androguard/androguard) - Android 앱 리버스 엔지니어링·모의 침투.
* [Apktool](https://github.com/iBotPeaches/Apktool) - Android APK 리버스 엔지니어링 도구.
* [Dex2Jar](https://github.com/pxb1988/dex2jar) - Android .dex와 Java .class 파일 작업 도구.
* [Enjarify](https://github.com/Storyyeller/enjarify) - Dalvik 바이트코드를 동등한 Java 바이트코드로 변환해 Java 분석 도구로 Android 앱을 분석.

<a id="-artifical-intelligence-libraries"></a>
## 🧠 인공지능 라이브러리
* [OpenCV](https://github.com/opencv/opencv) - 오픈소스 컴퓨터 비전 라이브러리.

<a id="-vendor-specific-research"></a>
## 🏢 제조사별 연구

<a id="dji"></a>
### DJI
* [Drone-ID Receiver for DJI OcuSync 2.0](https://github.com/RUB-SysSec/DroneSecurity)
* [DroneXtract](https://github.com/ANG13T/DroneXtract) - DJI 드론용 디지털 포렌식 스위트.
* [DJI Drone ID](https://github.com/proto17/dji_droneid) - SDR 기반 디코더로 DJI 전용 DroneID RF 버스트를 복조하고 MATLAB/Octave 스크립트로 임의 DroneID 프레임 생성.
* [Drone Hacks](https://drone-hacks.com/) - 구매형 DJI 드론 해킹 도구.
* [dji_rev](https://github.com/fvantienen/dji_rev) - DJI 리버스 엔지니어링 툴킷.
* [deejaeye-Modder](https://github.com/Bin4ry/deejayeye-modder) - DJI 드론 펌웨어 모딩 도구.
* [pyduml](https://github.com/hdnes/pyduml) - Python 기반 DUML("DJI Universal Markup Language") 익스플로잇 및 펌웨어 업·다운그레이드 도구.
* [RedHerring](https://github.com/MAVProxyUser/P0VsRedHerring) - FTPD 디렉터리 트래버설 0day.
* [DUMLrub](https://github.com/MAVProxyUser/DUMLrub) - PyDUML의 Ruby 포트.
* [DUMLdore](https://github.com/jezzab/DUMLdore) - DJI 펌웨어 플래싱 도구 v3.20.
* [No Limit Drones](https://nolimitdronez.com/) - 구매형 DJI 드론 해킹 도구.

<a id="parrot"></a>
### Parrot
* [SkyJack](https://github.com/samyk/skyjack) - 다른 Parrot·3DR 드론을 자동으로 찾아 해킹하고 무선으로 완전 제어하는 데 쓰인 드론 소스.
* [DroneJack](https://github.com/brospars/wic-ter-dronejack) - Parrot 드론을 제어하는 Node 웹 애플리케이션.
* [Maldrone](https://www.youtube.com/watch?v=5SlWdl4ZuAI) - 드론용 최초의 백도어(영상).

<a id="misc"></a>
### 기타
* [DroneSploit](https://github.com/dronesploit/dronesploit) - 드론 모의 침투 프레임워크 콘솔.
* [Drone Duel](https://github.com/marcnewlin/drone-duel) - 2016 Great Drone Duel에 사용된 코드.
* [Drone-Hacking-Tool](https://github.com/HKSSY/Drone-Hacking-Tool) - USB Wi‑Fi 어댑터와 HackRF One으로 드론 해킹에 쓰는 GUI 도구.
* [Snoopy](https://github.com/sensepost/Snoopy) - 분산 추적·데이터 가로채기 프레임워크.


<a id="-research-papers--blog-articles"></a>
## 📚 연구 논문 및 블로그 글
* [Vulnerability Analysis of the MAVLink Protocol for Command and Control of Unmanned Aircraft](https://apps.dtic.mil/sti/citations/ADA598977) - MAVLink C2 메시지의 기밀성·무결성·가용성 결함을 분석해 UAV 임무에 대한 맞춤 공격을 가능하게 한다는 DoD/AFIT 기술 보고.
* [How to Set Up A Drone Vulnerability Testing Lab](https://medium.com/@swalters/how-to-set-up-a-drone-vulnerability-testing-lab-db8f7c762663) - 장난감·취미용 드론과 RC로 100달러 미만 홈 드론 보안 랩을 꾸리는 방법을 담은 Medium 가이드(DJI·Futaba 등으로 확장 가능).
* [GPS Jamming Techniques for UAVs using Low-Cost SDR Platforms](https://www.researchgate.net/publication/339824302_Effective_GPS_Jamming_Techniques_for_UAVs_Using_Low-Cost_SDR_Platforms) - BladeRF/GNU Radio SDR로 UAV 항법을 방해할 수 있는 GPS 간섭을 생성할 수 있음을 보인 연구 논문.
* [Unmanned Aircraft Capture and Control via GPS Spoofing](https://rnl.ae.utexas.edu/images/stories/files/papers/unmannedCapture.pdf) - 특정 조건에서 기만적 GPS 신호 주입으로 UAV 탈취를 시연한 선구적 연구.
* [Drone Detection and Tracking Using RF Identification Signals](https://www.mdpi.com/1424-8220/23/17/7650) - 개발보드 RF 시스템으로 Drone‑ID 텔레메트리를 복호화하고 여러 DJI 기종에서 최대 약 3.7 km 탐지 거리를 보고한 MDPI 연구.

<a id="-osint--intelligence"></a>
## 🔍 OSINT 및 인텔리전스
* [The Drone Database](https://drones.cnas.org/drones/) - 전 세계 드론에 대한 상세 정보. 연구·분석·역량 파악에 유용.
* [DJI Hardware Schematics](https://github.com/o-gs/dji-hardware-schematics) - 다양한 DJI 드론 보드용 커뮤니티 공유 KiCad 회로도·PCB(오류 가능, 보증 없음).
* [DJI Packet Dumps](https://github.com/o-gs/dji-packet-dumps) - Wireshark 프로토콜 분석에 유용한 DJI 하드웨어 통신 로그 PCAP 모음.

<a id="-exploits-cves--vulnerabilities"></a>
## 💥 익스플로잇, CVE 및 취약점
* [Exploit Database](https://www.exploit-db.com/) - 모의 침투자·연구자를 위한 대규모 공개 CVE 준수 익스플로잇·PoC 저장소.
* [Robot Vulnerability Database](https://github.com/aliasrobotics/RVD) - Alias Robotics가 큐레이션한 RVSS 점수가 있는 로봇/ROS 취약점 아카이브.

<a id="-vulnerability-disclosure-programs"></a>
## 📣 취약점 공개·신고 프로그램
* [DJI](https://security.dji.com) - 약 50달러에서 최대 약 3만 달러 규모 포상을 제공하는 DJI 공식 프로그램.
* [Parrot](https://www.parrot.com/en/newsroom/parrot-launches-its-bug-bounty-partnership-yeswehack) - Parrot의 단계적 YesWeHack 버그 바운티 프로그램.
* [PX4](https://github.com/PX4/PX4-Autopilot/blob/main/SECURITY.md) - PX4 보안 정책.
* [ArduPilot](https://github.com/ArduPilot/MethodicConfigurator/security) - ArduPilot 취약점 공개 절차.
* [QGround Control](https://github.com/mavlink/qgroundcontrol/security) - QGroundControl 취약점 공개 절차.
* [Autel Robotics](https://www.autelrobotics.com/protocol/) - Autel Robotics 취약점 공개.
* [ROS](https://ros.org/reps/rep-2006.html) - ROS 취약점 공개 정책.
* [DroneDeploy](https://help.dronedeploy.com/hc/en-us/articles/1500004862001-Vulnerability-Reporting-Policy) - DroneDeploy 취약점 신고 정책.
* [Zipline](https://www.zipline.com/zipline-vulnerability-disclosure-policy) - Zipline 취약점 공개 정책.
* [IRIS Automation / uAvioni](https://www.irisonboard.com/responsible-disclosure/) - IRIS Automation / uAvioni 취약점 공개.
* [Ameta](https://ametasmart.com/pages/ameta-vulnerability-disclosure-policy) - Ameta 취약점 공개 정책.
* [Ouster](https://ouster.com/responsible-disclosure-policy) - Ouster 책임 공개 정책.

<a id="-training--education"></a>
## 🎓 교육 및 훈련
* [DSOC - DronSec Courses](https://training.dronesec.com/) - 드론 공격 작전·적대 행위 tradecraft 마스터 과정.
* [DarkWolf Drone Playbook](https://dronewolf.darkwolf.io/) - Dark Wolf Solutions가 개발한 드론 해킹 플레이북.

<a id="-communities"></a>
## 🗣️ 커뮤니티
* [Dronecode foundation](https://dronecode.org/) - MAVLink, QGroundControl, PX4의 본거지(리눅스 재단 산하).
* [FPV Freedom Coalation](https://fpvfc.org/) - 드론을 해킹 가능하고 안전하게(원문: hackabel).
* #DeejayeyeHackingClub

<a id="who-to-follow"></a>
### 팔로우 추천

<a id="medium"></a>
#### Medium
* [Sander Walters](https://medium.com/@swalters)

<a id="xtweeter"></a>
#### X(트위터)
* [d0tslash](https://x.com/d0tslash)

<a id="additional-resources"></a>
## 추가 자료
* [Awesome-Drones](https://github.com/janesmae/awesome-drones) - 엄선된 Awesome Drones 자료 목록.
* [Awesome-Flying-FPV](https://github.com/Matthias84/awesome-flying-fpv) - Awesome Flying FPV 목록.

<a id="-legal-notice"></a>
## ⚖️ 법적 고지
이 저장소는 교육 및 연구 목적으로만 제공됩니다. 이용자는 관련 법령을 준수할 책임이 있으며, 유지 관리자는 불법 행위를 조장하거나 지지하지 않습니다.
