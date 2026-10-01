<!-- ═══════════════════════════════  HEADER  ═══════════════════════════════ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00B4FF,50:A855F7,100:FF2E63&height=220&section=header&text=Mohamed%20Amine%20Namouchi&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Blue%20by%20trade%20%C2%B7%20Red%20by%20obsession%20%C2%B7%20Purple%20by%20design&descSize=18&descAlignY=58&animation=fadeIn" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=A855F7&center=true&vCenter=true&width=760&lines=I+build+the+detections.;Then+I+try+to+break+them.;Then+I+make+them+better.;SOC+Analyst+%40+Altinea+%7C+MSSP;Network-native+%C2%B7+CCNA+%E2%86%92+CCNP;Long-term+target%3A+0-days." alt="typing" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/namouchimohamedamine"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:Mohamed-Amine_Namouchi@etu.ube.fr"><img src="https://img.shields.io/badge/Email-A855F7?style=for-the-badge&logo=protonmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Dijon%20%C2%B7%20FR-0D1117?style=for-the-badge&logo=googlemaps&logoColor=A855F7" />
  <img src="https://komarev.com/ghpvc/?username=MedNamouchi&style=for-the-badge&color=A855F7&label=PROFILE+VIEWS" />
</p>

<br>

<!-- ═══════════════════════════════  TL;DR  ═══════════════════════════════ -->
<table align="center">
<tr>
<td align="center" width="33%">

### 🔵 Blue by day
**SOC Analyst** (work-study)<br>
@ **Altinea** — MSSP<br>
<sub>SIEM · correlation · hardening · IPS</sub>

</td>
<td align="center" width="33%">

### 🔴 Red by night
**Web · Network · Malware Dev**<br>
PortSwigger · Root-Me · OverTheWire<br>
<sub>SSRF → Gopher → Redis → RCE</sub>

</td>
<td align="center" width="33%">

### 🌐 Network-native
**CCNA 1–3 · heading for CCNP**<br>
OSPF · BGP · VLAN · IPSec · QoS<br>
<sub>NETCONF/YANG · SNMP · Zabbix</sub>

</td>
</tr>
</table>

> **I'm a final-year network security engineering student who ships detection to production — and then attacks it.**
> Two production SIEMs deployed before graduating. Thousands of false positives killed. Now I'm building the other half: the attacker's mindset.

---

## `$ git log --graph --career`

```mermaid
%%{init: { 'theme': 'dark', 'gitGraph': { 'mainBranchName': 'amine', 'showCommitLabel': true } } }%%
gitGraph
  commit id: "Bac · Tunisia"
  commit id: "CPGE"
  commit id: "Polytech Dijon"
  branch network
  commit id: "CCNA 1-3"
  commit id: "SNMP , NETCONF/YANG"
  commit id: "VoIP and QoS (SIP/RTP)"
  checkout amine
  merge network
  branch blue-team
  commit id: "Cowrie + Splunk"
  commit id: "Security Onion SOC"
  commit id: "OFIR · prod SIEM / NIS2 client"
  commit id: "Altinea · SOC" type: HIGHLIGHT
  checkout amine
  branch red-team
  commit id: "PortSwigger"
  commit id: "Root-Me · Bandit"
  commit id: "SignalBreach" type: HIGHLIGHT
  commit id: "Malware Dev"  type: HIGHLIGHT
  checkout amine
  merge blue-team
  merge red-team
  commit id: "PURPLE" type: REVERSE
```

<sub>🔵 blue and 🔴 red branches run in parallel — I learn offense and defense at the same time, then merge them.</sub>

---

## `$ cat impact.log`

<div align="center">

| | Metric | Context |
|:---:|:---|:---|
| 🧹 | **~9,300 false positives eliminated** | Zabbix audit — root-caused a Proxmox LXC memory trigger |
| 🛡️ | **50+ client vhosts monitored** | Production SIEM on a shared WordPress/Laravel hosting server |
| 🏭 | **2 production SIEMs shipped** | Incl. one for a NIS2 *important entity* — built on bare metal |
| 📈 | **CIS compliance 48% → 79%** | NIS2 / CIS Benchmark hardening on Ubuntu 24.04 |
| 🧬 | **21+ custom rules · 9 Sigma rules** | Custom PCRE2 decoders, every rule mapped to MITRE ATT&CK |
| 🔭 | **CCNA → CCNP in progress** | Network-native profile: OSPF, BGP, QoS, NETCONF/YANG |

</div>

---

## `$ ./operations --active`

<table>
<tr>
<td width="50%" valign="top">

### 📡 [SignalBreach](https://github.com/MedNamouchi/SignalBreach)
**What happens to call quality when someone attacks your VoIP stack?**

Docker lab (Asterisk · MediaMTX · Suricata) → QoS baseline (jitter, loss, MOS via E-model) → **live attacks** (SIPVicious cracking, INVITE floods, RTP eavesdropping via ARP spoofing) → **remediation** (SRTP/TLS, Fail2ban) → replay the same attacks to prove the fix.

`SIP` `RTP/RTCP` `RTSP` `Docker` `Suricata` `Python`

</td>
<td width="50%" valign="top">

### 🧬 Malware Development
**Learning to build what the blue team has to catch.**

Hands-on offensive tradecraft — studying payloads, droppers and evasion from the attacker's side, so my detections are sharper on the other end.

`Offensive R&D` `Windows` `Evasion` `Detection-aware`

</td>
</tr>
<tr>
<td colspan="2" align="center">

### 🧪 `[REDACTED]`
<sub>Still in the lab: the **Sentinel Breach** purple-team cyber range, and a long-term **AI purple team platform** (autonomous offensive agent + defensive SOC agent). Not public yet. 👀</sub>

</td>
</tr>
</table>

---

## `$ ./operations --shipped`

```mermaid
flowchart LR
    A[🛜 MikroTik CCR] -->|syslog| B[Graylog]
    B -->|parsed| C[Wazuh]
    C -->|custom PCRE2 decoders<br/>+ ATT&CK rules| D[(OpenSearch)]
    C -->|active response| E[🚨 Mattermost · Email]
    C -->|enrichment| F[AbuseIPDB · VirusTotal]
    C -->|block| G[iptables · MikroTik · Cloudflare]
```

> **SIEM-MikroTik-Wazuh-Graylog** — the pipeline above, from EVE-NG prototype to commercial deployment. Multi-layer IP blocking, FIM on 14 critical paths, 6-month retention. → [repo](https://github.com/MedNamouchi/SIEM-MikroTik-Wazuh-Graylog)

### 🎓 Academic projects

| Project | What it does | Stack |
|---|---|---|
| **NETCONF & YANG** | Atomic config & inter-VLAN routing automation via XML against YANG models, replacing legacy SNMP/CLI workflows | `NETCONF` `YANG` `GNS3` |
| **Cowrie + SIEM** | SSH/Telnet honeypot capturing & correlating intrusion attempts in Splunk, with a Telegram bot for live attack alerts | `Cowrie` `Splunk` |
| **SOC on Security Onion** | Full SOC stack for detection & incident investigation, with alert triage and IR procedures | `Suricata` `Zeek` |

### 📂 Pick a repo

<sub>Click to expand 👇</sub>

<details>
<summary><b>📡 SignalBreach</b> — VoIP security & QoS under attack</summary>
<br>
Multimedia signaling (SIP / RTP / RTSP) lab: measure QoS, attack it, defend it, replay to validate.
<br><br>
<a href="https://github.com/MedNamouchi/SignalBreach"><img src="https://img.shields.io/badge/View%20on%20GitHub-A855F7?style=for-the-badge&logo=github&logoColor=white" /></a>
</details>

<details>
<summary><b>🛰️ SIEM-MikroTik-Wazuh-Graylog</b> — end-to-end detection pipeline</summary>
<br>
Production SIEM built from scratch across EVE-NG simulation and physical MikroTik CCR routers.
<br><br>
<a href="https://github.com/MedNamouchi/SIEM-MikroTik-Wazuh-Graylog"><img src="https://img.shields.io/badge/View%20on%20GitHub-00B4FF?style=for-the-badge&logo=github&logoColor=white" /></a>
</details>

<details>
<summary><b>➕ More</b> — all repositories</summary>
<br>
<a href="https://github.com/MedNamouchi?tab=repositories"><img src="https://img.shields.io/badge/Browse%20all%20repos-0D1117?style=for-the-badge&logo=github&logoColor=A855F7" /></a>
</details>

---

## `$ arsenal --list`

<div align="center">

<img src="https://skillicons.dev/icons?i=linux,ubuntu,debian,bash,python,docker,git,github,kali&theme=dark" />

<br><br>

![Wazuh](https://img.shields.io/badge/Wazuh-00B4FF?style=flat-square&logo=wazuh&logoColor=white)
![Graylog](https://img.shields.io/badge/Graylog-00B4FF?style=flat-square&logo=graylog&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-00B4FF?style=flat-square&logo=opensearch&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-00B4FF?style=flat-square&logo=splunk&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-00B4FF?style=flat-square)
![Zeek](https://img.shields.io/badge/Zeek-00B4FF?style=flat-square)
![Sigma](https://img.shields.io/badge/Sigma%20Rules-00B4FF?style=flat-square)
![Zabbix](https://img.shields.io/badge/Zabbix-00B4FF?style=flat-square&logo=zabbix&logoColor=white)

![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF2E63?style=flat-square&logo=burpsuite&logoColor=white)
![PortSwigger](https://img.shields.io/badge/PortSwigger-FF2E63?style=flat-square)
![Kali](https://img.shields.io/badge/Kali-FF2E63?style=flat-square&logo=kalilinux&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-FF2E63?style=flat-square)
![SIPVicious](https://img.shields.io/badge/SIPVicious-FF2E63?style=flat-square)
![OWASP](https://img.shields.io/badge/OWASP-FF2E63?style=flat-square&logo=owasp&logoColor=white)
![ARP Spoofing](https://img.shields.io/badge/ARP%20Spoofing-FF2E63?style=flat-square)

![Cisco](https://img.shields.io/badge/CCNA%20%E2%86%92%20CCNP-A855F7?style=flat-square&logo=cisco&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-A855F7?style=flat-square&logo=mikrotik&logoColor=white)
![GNS3](https://img.shields.io/badge/GNS3-A855F7?style=flat-square)
![EVE-NG](https://img.shields.io/badge/EVE--NG-A855F7?style=flat-square)
![Asterisk](https://img.shields.io/badge/Asterisk-A855F7?style=flat-square&logo=asterisk&logoColor=white)
![Stormshield](https://img.shields.io/badge/Stormshield-A855F7?style=flat-square)

<sub>🔵 detect · 🔴 exploit · 🟣 network & infra</sub>

</div>

---

## `$ cat training.status`

```diff
+ [DONE]  CCNA 1-3  ·  2 production SIEMs shipped (one NIS2 important entity)
+ [DONE]  PortSwigger — SSRF, WebSockets, Web Cache Deception (Expert CSRF+WCD lab)
+ [DONE]  Root-Me — SSRF → Gopher → Redis → RCE  ·  OverTheWire Bandit
+ [DONE]  Custom PCRE2 decoders + 9 Sigma rules, all MITRE ATT&CK-mapped
! [WIP]   Malware development  ·  network & web exploitation
! [WIP]   CCNP  ·  PortSwigger Academy — remaining topics
- [NEXT]  Cloud & DevOps for the cyber range
- [LONG]  Vulnerability research → 0-days
```

---

## `$ github --stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=MedNamouchi&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A855F7&icon_color=00B4FF&text_color=c9d1d9&ring_color=FF2E63" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MedNamouchi&layout=compact&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=c9d1d9" />

<img src="https://streak-stats.demolab.com/?user=MedNamouchi&hide_border=true&background=0D1117&ring=A855F7&fire=FF2E63&currStreakLabel=A855F7&sideLabels=00B4FF&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff" />

</div>

---

<div align="center">

### `$ echo "let's talk"`
**Open to:** purple team collabs · CTF teams · security research · VoIP / network security discussions

[![LinkedIn](https://img.shields.io/badge/-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/namouchimohamedamine)
[![Email](https://img.shields.io/badge/-Reach%20out-A855F7?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:Mohamed-Amine_Namouchi@etu.ube.fr)

<br>

*"I write the rules. Then I find the ways around them. Then I write better rules."*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FF2E63,50:A855F7,100:00B4FF&height=120&section=footer" />
