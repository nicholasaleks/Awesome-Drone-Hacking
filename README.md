<!--lint disable awesome-toc-->
# Awesome Drone Hacking [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

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
  <strong>A list of awesome drone hacking tools & resources.</strong><br/>

  <img
   src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/blob/main/Awesome-Drone-Hacking-Banner.png?raw=true"
   alt="Awesome Drone Hacking List Logo" />

  This repository covers tools, techniques, and research for hacking open-source,
  autonomous, FPV (First-Person View), and proprietary drone systems—from telemetry
  and flight control to hardware, firmware, and communication protocols.
</p>

### Legend

* 🌟: Most Awesome
* 💰: Costs Money
* 👻: Outdated / Archived
<!-- markdownlint-enable MD033 -->

---

## 📚 Table of Contents
<!--lint disable awesome-list-item-->
* [🔬 Drone Hacking Labs, CTFs & Workshops](#-drone-hacking-labs-ctfs--workshops)
* [🎤 Conference Talks & Videos](#-conference-talks--videos)
* [💿 Real-Time Operating Systems](#-real-time-operating-systems)
  * [Fuzzing & Analysis Tools](#fuzzing--analysis-tools)
  * [Emulators](#emulators)
* [🔌 Flight Controller & Embedded Systems](#-flight-controller--embedded-systems)
  * [Embedding Hacking Tools](#embedding-hacking-tools)
  * [Common Flight Controller & Embedded System Resources](#common-flight-controller--embedded-system-resources)
* [📻 Radio & Telemetry](#-radio--telemetry)
  * [Remote Identification Discovery & Spoofing Tools](#remote-identification-discovery--spoofing-tools)
  * [Telemetry Detection & Eavesdropping Tools](#telemetry-detection--eavesdropping-tools)
* [Misc RF Tools](#misc-rf-tools)
  * [Common Telemetry Radios](#common-telemetry-radios)
* [📶 Wi-Fi Communications](#-wi-fi-communications)
  * [Wi-Fi Detection & Infiltration Tools](#wi-fi-detection--infiltration-tools)
  * [Common Wi-Fi Protocols & Equipment](#common-wi-fi-protocols--equipment)
* [📺 FPV & Payloads](#-fpv--payloads)
  * [Video Eavesdropping](#video-eavesdropping)
* [📡 BVLOS Communications](#-bvlos-communications)
  * [Cellular Analysis & Tampering Tools](#cellular-analysis--tampering-tools)
  * [Common BVLOS Equipment](#common-bvlos-equipment)
* [🤖 Protocols & Middleware Tools](#-protocols--middleware-tools)
  * [Protocol Analysis & Tampering](#protocol-analysis--tampering)
* [💽 Autopilot Firmware](#-autopilot-firmware)
  * [Firmware Analysis](#firmware-analysis)
  * [Firmware Extraction](#firmware-extraction)
  * [Firmware Modification](#firmware-modification)
* [🧠 Companion Computers](#-companion-computers)
* [🛫 Ground Control Stations](#-ground-control-stations)
* [📱 Mobile GCS Apps](#-mobile-gcs-apps)
* [🧠 Artifical Intelligence Libraries](#-artifical-intelligence-libraries)
* [🏢 Vendor-Specific Research](#-vendor-specific-research)
  * [DJI](#dji)
  * [Parrot](#parrot)
  * [Misc](#misc)
* [📚 Research Papers & Blog Articles](#-research-papers--blog-articles)
* [🔍 OSINT & Intelligence](#-osint--intelligence)
* [💥 Exploits, CVEs & Vulnerabilities](#-exploits-cves--vulnerabilities)
* [📣 Vulnerability Disclosure Programs](#-vulnerability-disclosure-programs)
* [🎓 Training & Education](#-training--education)
* [🗣️ Communities](#-communities)
* [Additional Resources](#additional-resources)
* [⚖️ Legal Notice](#-legal-notice)
<!--lint enable awesome-list-item-->

## 🔬 Drone Hacking Labs, CTFs & Workshops
* [Damn Vulnerable Drone (DVD)](https://github.com/nicholasaleks/Damn-Vulnerable-Drone) - Docker-based virtual drone hacking simulator.
* [Hack Our Drone Workshop](https://dronewolf.darkwolf.io/workshop) - Dark Wolf Hack Our Drone Workshop.
* [Drone Wars, BloomCon](https://www.commonwealthu.edu/offices-directory/mathematics-computer-science-and-digital-forensics/drone-wars-competition) - Collegiate arena where teams hijack Wi‑Fi drones and race them through obstacles.
* [Hack The Drone](http://hackthedrone.org/eng/index.php) - International Drone Hacking Competition, Korea Drone Security Association.

## 🎤 Conference Talks & Videos
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

## 💿 Real-Time Operating Systems

### Fuzzing & Analysis Tools
* [Fuzzware](https://github.com/fuzzware-fuzzer/fuzzware) - The target orchestration framework with focus on dynamic analysis of embedded devices' firmware.
* [Avatar² Framework](https://github.com/avatartwo/avatar2) - Fuzzware is a project for automated, self-configuring fuzzing of firmware images.
* [American Fuzzy Lop plus plus](https://github.com/AFLplusplus/AFLplusplus) - AFL with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more!

## Emulators
* [QEMU](https://www.qemu.org/) - A generic and open source machine emulator and virtualizer.
* [Renode](https://github.com/renode/renode) - Antmicro's open source simulation and virtual development framework for complex embedded systems. Supports many [STM32](https://github.com/renode/renode/blob/master/platforms/cpus/stm32f4.repl) series chips.

### Common RTOS
* [NuttX](https://nuttx.apache.org/) - NuttX RTOS, used by PX4.
* [ChibiOS](https://www.chibios.org/dokuwiki/doku.php) - ChibiOS RTOS, used by ArduPilot.

## 🔌 Flight Controller & Embedded Systems

### Embedding Hacking Tools
* [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - Detects and interacts with hardware debug ports like UART and JTAG.
* [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Detects and interacts with hardware debug ports like UART and JTAG.
* [Tigard](https://www.crowdsupply.com/securinghw/tigard) - An open source FT2232H-based, multi-protocol, multi-voltage tool for hardware hacking.
* [JTAGULATOR](https://grandideastudio.com/portfolio/security/jtagulator/) - Detects JTAG Pinouts fast.
* [Saleae](https://www.saleae.com/) - Easy to use Logic Analyzer that support many protocols.
* [Ikalogic](https://www.ikalogic.com/sp209-logic-analyzer/) - Alternative to Saleae logic analyzers.
* [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/?v=0b3b97fa6688) - Open source multi-tool hardware similar to the BusPirate but with NFC capabilities.
* [ChipWhisperer](https://www.newae.com/chipwhisperer) - Detects Glitch/Side-channel attacks.
* [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) - Tool for exploring and debugging different digital interfaces.
* [J-Link](https://www.segger.com/products/debug-probes/j-link/) - J-Link offers USB powered JTAG debug probes for multiple different CPU cores.

### Common Flight Controller & Embedded System Resources
* [STM32](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html) - 32-bit Arm Cortex MCUs.
* [AT32](https://www.arterychip.com/en/product/AT32F425.jsp) - 32-bit Cortex-M4 microcontroller MUCs.
* [Pixhawk](https://pixhawk.org/) - Open source hardware flight controller.
* [Cube](https://www.cubepilot.com/#/home) - Modular flight controller hardware.
* [DJI A3](https://www.dji.com/ca/a3) - A commercial-grade flight controller offering triple-redundant IMUs and advanced fail-safes for industrial multirotors.
* [DJI N3](https://www.dji.com/ca/n3) - A flight controller designed for professional aerial cinematography, optimized for integration with the DJI Inspire 2 and Lightbridge 2.
* [CUAV X7 & V5+](https://ardupilot.org/copter/docs/common-cuav-x7-family-overview.html) - High-performance ArduPilot flight controllers with rich I/O and robust sensor redundancy.
* [Holybro Kakute F7/H7](https://holybro.com/products/kakute-h7-v2?srsltid=AfmBOorAjpi2nnbfkXOsFjFxvt8UiLFDPlo7vlpXIBhJMvUBZDkQ2fqW) - Compact Betaflight-compatible flight controllers popular in racing and freestyle drones.
* [PX4 Wiring Diagram](https://docs.px4.io/main/en/assembly/quick_start_pixhawk5x.html) - Official reference diagram for wiring Pixhawk 5X flight controllers running PX4.

## 📻 Radio & Telemetry

### Remote Identification Discovery & Spoofing Tools
* [DragonSync-iOS](https://github.com/Root-Down-Digital/DragonSync-iOS) - Real-time Remote/Drone ID–compliant drone detection and monitoring on iOS/macOS.
* [RemoteID Spoofer](https://github.com/jjshoots/RemoteIDSpoofer) - An ESP8266/NodeMCU tool that simulates up to 16 fake Remote ID–broadcasting drones around a GPS location via Wi‑Fi for Red Team testing.
* [WiFi RID capture](https://github.com/sxjack/unix_rid_capture) - A Linux tool that listens for ASTM F3411 (Wi‑Fi/Bluetooth) Remote ID frames and logs real UAV positions in JSON for monitoring or analysis.
* [DJI DroneID Detection](https://www.crowdsupply.com/microphase-technology/antsdr-e200/updates/dji-droneid-detection) - FPGA-based software-defined radio based on the ZYNQ and AD936x chipsets.

### Telemetry Detection & Eavesdropping Tools
* [SiKW00F](https://github.com/nicholasaleks/sikw00f) - SiK Radio Detection & MAVLink Telemetry Eavesdropping Toolkit.
* [SiKening](https://github.com/MAVProxyUser/SiKening) - 3DR Radio SiKening PoC by Meatball Ninja - Brute force 3DR NetID and sync up with hopping sequence.

## Misc RF Tools
* [GNURadio](https://github.com/gnuradio/gnuradio) - Free and Open Software Radio Ecosystem.
* [SigDigger](https://github.com/BatchDrake/SigDigger) - Free digital signal analyzer.
* [SDRangel](https://github.com/f4exb/sdrangel) - Open-source Qt5 / OpenGL 3.0+ SDR and signal analyzer frontend to various hardware.
* [GQRX](https://github.com/gqrx-sdr/gqrx) - Software defined radio receiver powered by GNU Radio and Qt.
* [SDR# (SDRSharp)](https://airspy.com/download/) - Airspy is a popular, affordable SDR (software defined radio.
* [UberTooth One](https://github.com/greatscottgadgets/ubertooth) - Open source 2.4 GHz wireless development platform suitable for Bluetooth experimentation.
* [Bluefruit LE Sniffer](https://www.adafruit.com/product/2269) - Easy to use Bluetooth Low Energy sniffer.
* [DragonOS](https://cemaxecuter.com/) - Ubuntu-based SDR distribution with preinstalled cellular tools.
* [RTL-SDR](https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/) - Cheapest SDR for beginners. It is a computer based radio scanner for receiving live radio signals frequencies from 500 kHz up to 1.75 GHz.
* [HackRF One](https://github.com/greatscottgadgets/hackrf) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 1 MHz to 6 GHz (half-duplex).
* [YardStick One](https://greatscottgadgets.com/yardstickone/) - Half-duplex sub-1 GHz wireless transceiver.
* [LimeSDR](https://www.crowdsupply.com/lime-micro/limesdr) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 100 KHz to 3.8 GHz (full-duplex).
* [BladeRF 2.0](https://www.nuand.com/bladerf-2-0-micro/) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 47 MHz to 6 GHz (full-duplex).
* [USRP B Series](https://www.ettus.com/product-categories/usrp-bus-series/) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 70 MHz to 6 GHz (full-duplex).
* [ApiMote](https://apimote.com/) - ZigBee security research hardware for learning about and evaluating the security of IEEE 802.15.4/ZigBee systems. Killerbee compatible.
* [Killerbee](https://github.com/riverloopsec/killerbee) - Framework for Testing & Auditing ZigBee and IEEE 802.15.4 Networks.
* [zigdiggity](https://github.com/BishopFox/zigdiggity) - A ZigBee hacking toolkit by Bishop Fox.

### Common Control & Telemetry Radios
* [RFD900X / RFD868X](https://files.rfdesign.com.au/Files/documents/RFD900x%20DataSheet%20V1.2.pdf) - Long-range radio data modem operating in the 902-928MHzor 865-870MHz frequency band.
* [3DR SiK Radio](https://store.3dr.com/3dr-sik-air-telemetry-radio-kit/) - SIK Air Telemetry Radio kit.
* [mRo SiK Radios](https://mrobotics.io/docs/mro-sik-telemetry-radio-v2/) - mRo SiK Telemetry Radio V2.
* [Holybro Sik Radios](https://holybro.com/products/sik-telemetry-radio-v3?srsltid=AfmBOorDhmwntjJAQDArI1vKzOLlMTaVHsFBltXve9pSeBN4d9LgGvDA) - SiK Telemetry Radio V3.
* [Microhard Telemetry Radios](https://docs.px4.io/main/en/telemetry/microhard_serial.html) - FHSS serial radios in 900 MHz/840 MHz/410–480 MHz bands; ~60 km range, mesh/point‑to‑point.
* [ExpressLRS](https://www.expresslrs.org/) - Open-source RC link that now supports bidirectional MAVLink passthrough with sub-10 ms latency—favoured by FPV pilots and DIY UAVs.
* [TBS Crossfire](https://www.team-blacksheep.com/products/prod:crossfire_tx?srsltid=AfmBOoqZ42ooZ6riBbs-Dec_6hXpMLN2u2njFGDQ5YWaFtzroDmUrZ0r) - Team Black Sheep Crossfire TX - Long Range R/C Transmitter.

## 📶 Wi-Fi Communications

### Wi-Fi Detection & Infiltration Tools
* [Aircrack-ng](https://aircrack-ng.org) - Deauth and WPA cracking toolkit.
* [Bettercap](https://github.com/bettercap/bettercap) - MITM framework to hijack drone app traffic.
* [WifiPhisher](https://github.com/wifiphisher/wifiphisher) - Automated Evil Twin to phish Drone app creds.
* [DangerDrone](https://resources.bishopfox.com/resources/tools/drones-penetration-testers/attack-tools/) - A DIY penetration testing quadcopter platform announced at Black Hat 2016.
* [WASP](https://www.suasnews.com/2010/08/wi-fi-aerial-surveillance-platform-wasp/) - Wireless Aerial Surveillance Platform.
* [Hack-a-drone](https://github.com/Ordina-JTech/hack-a-drone?tab=readme-ov-file) - A Java-based project allowing control of Wi‑Fi drones (e.g. Cheerson CX‑10) via app or keyboard, demonstrating remote command capabilities.

### Common Wi-Fi Protocols & Equipment
* [WFB-ng](https://github.com/svpcom/wfb-ng) - Low‑latency UDP Wi‑Fi broadcast for FPV drones.
* [OpenIPC](https://openipc.org/) - Open firmware turning IP cameras into low‑cost FPV links.
* [RubyFPV](https://rubyfpv.com/) - Cross‑platform digital FPV stack for Wi‑Fi dongles.
* [RunCam WifiLink](https://shop.runcam.com/runcam-wifilink-based-on-openipc/) - 5.8 GHz Wi‑Fi FPV adapter with open protocol docs.

## 📺 FPV & Payloads

### Video Detection & Eavesdropping
* [FPV DETECTION](https://github.com/Payalo64/FPV_DETECTED_1.2_5.8GHZ) - Raspberry Pi Pico-based FPV Detection Tool with 1.6 km range.
* [RX5808 Pro Diversity](https://github.com/sheaivey/rx5808-pro-diversity) - DIY 5.8 GHz FPV video receiver station with antenna diversity.
* [Meshtastic Detection Node (Drone Detection)](https://www.tindie.com/products/thewolfblitz7/fpv-meshtastic-detection-node-drone-detection/) - Mesh nodes designed to detect, and alert presence of 5.8GHz FPV analog video transmissions. They alert via Meshtastic and Serial USB.
* [TVSharp](https://github.com/linuxuser2064/TVSharper) - An analog TV decoder for the RTL-SDR (but sharper).

### Video Jamming, Spoofing & Tampering
* [HackTV](https://github.com/fsphil/hacktv) - Analogue TV transmitter for the HackRF.

## 📡 BVLOS Communications

### Cellular Analysis & Tampering Tools
* [LTE-Cell-Scanner](https://github.com/Evrytania/LTE-Cell-Scanner) - LTE cell detection and analysis.
* [gr-gsm](https://github.com/ptrkrysik/gr-gsm) - GSM analysis with GNU Radio.
* [QCSuper](https://github.com/P1sec/QCSuper) - Capture 2G-4G traffic using Qualcomm phones.
* [5GBaseChecker](https://github.com/SyNSec-den/5GBaseChecker) - Tool for detecting vulnerabilities in 5G baseband implementations (2024).
* [FALCON LTE](https://github.com/falkenber9/falcon) - Fast Analysis of LTE Control Channels for real-time analysis.
* [Kalibrate](https://github.com/scateu/kalibrate-hackrf) - GSM base station scanner and frequency calibration tool.
* [LTE Sniffer](https://github.com/SysSec-KAIST/LTESniffer) - Open-source LTE downlink/uplink eavesdropper.
* [OsmocomBB](https://github.com/korczis/osmocom-bb) - Free firmware for mobile phone baseband processors.
* [Modmobmap](https://github.com/Synacktiv-contrib/Modmobmap) - Mobile network mapping.
* [Modmobjam](https://github.com/Synacktiv-contrib/Modmobjam) - Mobile jamming research.

### Common BVLOS Equipment
* [CUAV SR 4/5G Link](https://doc.cuav.net/link/lte-link/en/) - LTE LINK series communication link is a UAV link, independently supported by CUAV.
* [Iridium RockBlock](https://docs.px4.io/main/en/advanced_features/satcom_roadblock.html) - Satellite Communications Module.
* [Cloud Walker](https://www.cloudwalkerfpv.com/) - Optical Fiber Digital Communication Module.
* [OpenBTS](https://github.com/PentHertz/OpenBTS) - GSM+GPRS Radio Access Network Node reloaded for 2024-2025 for newest UHD drivers and supporting Ubuntu 22.04 & 24.04.
* [LimeNET CrowdCell](https://limemicro.com/) - Network in a box solution with integrated LimeSDR for small cell deployments.
* [Magma Core Network](https://github.com/magma) - Meta's distributed packet core now under Linux Foundation.

## 🤖 Protocols & Middleware Tools
* [MAVLink](https://github.com/mavlink/mavlink) - Marshalling / communication library for drones.
* [MAVSDK](https://github.com/mavlink/MAVSDK) - API and library for MAVLink compatible systems written in C++17.
* [ROS](https://www.ros.org/) - Open Source Robot Operation System (ROS).
* [MAVROS](https://github.com/mavlink/mavros) - MAVLink to ROS gateway with proxy for Ground Control Station.
* [MAVLink Router](https://github.com/mavlink-router/mavlink-router) - Route mavlink packets between endpoints.

### Protocol Analysis & Tampering
* [MAVSploit](https://github.com/Rud3m/MavSploit) - Pentesting toolkit designed specifically for identifying and exploiting vulnerabilities within the MavLink communication protocol.
* [MAVLink Wireshark PLugin](https://mavlink.io/en/guide/wireshark.html) - Parsing MAVLink Messages in Wireshark.
* [aztarna](https://github.com/aliasrobotics/aztarna) - ROS Footprinting Tool.

## 💽 Autopilot Firmware
* [ArduPilot](https://ardupilot.org/) - Trusted, versatile, and open source autopilot system supporting many vehicle types.
* [PX4](https://px4.io/) - Open Source Autopilot fro Drone Developers.
* [iNav](https://github.com/iNavFlight/inav) - Navigation-enabled flight control software.
* [Betaflight](https://github.com/betaflight/betaflight) - Open Source Flight Controller Firmware for FPV Drones.

### Firmware Analysis
* [Binwalk](https://github.com/ReFirmLabs/binwalk) - Searches a binary for "interesting" stuff, as well as extracts arbitrary files.
* Firmware Analysis Toolkit
* [cwe_checker](https://github.com/fkie-cad/cwe_checker) - Finds vulnerable patterns in binary executables - ELF support for x86, ARM, and MIPS, experimental bare-metal support.
* [emba](https://github.com/e-m-b-a/emba) - Analyze Linux-based firmware of embedded devices.
* [Firmwalker](https://github.com/craigz28/firmwalker) - Searches extracted firmware images for interesting files and information.
* [Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap) - Discovering vulnerabilities in firmware through concolic analysis and function clustering.
* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) - Software Reverse Engineering suite; handles arbitrary binaries, if you provide CPU architecture and endianness of the binary.
* [Radare2](https://github.com/radareorg/radare2) - Software Reverse Engineering framework, also handles popular formats and arbitrary binaries, has an extensive command line toolset.
* [Trommel](https://github.com/CERTCC/trommel) - Searches extracted firmware images for interesting files and information.
* [JTAGenum](https://github.com/cyphunk/JTAGenum) - Add JTAG capabilities to an Arduino.
* [OpenOCD](https://openocd.org/) - Free and Open On-Chip Debugging, In-System Programming and Boundary-Scan Testing.

### Firmware Extraction
* [DJI Firmware Tools](https://github.com/o-gs/dji-firmware-tools) - Utilities to extract, modify, and rebuild DJI drone firmware modules—including calibration, parameter editing, and repackaging for analysis.
* [FACT Extractor](https://github.com/fkie-cad/fact_extractor) - Detects container format automatically and executes the corresponding extraction tool.
* [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit) - Extraction tools for several container formats.
* [The SRecord package](https://srecord.sourceforge.net/) - Collection of tools for manipulating EPROM files (can convert lots of binary formats).
* [Cotopaxi](https://github.com/Samsung/cotopaxi) - Set of tools for security testing of Internet of Things devices using specific network IoT protocols.
* [dumpflash](https://github.com/ohjeongwook/dumpflash) - Low-level NAND Flash dump and parsing utility.
* [flashrom](https://github.com/flashrom/flashrom) - Tool for detecting, reading, writing, verifying and erasing flash chips.
* [Samsung Firmware Magic](https://github.com/chrivers/samsung-firmware-magic) - Decrypt Samsung SSD firmware updates.

### Firmware Modification
* [WAF](https://github.com/ArduPilot/waf) - Python-based Ardupilot Firmware Compiler.
* [DJI FC Patcher](https://github.com/o-gs/DJI_FC_Patcher) - Custom FC Patcher and Flashing for various DJI drones.

## 🧠 Companion Computers

### Companion Network Analysis
* [Wireshark](https://www.wireshark.org/) - Network traffic analyzer.
* [NMAP](https://nmap.org/) - Network Mapping Tool.

### Companion Web Application Attacking
* [BurpSuite](https://portswigger.net/) - Web application security testing tooling, provides automated testing & external plugins.

## 🛫 Ground Control Stations
* [QGround Control](https://github.com/mavlink/qgroundcontrol) - Cross-platform ground control station for drones.
* [Mission Planner](https://ardupilot.org/planner/) - Windows-based GCS Software.
* [MAVProxy](https://github.com/ArduPilot/MAVProxy) - CLI-based GCS Software.

## 📱 Mobile GCS Apps
* [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - Automated, all in one mobile application hacking.
* [ADB Toolkit](https://github.com/ASHWIN990/ADB-Toolkit) - ADB-Toolkit V2 for easy ADB tricks with many perks in all one.
* [Androguard](https://github.com/androguard/androguard) - Reverse engineering and pentesting for Android applications.
* [Apktool](https://github.com/iBotPeaches/Apktool) - A tool for reverse engineering Android apk files.
* [Dex2Jar](https://github.com/pxb1988/dex2jar) - Tools to work with android .dex and java .class files.
* [Enjarify](https://github.com/Storyyeller/enjarify) - Tool for translating Dalvik bytecode to equivalent Java bytecode. This allows Java analysis tools to analyze Android applications.

## 🧠 Artifical Intelligence Libraries
* [OpenCV](https://github.com/opencv/opencv) - Open Source Computer Vision Library.

## 🏢 Vendor-Specific Research

### DJI
* [Drone-ID Receiver for DJI OcuSync 2.0](https://github.com/RUB-SysSec/DroneSecurity)
* [DroneXtract](https://github.com/ANG13T/DroneXtract) - Digital forensics suite for DJI drones.
* [DJI Drone ID](https://github.com/proto17/dji_droneid) - An SDR-based decoder that demodulates proprietary DJI DroneID RF bursts and allows creation of arbitrary DroneID frames using MATLAB/Octave scripts.
* [Drone Hacks](https://drone-hacks.com/) - DJI Drone Hacking Tool for purchase.
* [dji_rev](https://github.com/fvantienen/dji_rev) - DJI Reverse Engineering Toolkit.
* [deejaeye-Modder](https://github.com/Bin4ry/deejayeye-modder) - DJI Drone Firmware Modding Tool.
* [pyduml](https://github.com/hdnes/pyduml) - Python based DUML "DJI Universal Markup Language" Exploit & FW upgrade/downgrade tool.
* [RedHerring](https://github.com/MAVProxyUser/P0VsRedHerring) - FTPD directory transversal 0day.
* [DUMLrub](https://github.com/MAVProxyUser/DUMLrub) - Ruby port of PyDUML.
* [DUMLdore](https://github.com/jezzab/DUMLdore) - DJI Firmware Flashing Tool v3.20.
* [No Limit Drones](https://nolimitdronez.com/) - DJI Drone Hacking Tool for purchase.

### Parrot
* [SkyJack](https://github.com/samyk/skyjack) - Drone source used to autonomously seek out, hack, and wirelessly take full control over any other Parrot or 3DR drones.
* [DroneJack](https://github.com/brospars/wic-ter-dronejack) - Dronejack is a node web-based application to take control of a Parrot drone.
* [Maldrone](https://www.youtube.com/watch?v=5SlWdl4ZuAI) - First Backdoor for Drones.

### Misc
* [DroneSploit](https://github.com/dronesploit/dronesploit) - Drone pentesting framework console.
* [Drone Duel](https://github.com/marcnewlin/drone-duel) - Code used in the Great Drone Duel of 2016.
* [Drone-Hacking-Tool](https://github.com/HKSSY/Drone-Hacking-Tool) - Drone Hacking Tool is a GUI tool that works with a USB Wifi adapter and HackRF One for hacking drones.
* [Snoopy](https://github.com/sensepost/Snoopy) - A distributed tracking and data interception framework.


## 📚 Research Papers & Blog Articles
* [Vulnerability Analysis of the MAVLink Protocol for Command and Control of Unmanned Aircraft](https://apps.dtic.mil/sti/citations/ADA598977) - A DoD/AFIT technical report identifying confidentiality, integrity, and availability flaws in MAVLink C2 messages, enabling crafted attacks on UAV missions.
* [How to Set Up A Drone Vulnerability Testing Lab](https://medium.com/@swalters/how-to-set-up-a-drone-vulnerability-testing-lab-db8f7c762663) - A Medium guide detailing a <$100 home drone security lab using toy/hobby drones and RC systems, upgradable to advanced gear like DJI and Futaba.
* [GPS Jamming Techniques for UAVs using Low-Cost SDR Platforms](https://www.researchgate.net/publication/339824302_Effective_GPS_Jamming_Techniques_for_UAVs_Using_Low-Cost_SDR_Platforms) - A research paper showing BladeRF/GNU Radio SDR can generate effective GPS interference to disrupt UAV navigation.
* [Unmanned Aircraft Capture and Control via GPS Spoofing](https://rnl.ae.utexas.edu/images/stories/files/papers/unmannedCapture.pdf) - A seminal study demonstrating UAV takeover by injecting deceptive GPS signals under specific conditions.
* [Drone Detection and Tracking Using RF Identification Signals](https://www.mdpi.com/1424-8220/23/17/7650) - An MDPI study presenting a dev‑board RF system decoding Drone‑ID telemetry with detection ranges of up to ~3.7 km on various DJI models.

## 🔍 OSINT & Intelligence
* [The Drone Database](https://drones.cnas.org/drones/) - Detailed information on drones from around the world. Perfect for research, analysis, and staying informed about global drone capabilities.
* [DJI Hardware Schematics](https://github.com/o-gs/dji-hardware-schematics) - Community-shared KiCad schematics and PCBs for various DJI drone boards, though may contain errors and lack warranty.
* [DJI Packet Dumps](https://github.com/o-gs/dji-packet-dumps) - Collections of DJI hardware communication logs in PCAP format, useful for protocol analysis in Wireshark.

## 💥 Exploits, CVEs & Vulnerabilities
* [Exploit Database](https://www.exploit-db.com/) - A large, public, CVE‑compliant repo of exploits and proof‑of‑concept code for penetration testers and researchers.
* [Robot Vulnerability Database](https://github.com/aliasrobotics/RVD) - An open archive tracking robot/ROS vulnerabilities with RVSS scoring, curated by Alias Robotics.

## 📣 Vulnerability Disclosure Programs
* [DJI](https://security.dji.com) - Official DJI program offering $50–$30 k rewards.
* [Parrot](https://www.parrot.com/en/newsroom/parrot-launches-its-bug-bounty-partnership-yeswehack) - Parrot runs a phased YesWeHack bug bounty program.
* [PX4](https://github.com/PX4/PX4-Autopilot/blob/main/SECURITY.md) - PX4 Security Policy.
* [ArduPilot](https://github.com/ArduPilot/MethodicConfigurator/security) - ArduPilot Vulnerability Disclosure.
* [QGround Control](https://github.com/mavlink/qgroundcontrol/security) - QGround Control Vulnerability Disclosure.
* [Autel Robotics](https://www.autelrobotics.com/protocol/) - Autel Robotics Vulnerability Disclosure.
* [ROS](https://ros.org/reps/rep-2006.html) - ROS Vulnerability Disclosure Policy.
* [DroneDeploy](https://help.dronedeploy.com/hc/en-us/articles/1500004862001-Vulnerability-Reporting-Policy) - DroneDeploy Vulnerability Reporting Policy.
* [Zipline](https://www.zipline.com/zipline-vulnerability-disclosure-policy) - Zipline Vulnerability Disclosure Policy.
* [IRIS Automation / uAvioni](https://www.irisonboard.com/responsible-disclosure/) - IRIS Automation / uAvioni Vulnerability Disclosure.
* [Ameta](https://ametasmart.com/pages/ameta-vulnerability-disclosure-policy) - Ameta Vulnerability Disclosure Policy.
* [Ouster](https://ouster.com/responsible-disclosure-policy) - Ouster Responsible Disclosure Policy.

## 🎓 Training & Education
* [DSOC - DronSec Courses](https://training.dronesec.com/) - Master Offensive Operations & Adversary Tradecraft for Drones.
* [DarkWolf Drone Playbook](https://dronewolf.darkwolf.io/) - Drone Hacking Playbook Developed by Dark Wolf Solutions.

## 🗣️ Communities
* [Dronecode foundation](https://dronecode.org/) - Home for MavLink, QGroundcontrol and PX4, part of Linux foundation.
* [FPV Freedom Coalation](https://fpvfc.org/) - Keep drones hackabel and safe.
* #DeejayeyeHackingClub

### Who to Follow

#### Medium
* [Sander Walters](https://medium.com/@swalters)

#### X/Tweeter
* [d0tslash](https://x.com/d0tslash)

## Additional Resources
* [Awesome-Drones](https://github.com/janesmae/awesome-drones) - A curated list of Awesome Drones resources.
* [Awesome-Flying-FPV](https://github.com/Matthias84/awesome-flying-fpv) - Awesome Flying FPV List.

## ⚖️ Legal Notice
This repository is for educational and research purposes only. Users are responsible for complying with all applicable laws and regulations. The maintainers do not endorse or encourage any illegal activities.
