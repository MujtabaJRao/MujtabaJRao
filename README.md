<div align="center">

```
███╗   ███╗██╗   ██╗     ██╗████████╗ █████╗ ██████╗  █████╗
████╗ ████║██║   ██║     ██║╚══██╔══╝██╔══██╗██╔══██╗██╔══██╗
██╔████╔██║██║   ██║     ██║   ██║   ███████║██████╔╝███████║
██║╚██╔╝██║██║   ██║██   ██║   ██║   ██╔══██║██╔══██╗██╔══██║
██║ ╚═╝ ██║╚██████╔╝╚█████╔╝   ██║   ██║  ██║██████╔╝██║  ██║
╚═╝     ╚═╝ ╚═════╝  ╚════╝    ╚═╝   ╚═╝  ╚═╝╚═════╝ ╚═╝  ╚═╝
```

###  `Penetration Tester` · `RTL/FPGA Engineer` · `Arch Linux`

*where register-transfer logic meets exploit development*

[![HackerOne](https://img.shields.io/badge/HackerOne-grey?style=flat-square&logo=hackerone)](https://hackerone.com)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-grey?style=flat-square&logo=bugcrowd)](https://bugcrowd.com)
[![PortSwigger](https://img.shields.io/badge/PortSwigger_Web_Academy-FF6633?style=flat-square)](https://portswigger.net/web-security)
[![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)](https://archlinux.org)

</div>

---

## The Angle

Most people come at security from software. I come at it from silicon.

Designing RTL — where you control every clock edge, every signal propagation path, every pipeline stage — gives you a level of systems intuition that pure software engineers don't have. That maps directly onto a class of vulnerabilities most people skip: timing oracles, cache-based side channels, speculative execution leaks, hardware-accelerated fuzzing.

That's the edge I'm building.

```
HARDWARE KNOWLEDGE                    SECURITY APPLICATION
─────────────────────────────────────────────────────────
Clock domain crossing          →      Timing attack primitives
Cache hierarchy design         →      Flush+Reload, Prime+Probe
Pipeline stage analysis        →      Spectre-style gadget hunting
Signal integrity / EMI         →      Power analysis (SPA/DPA)
RTL state machines             →      Protocol-level exploit logic
```

---

## Hardware

**Focus:** FPGA/RTL design, custom processor architecture, low-level systems

![Verilog](https://img.shields.io/badge/Verilog-grey?style=flat-square)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-grey?style=flat-square)
![C](https://img.shields.io/badge/C-grey?style=flat-square&logo=c)
![C++](https://img.shields.io/badge/C++-grey?style=flat-square&logo=cplusplus)
![RISC-V](https://img.shields.io/badge/RISC--V-grey?style=flat-square)

**IBN-E-SINA — Custom 16-bit Stack Processor** ← main project right now  
Zero-address architecture. Hybrid stack-register design with TOS/NOS buffers.  
Single-cycle execution. High code density. Built from scratch in Verilog.  
→ [CS-221-Computer-Organization-Design-CEP-IBN-E-SINA-Architecture](https://github.com/MujtabaJRao/CS-221-Computer-Organization-Design-CEP-IBN-E-SINA-Architecture)

Currently studying:  
`Cache hierarchies` · `RISC-V single-cycle datapath` · `IEEE 754` · `CPI analysis`

---

## Pentesting

**Focus:** Web application security, bug bounty, working toward elite on PortSwigger

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square)
![Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)
![Python](https://img.shields.io/badge/Python-grey?style=flat-square&logo=python)
![JavaScript](https://img.shields.io/badge/JavaScript-grey?style=flat-square&logo=javascript)

Active on:
- **PortSwigger Web Security Academy** — pushing through Expert-tier labs
- **HackerOne / Bugcrowd** — transitioning to real targets
- Recon stack: `subfinder` `amass` `httpx` `ffuf` `nuclei` `gau` `shodan`

Vuln classes: `SQLi` `XSS` `SSRF` `IDOR` `CSRF` `XXE` `RCE` `OAuth flaws` `JWT attacks`  
Certs on the radar: `OSCP` · `BSCP` · `eWPT`

---

## Stack

```
OS          Arch Linux (btw)
Editor      Neovim
HDL         Verilog / SystemVerilog
Languages   C · C++ · Python · JavaScript
Sim         GTKWave · Icarus Verilog
Web Sec     Burp Suite · ffuf · nuclei · sqlmap
Recon       subfinder · amass · httpx · gau · Shodan
```

---

## Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=MujtabaJRao&show_icons=true&hide_border=true&count_private=true&theme=tokyonight&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&icon_color=58a6ff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=MujtabaJRao&layout=compact&hide_border=true&theme=tokyonight&bg_color=0d1117&title_color=58a6ff&text_color=8b949e)

</div>

---

<div align="center">

`Karachi, PK` · Open to internships & research collab  
*If you're working on hardware security, side-channels, or low-level exploit dev — let's talk.*

</div>
