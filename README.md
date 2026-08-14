<img src="assets/banner.svg" alt="Harsh Yadav — low-level systems, security, embedded" width="100%">

<p align="center">
  <a href="https://www.linkedin.com/in/harsh-yadav-aa2214345"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:hyadav42774@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Vellore,_India-30363d?style=flat-square&logo=googlemaps&logoColor=white" alt="Vellore, India">
</p>

I build low-level systems and then try to break them — IoT devices on hostile networks, concurrent servers in Go, and AI agents that can move real money.

Right now I'm doing IoT security at **SVNT Infotech**, shipping encrypted telemetry off field-deployed hardware over cellular.

<br>

## 🏆 Wins

<table>
<tr>
<td align="center" width="33%">
<h2>🥇</h2>
<b>1st Place</b><br>
<sub>AI agent build-off</sub><br>
<sub><b>WITHAI</b> · YC P26</sub><br>
<sub>$600</sub>
</td>
<td align="center" width="33%">
<h2>🥈</h2>
<b>2nd Place</b><br>
<sub>Capture The Flag</sub><br>
<sub><b>MIT Bangalore</b></sub><br>
<sub>crypto · rev · web · forensics</sub>
</td>
<td align="center" width="33%">
<h2>🥉</h2>
<b>3rd Place</b><br>
<sub>RC Car Racing</sub><br>
<sub><b>Technoxian</b> World Robotics</sub><br>
<sub>South Zone → Nationals</sub>
</td>
</tr>
</table>

<br>

## ⚡ Things I've built

| | |
| :--- | :--- |
| **[Cerberus](https://github.com/Harshyadav442277/Cerberus-finance)**<br><sub>`TypeScript` `Next.js` `Solidity`</sub> | Pre-execution governance for AI agents that can spend money. Every proposed payment gets `ALLOW` / `DENY` / `ESCALATE` before the request even exists. The model proposes — a deterministic engine decides. |
| **[Secure IoT Comms](https://github.com/Harshyadav442277/secureCommunicationInIoT)**<br><sub>`C` `ESP32` `MQTT` `mTLS`</sub> | TLS with mutual auth between ESP32 nodes and broker. Nonce + timestamp validation kills replayed packets; protocol-level rate limiting kills the flood. |
| **[Concurrent TCP Chat Server](https://github.com/Harshyadav442277/RTC-with-GO)**<br><sub>`Go`</sub> | Multi-client TCP server in Go. One hub goroutine owns the client registry and fans out messages over non-blocking channels, with graceful disconnect. |
| **[Telemetry Pipeline](https://github.com/Harshyadav442277/Real-Time-Distributed-Telemetry-Pipeline)**<br><sub>`C++` `ESP32` `Node.js`</sub> | ChaCha20-encrypted telemetry from an ESP32 + SIM800L, pushed over cellular into a backend collector. |
| **[THE HOOK](https://github.com/Harshyadav442277/the-hook)**<br><sub>`Python` `Streamlit`</sub> | Explainable MLB bullpen simulator — replays real high-leverage pitching changes and scores the alternatives the manager didn't take. **[live →](https://the-hook.streamlit.app/)** |
| **[MicroSpark AI](https://github.com/Harshyadav442277/MicroSpark_AI)**<br><sub>`TypeScript` `Next.js`</sub> | Task-initiation assistant for neurodivergent learners. Turns a wall-of-text assignment into one concrete next move. |

<br>

## 🧰 Stack

<p>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C">
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
</p>

<p>
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp Suite">
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" alt="Wireshark">
<img src="https://img.shields.io/badge/Nmap-4682B4?style=flat-square&logo=gnometerminal&logoColor=white" alt="Nmap">
<img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" alt="Kali Linux">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
</p>

<p>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32">
<img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT">
<img src="https://img.shields.io/badge/TLS_/_mTLS-2E7D32?style=flat-square&logo=letsencrypt&logoColor=white" alt="TLS / mTLS">
<img src="https://img.shields.io/badge/WebSockets-2C3E50?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

<br>

## 📡 Currently

```
> extending the Go server    :: websocket upgrade, JWT auth, persistence
> agent guardrails           :: deterministic policy, audit trails
> field hardware             :: firmware + protocol hardening over cellular
```
