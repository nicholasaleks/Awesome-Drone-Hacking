# Awesome Drone Hacking [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center">
  <a href="https://x.com/intent/tweet?text=Awesome%20Drone%20Hacking%20-%20A%20curated%20list%20of%20resources%20related%20to%20drone%20hacking.%0Ahttps%3A%2F%2Fgithub.com%2Fnicholasaleks%2FAwesome-Drone-Hacking&hashtags=awesomelists,drone,hacking,cybersecurity,infosec" target="_blank">
    <img src="https://img.shields.io/badge/Tweet--lightgrey?logo=x&style=social" alt="Tweet" height="20"/>
  </a>
  <img alt="Deadlinks Checked" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/deadlinks.yml/badge.svg">
  <img alt="Markdown Lint" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/markdownlint.yml/badge.svg">
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
  <strong>A curated list of offensive drone security resources for researchers, pentesters, and hackers.</strong><br/>
  This repository covers tools, techniques, and research for hacking open-source, autonomous, FPV (First-Person View), and proprietary drone systems—from telemetry and flight control to hardware, firmware, and communication protocols.
</p>

---

# 📚 Table of Contents

- [🔬 Drone Hacking Labs, CTFs & Workshops](#-drone-hacking-labs-ctfs--workshops) 
- [🎤 Conference Talks & Videos](#-conference-talks--videos)
- [🧰 Attack Surface & Tools](#-attack-surface--tools)
  - [💿 Real-Time Operating Systems](#-real-time-operating-systems)
  - [🔌 Flight Controller & Embedded Systems](#-flight-controller--embedded-systems)
  - [📻 Radio & SiK Telemetry](#-radio--sik-telemetry)
  - [📶 Wi-Fi Communications](#-wi-fi-communications)
  - [📺 FPV & Payloads](#-fpv--payloads)
  - [📡 BVLOS Cellular & Satelitte](#-bvlos-cellular--satelitte)
  - [🤖 ROS & MAVLink](#-ros--mavlink)
  - [💽 Autopilot Firmware](#-autopilot-firmware)
  - [🖥️ Companion Computers](#-companion-computers)
  - [🛫 Ground Control Stations](#-ground-control-stations)
  - [📱 Mobile GCS Apps](#-mobile-gcs-apps)
  - [🧠 Artifical Intelligence Libraries](#-artifical-intelligence-libraries)
- [🏢 Vendor-Specific Research](#-vendor-specific-research)
- [📚 Research Papers & Blog Articles](#-research-papers--blog-articles)
- [🔍 OSINT & Intelligence](#-osint--intelligence)
- [💥 Exploits, CVEs & Vulnerabilities](#-exploits-cves--vulnerabilities)
- [🎓 Training & Education](#-training--education)
- [📣 Vulnerability Disclosure Programs](#-vulnerability-disclosure-programs)
- [🗣️ Communities](#-communities)
- [⚖️ Legal Notice](#-legal-notice)

# 🔬 Drone Hacking Labs, CTFs & Workshops
- [Damn Vulnerable Drone (DVD)](https://github.com/nicholasaleks/Damn-Vulnerable-Drone) - Docker-based virtual drone hacking simulator
- [Hack Our Drone Workshop](https://dronewolf.darkwolf.io/workshop) - Dark Wolf Hack Our Drone Workshop
- [Drone Wars, BloomCon](https://www.commonwealthu.edu/offices-directory/mathematics-computer-science-and-digital-forensics/drone-wars-competition) - Collegiate arena where teams hijack Wi‑Fi drones and race them through obstacles.
- [Hack The Drone](http://hackthedrone.org/eng/index.php) - International Drone Hacking Competition, Korea Drone Security Association

# 🎤 Conference Talks & Videos
- [WTF WJI, UAV CTF?](https://ftp.fau.de/cdn.media.ccc.de/events/camp2023/h264-hd/camp2023-57063-eng-WTF_DJI_UAV_CTF_hd.mp4) - Felix Domke, cccamp23
- [Debugging Microcontrollers](https://media.ccc.de/v/camp2023-57321-debugging_microcontrollers) - Niklas Hauser, ccamp23
- [Demodulating 5GHz analog drone video](https://www.youtube.com/watch?app=desktop&v=rl8ACNnjPFA) - cemaxecuter, Youtube
- [Game of Drones](https://www.slideshare.net/slideshow/def-con-25-2017-game-of-drones-brown-latimer-29july2017-slidespdf/250332791)
- [Parrot Drones Hijacking](https://www.youtube.com/watch?v=66z-aXy_1Yo) - RSA2018 Video, Pedro Cabrera, March 2018 (Slides)
- [A Drone Tale, All your drones are belong to us](http://youtube.com/watch?v=aU4ULr3Lwt8) - Paolo Stagno, Hacktivity
- [All your bebop drones still belong to us](https://www.youtube.com/watch?v=ra0nKHvaXnc) - Pedro Cabrera, Rooted CON, 2016
- [Shelling out a "smart drone"](https://www.youtube.com/watch?v=IqCz-V6WMVg&t=2875s) - Kevin Finisterre, Derbycon 2015
- [Drones Hijacking - Multi dimensional attack vectors](https://www.youtube.com/watch?v=DFLofy789ko) - Aaron Luo, DEF CON 24, 2016
- [Hacking a Professional Drone](https://www.youtube.com/watch?v=JRVb-xE1zTI&t=470s) - Nils Rodday, Black Hat, 2016
- [Avoiding CounterDrone Systems with NanoDrones](https://www.youtube.com/watch?v=pVmFxJPOu9I) - David Melendez Cano, DEF CON 26, 2018
- [Game of Drones](https://www.youtube.com/watch?v=iG7hUE2BZZo) - Fran Brown & David Latimer, DEF CON 25, 2017
- [Spread Spectrum techniques for anti drone evasion](https://www.youtube.com/watch?v=8Ng91UY3D2M) - David Melendez, Gabriela Garcia, DEF CON 31, 2023
- [Knocking my neighbors kids cruddy drone offline](https://www.youtube.com/watch?v=5CzURm7OpAA) - Michael Robinson, DEF CON 23, 2015
- [Practical Aerial Hacking & Surveillance](https://www.youtube.com/watch?v=knrvrR-B1ZI) - Glenn Wilkinson, DEF CON 22, 2015
- [SkyJack - autonomous drone hacking](https://www.youtube.com/watch?v=EHKV01YQX_w) - Samy Kamkar, Youtube, 2013

# 🧰 Attack Surface & Tools

## 💿 Real-Time Operating Systems
- [NuttX](https://nuttx.apache.org/)
- [ChibiOS](https://www.chibios.org/dokuwiki/doku.php)

## 🔌 Flight Controller & Embedded Systems

### Embedding Hacking Tools
- [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - Detects and interacts with hardware debug ports like UART and JTAG.
- [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Detects and interacts with hardware debug ports like UART and JTAG.
- [Tigard](https://www.crowdsupply.com/securinghw/tigard) - An open source FT2232H-based, multi-protocol, multi-voltage tool for hardware hacking
- [JTAGULATOR](https://grandideastudio.com/portfolio/security/jtagulator/) - Detects JTAG Pinouts fast.
- [Saleae](https://www.saleae.com/) - Easy to use Logic Analyzer that support many protocols 💶.
- [Ikalogic](https://www.ikalogic.com/sp209-logic-analyzer/) - Alternative to Saleae logic analyzers 💶.
- [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/?v=0b3b97fa6688) - Open source multi-tool hardware similar to the BusPirate but with NFC capabilities.
- [ChipWhisperer](https://www.newae.com/chipwhisperer) - Detects Glitch/Side-channel attacks.
- [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) - Tool for exploring and debugging different digital interfaces.
- [J-Link](https://www.segger.com/products/debug-probes/j-link/) - J-Link offers USB powered JTAG debug probes for multiple different CPU cores 💶.

### Common Flight Controller & Embedded System Resources
- [STM32](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html) - 32-bit Arm Cortex MCUs
- [AT32](https://www.arterychip.com/en/product/AT32F425.jsp) - 32-bit Cortex-M4 microcontroller MUCs
- [Pixhawk](https://pixhawk.org/) / [Cube](https://www.cubepilot.com/#/home)
- DJI [A3](https://www.dji.com/ca/a3) / [N3](https://www.dji.com/ca/n3)
- [CUAV X7 & V5+](https://ardupilot.org/copter/docs/common-cuav-x7-family-overview.html)
- [Holybro Kakute F7/H7](https://holybro.com/products/kakute-h7-v2?srsltid=AfmBOorAjpi2nnbfkXOsFjFxvt8UiLFDPlo7vlpXIBhJMvUBZDkQ2fqW)
- [PX4 Wiring Diagram](https://docs.px4.io/main/en/assembly/quick_start_pixhawk5x.html)

## 📻 Radio & Telemetry

### Remote Identification Discovery & Spoofing Tools
- [RemoteID Spoofer](https://github.com/jjshoots/RemoteIDSpoofer)
- [WiFi RID capture](https://github.com/sxjack/unix_rid_capture)

### Telemetry Detection & Eavesdropping Tools
- [SiKW00F](https://github.com/nicholasaleks/sikw00f) - SiK Radio Detection & MAVLink Telemetry Eavesdropping Toolkit
- [SiKening](https://github.com/MAVProxyUser/SiKening) - 3DR Radio SiKening PoC by Meatball Ninja - Brute force 3DR NetID and sync up with hopping sequence.

## Misc RF Tools
- [Wireshark](https://www.wireshark.org/) - Network traffic analyzer
- [GNURadio](https://github.com/gnuradio/gnuradio) - Free and Open Software Radio Ecosystem
- [GQRX](https://github.com/gqrx-sdr/gqrx) - Software defined radio receiver powered by GNU Radio and Qt
- [SDR# (SDRSharp)](https://airspy.com/download/) - Airspy is a popular, affordable SDR (software defined radio
- [UberTooth One](https://github.com/greatscottgadgets/ubertooth) - Open source 2.4 GHz wireless development platform suitable for Bluetooth experimentation.
- [Bluefruit LE Sniffer](https://www.adafruit.com/product/2269) - Easy to use Bluetooth Low Energy sniffer.
- DragonOS: Ubuntu-based SDR distribution with preinstalled cellular tools
- RTL-SDR - Cheapest SDR for beginners. It is a computer based radio scanner for receiving live radio signals frequencies from 500 kHz up to 1.75 GHz.
- [HackRF One](https://github.com/greatscottgadgets/hackrf) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 1 MHz to 6 GHz (half-duplex).
- YardStick One - Half-duplex sub-1 GHz wireless transceiver.
- LimeSDR - Software Defined Radio peripheral capable of transmission or reception of radio signals from 100 KHz to 3.8 GHz (full-duplex).
- BladeRF 2.0 - Software Defined Radio peripheral capable of transmission or reception of radio signals from 47 MHz to 6 GHz (full-duplex).
- USRP B Series - Software Defined Radio peripheral capable of transmission or reception of radio signals from 70 MHz to 6 GHz (full-duplex).
- ApiMote - ZigBee security research hardware for learning about and evaluating the security of IEEE 802.15.4/ZigBee systems. Killerbee compatible.
- [Killerbee](https://github.com/riverloopsec/killerbee) - Framework for Testing & Auditing ZigBee and IEEE 802.15.4 Networks.
- Atmel RZUSBstick - Discontinued product. Lucky if you have one! - Tool for development, debugging and demonstration of a wide range of low power wireless applications including IEEE 802.15.4, 6LoWPAN, and ZigBee networks. Killerbee compatible.
- Freakduino - Low Cost Battery Operated Wireless Arduino Board that can be turned into a IEEE 802.15.4 protocol sniffer.

### Common Telemetry Radios
- RFD900X / RFD868X
- 3DR SiK Radio
- mRo SiK Radios
- Holybro Sik Radios
- [Microhard Telemetry Radios](https://docs.px4.io/main/en/telemetry/microhard_serial.html) - 
- [ExpressLRS](https://www.expresslrs.org/) - Open-source RC link that now supports bidirectional MAVLink passthrough with sub-10 ms latency—favoured by FPV pilots and DIY UAVs.
- TBS Crossfire

## 📶 Wi-Fi Communications

### Wi-Fi Detection & Infiltration Tools
- [Aircrack-ng](https://aircrack-ng.org) - Deauth and WPA cracking toolkit.
- [Bettercap](https://github.com/bettercap/bettercap) - MITM framework to hijack drone app traffic.
- [WifiPhisher](https://github.com/wifiphisher/wifiphisher) - Automated Evil Twin to phish Drone app creds.
- [DangerDrone (Bishop Fox)](https://resources.bishopfox.com/resources/tools/drones-penetration-testers/attack-tools/) – A DIY penetration-testing quadcopter platform announced at Black Hat 2016.

### Common Wi-Fi Protocols & Equipment
- [WFB-ng](https://github.com/svpcom/wfb-ng) - Low‑latency UDP Wi‑Fi broadcast for FPV drones.
- [OpenIPC](https://openipc.org/) - Open firmware turning IP cameras into low‑cost FPV links.
- [RubyFPV](https://rubyfpv.com/) - Cross‑platform digital FPV stack for Wi‑Fi dongles.
- [RunCam WifiLink](https://shop.runcam.com/runcam-wifilink-based-on-openipc/) - 5.8 GHz Wi‑Fi FPV adapter with open protocol docs.

## 📺 FPV & Payloads

### Video Eavesdropping

## 📡 BVLOS Communications

### Cellular Analysis & Tampering Tools
- WASP (Wireless Aerial Surveillance Platform)
- OpenBTS 2024 Reloaded: Updated for modern UHD drivers and Ubuntu 22.04/24.04 support
- OpenAirInterface (OAI): Major 5G platform with complete 3GPP Release-15+ implementation
- LimeNET CrowdCell: Network-in-a-box solution with integrated LimeSDR for small cell deployments
- Amarisoft LTEENB/gNB: Professional-grade LTE/5G NR base station software
- Magma Core Network: Meta's distributed packet core now under Linux Foundation
- 5GBaseChecker: New tool for automated 5G baseband vulnerability detection
- LTE-Cell-Scanner - LTE cell detection and analysis
- gr-gsm - GSM analysis with GNU Radio
- IMSI-Catcher Detector - Android app for detecting IMSI catchers
- QCSuper - Capture 2G-4G traffic using Qualcomm phones
- 5GBaseChecker - Tool for detecting vulnerabilities in 5G baseband implementations (2024)
- FALCON LTE - Fast Analysis of LTE Control Channels for real-time analysis
- Kalibrate - GSM base station scanner and frequency calibration tool
- LTE Sniffer - Open-source LTE downlink/uplink eavesdropper
- OsmocomBB - Free firmware for mobile phone baseband processors
- Modmobmap - Mobile network mapping
- Modmobjam - Mobile jamming research

### Common BVLOS Equipment
- [CUAV SR 4/5G Link](https://doc.cuav.net/link/lte-link/en/) - LTE LINK series communication link is a UAV link, independently supported by CUAV
- [Iridium RockBlock](https://docs.px4.io/main/en/advanced_features/satcom_roadblock.html) - Satellite Communications Module
- [Cloud Walker](https://www.cloudwalkerfpv.com/) - Optical Fiber Digital Communication Module

## 🤖 Protocols & Middleware Tools
- [MAVLink](https://mavlink.io/en/)
- [MAVSDK](https://mavsdk.mavlink.io/main/en/index.html)
- ROS
- MAVROS
- MAVLink Router
- MAVProxy

### Protocol Analysis & Tampering
- MAVSploit
- [MAVLink Wireshark PLugin](https://mavlink.io/en/guide/wireshark.html) - Parsing MAVLink Messages in Wireshark
- [aztarna](https://github.com/aliasrobotics/aztarna) - ROS Footprinting Tool

## 💽 Autopilot Firmware
- ArduPilot
- PX4
- iNav
- Betaflight

### Firmware Analysis
- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Searches a binary for "interesting" stuff, as well as extracts arbitrary files.
- Firmware Analysis Toolkit
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) - Finds vulnerable patterns in binary executables - ELF support for x86, ARM, and MIPS, experimental bare-metal support.
- [emba](https://github.com/e-m-b-a/emba) - Analyze Linux-based firmware of embedded devices.
- [Firmwalker](https://github.com/craigz28/firmwalker) - Searches extracted firmware images for interesting files and information.
- [Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap) - Discovering vulnerabilities in firmware through concolic analysis and function clustering.
- [Ghidra](https://github.com/NationalSecurityAgency/ghidra) - Software Reverse Engineering suite; handles arbitrary binaries, if you provide CPU architecture and endianness of the binary.
- [Radare2](https://github.com/radareorg/radare2) - Software Reverse Engineering framework, also handles popular formats and arbitrary binaries, has an extensive command line toolset.
- [Trommel](https://github.com/CERTCC/trommel) - Searches extracted firmware images for interesting files and information.
- [JTAGenum](https://github.com/cyphunk/JTAGenum) - Add JTAG capabilities to an Arduino.
- [OpenOCD](https://openocd.org/) - Free and Open On-Chip Debugging, In-System Programming and Boundary-Scan Testing.

### Firmware Extraction
- [DJI Firmware Tools](https://github.com/o-gs/dji-firmware-tools) - 
- FACT Extractor - Detects container format automatically and executes the corresponding extraction tool.
- Firmware Mod Kit - Extraction tools for several container formats.
- The SRecord package - Collection of tools for manipulating EPROM files (can convert lots of binary formats).
- Cotopaxi - Set of tools for security testing of Internet of Things devices using specific network IoT protocols.
- dumpflash - Low-level NAND Flash dump and parsing utility.
- flashrom - Tool for detecting, reading, writing, verifying and erasing flash chips.
- Samsung Firmware Magic - Decrypt Samsung SSD firmware updates.

### Firmware Modification
- [WAF](https://github.com/ArduPilot/waf) - Python-based Ardupilot Firmware Compiler
- [DJI FC Patcher](https://github.com/o-gs/DJI_FC_Patcher) - Custom FC Patcher and Flashing for various DJI drones

## 🧠 Companion Computers
- NMAP

## 🛫 Ground Control Stations
- [QGround Control](https://qgroundcontrol.com/)
- Mission Planner
- MAVProxy

## 📱 Mobile GCS Apps
- MobSF
- ADB
- Androwarn - detect and warn the user about potential malicious behaviors developed by an Android application.
- ApkAnalyser
- APKInspector
- Droid Intent Data Flow Analysis for Information Leakage
- DroidLegacy
- FlowDroid
- Smali/Baksmali – apk decompilation
- AndBug
- Androguard – powerful, integrates well with other tools
- Apktool – really useful for compilation/decompilation (uses smali)
- Android Framework for Exploitation
- Bypass signature and permission checks for IPCs
- Android OpenDebug – make any application on the device debuggable (using cydia substrate).
- Dex2Jar - dex to jar converter
- Enjarify - dex to jar converter from Google

## 🧠 Artifical Intelligence Libraries
- OpenCV
- TensorFlow
- Pytorch
- GStreamer

# 🏢 Vendor-Specific Research

## DJI
- [Drone-ID Receiver for DJI OcuSync 2.0](https://github.com/RUB-SysSec/DroneSecurity)
- Drone Hacks
- No Limit Drones

## Parrot
- [SkyJack](https://github.com/samyk/skyjack) - Drone source used to autonomously seek out, hack, and wirelessly take full control over any other Parrot or 3DR drones
- DroneJack
- Maldrone

## Misc
- [DroneSploit](https://github.com/dronesploit/dronesploit) - Drone pentesting framework console
- Drone Duel
- Drone-Hacking-Tool
- Snoopy


# 📚 Research Papers & Blog Articles
- [Vulnerability Analysis of the MAVLink Protocol for Command and Control of Unmanned Aircraft](https://apps.dtic.mil/sti/citations/ADA598977)
- [Hack-a-drone](https://github.com/Ordina-JTech/hack-a-drone?tab=readme-ov-file)
- [How to Set Up A Drone Vulnerability Testing Lab](https://medium.com/@swalters/how-to-set-up-a-drone-vulnerability-testing-lab-db8f7c762663)
- [GPS Jamming Techniques for UAVs using Low-Cost SDR Platforms](https://www.researchgate.net/publication/339824302_Effective_GPS_Jamming_Techniques_for_UAVs_Using_Low-Cost_SDR_Platforms)
- [Unmanned Aircraft Capture and Control via GPS Spoofing](https://rnl.ae.utexas.edu/images/stories/files/papers/unmannedCapture.pdf)
- [Drone Detection and Tracking Using RF Identification Signals](https://www.mdpi.com/1424-8220/23/17/7650)

# 🔍 OSINT & Intelligence
- [DJI Hardware Schematics](https://github.com/o-gs/dji-hardware-schematics)
- [DJI Packet Dumps](https://github.com/o-gs/dji-packet-dumps)

# 💥 Exploits, CVEs & Vulnerabilities
- [Exploit Database](https://www.exploit-db.com/)
- [Robot Vulnerability Database](https://github.com/aliasrobotics/RVD)

# 📣 Vulnerability Disclosure Programs
- [DJI Bug Bounty](https://security.dji.com)
- [Parrot Security Bounty](https://www.parrot.com/en/newsroom/parrot-launches-its-bug-bounty-partnership-yeswehack)
- [PX4 Security Policy](https://github.com/PX4/PX4-Autopilot/blob/main/SECURITY.md) & [Advisories](https://github.com/PX4/PX4-Autopilot/security/advisories)
- [ArduPilot Vulnerability Disclosure](https://github.com/ArduPilot/MethodicConfigurator/security)
- [QGround Control Vulnerability Disclosure](https://github.com/mavlink/qgroundcontrol/security)
- [Autel Robotics Vulnerability Disclosure](https://www.autelrobotics.com/protocol/)
- [ROS Vulnerability Disclosure Policy](https://ros.org/reps/rep-2006.html)
- [DroneDeploy Vulnerability Reporting Policy](https://help.dronedeploy.com/hc/en-us/articles/1500004862001-Vulnerability-Reporting-Policy)
- [Zipline Vulnerability Disclosure Policy](https://www.zipline.com/zipline-vulnerability-disclosure-policy)
- [IRIS Automation / uAvioni Vulnerability Disclosure](https://www.irisonboard.com/responsible-disclosure/)
- [Ameta Vulnerability Disclosure Policy](https://ametasmart.com/pages/ameta-vulnerability-disclosure-policy)
- [Ouster Responsible Disclosure Policy](https://ouster.com/responsible-disclosure-policy)

# 🎓 Training & Education
- [DSOC - DronSec Courses](https://training.dronesec.com/) - Master Offensive Operations & Adversary Tradecraft for Drones.
- [DarkWolf Drone Playbook](https://dronewolf.darkwolf.io/) - Drone Hacking Playbook Developed by Dark Wolf Solutions

# 🗣️ Communities
- [Dronecode foundation](https://dronecode.org/) - Home for MavLink, QGroundcontrol and PX4, part of Linux foundation.
- [FPV Freedom Coalation](https://fpvfc.org/) - Keep drones hackabel and safe.
- [Deutscher Modellflieger Verband e.V.](https://www.dmfv.aero/) - 🇩🇪 Events, local communities, assurance, ... .
- [Deutscher Aero Club e.V.](https://www.daec.de/) - 🇩🇪.

# Additional Resources
- [Awesome-Flying-FPV](https://github.com/Matthias84/awesome-flying-fpv)

# ⚖️ Legal Notice
This repository is for educational and research purposes only. Users are responsible for complying with all applicable laws and regulations. The maintainers do not endorse or encourage any illegal activities.