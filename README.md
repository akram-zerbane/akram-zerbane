<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:0f766e,100:22d3ee&height=230&section=header&text=Akram%20Zerbane&fontSize=60&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Defensive%20Cybersecurity%20%E2%80%A2%20SOC%20%E2%80%A2%20Detection%20Engineering&descSize=18&descAlignY=60&descColor=a5f3fc" alt="Header" />

<a href="https://github.com/akram-zerbane">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=22D3EE&center=true&vCenter=true&width=760&height=50&lines=Detection+Engineering+%7C+Detection-as-Code;Threat+Hunting+%26+Alert+Analysis;SIEM+%E2%80%A2+SOAR+%E2%80%A2+Incident+Response;Turning+telemetry+into+detections+%F0%9F%9B%A1%EF%B8%8F" alt="Typing animation" />
</a>

<br/>

![Status](https://img.shields.io/badge/STATUS-OPEN_TO_PFE_INTERNSHIP-22d3ee?style=for-the-badge&labelColor=0f172a)
![Focus](https://img.shields.io/badge/FOCUS-BLUE_TEAM_%7C_SOC-14b8a6?style=for-the-badge&labelColor=0f172a)
![Start](https://img.shields.io/badge/START-FEBRUARY-38bdf8?style=for-the-badge&labelColor=0f172a)

<br/>

<a href="https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://github.com/akram-zerbane?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-Explore-0f172a?style=for-the-badge&logo=github&logoColor=22d3ee" alt="Repositories" />
</a>

</div>

<br/>

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->

## `> whoami`

```console
akram@soc:~$ cat profile.txt

 Role       : 5th-year Engineering Student — Intelligent Networks & Cybersecurity (ENSA Khouribga)
 Specialty  : Defensive Security · SOC · Detection Engineering
 Interests  : Threat Hunting · Alert Analysis · SIEM · Incident Response · DFIR
 Building   : Detection-as-Code pipelines, SOAR automation, AI-assisted Sigma rule synthesis
 Seeking    : Final-year internship (PFE) starting in February, within a SOC team
```

I design and automate the **full lifecycle of detection use cases**, from adversary emulation and telemetry analysis to rule validation, CI/CD deployment, and KPI-driven governance.

<br/>

<!-- ═══════════════════════════ FOCUS AREAS ═══════════════════════════ -->

## `> focus_areas`

<table>
<tr>
<td width="25%" align="center">

### 🛡️
**Detection Engineering**<br/>
<sub>Sigma / Wazuh rules<br/>MITRE ATT&CK mapping<br/>Detection-as-Code</sub>

</td>
<td width="25%" align="center">

### 🔎
**Threat Hunting & DFIR**<br/>
<sub>Sysmon telemetry<br/>LOLBins analysis<br/>Artifact forensics</sub>

</td>
<td width="25%" align="center">

### ⚙️
**SOAR & Automation**<br/>
<sub>Shuffle playbooks<br/>Ansible remediation<br/>GitLab CI/CD</sub>

</td>
<td width="25%" align="center">

### 📊
**SOC Metrics & Governance**<br/>
<sub>MTTD · Lead Time<br/>KPI / KRI dashboards<br/>Use Case Factory</sub>

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════ LIFECYCLE ═══════════════════════════ -->

## `> detection_lifecycle`

```mermaid
flowchart LR
    A([🎯 Adversary<br/>Emulation]) --> B([📡 Telemetry<br/>Sysmon · Wazuh])
    B --> C([🧪 Rule Authoring<br/>Sigma · XML])
    C --> D([🔁 CI/CD<br/>Validate & Deploy])
    D --> E([🚨 SIEM<br/>Detection])
    E --> F([🤖 SOAR<br/>Response])
    F --> G([📈 KPI / KRI<br/>MTTD · Coverage])
    G -.feedback.-> C

    style A fill:#0f172a,stroke:#22d3ee,color:#e2e8f0
    style B fill:#0f172a,stroke:#22d3ee,color:#e2e8f0
    style C fill:#0f172a,stroke:#14b8a6,color:#e2e8f0
    style D fill:#0f172a,stroke:#14b8a6,color:#e2e8f0
    style E fill:#0f172a,stroke:#38bdf8,color:#e2e8f0
    style F fill:#0f172a,stroke:#38bdf8,color:#e2e8f0
    style G fill:#0f172a,stroke:#a5f3fc,color:#e2e8f0
```

<br/>

<!-- ═══════════════════════════ FEATURED PROJECTS ═══════════════════════════ -->

## `> featured_projects`

<table>
<tr>
<td width="50%" valign="top">

#### 🔁 Continuous Assessment & SOC Lifecycle Management
`Detection as Code`

- OpenProject ticketing + GitLab CI/CD: syntax validation, SSH deployment of Wazuh XML rules, remote **Atomic Red Team** execution
- Python **ETL engine** correlating tickets, commits and Wazuh/Sysmon alerts to compute **MTTD** and **Lead Time**
- PostgreSQL + **Grafana** dashboards for governance KPI/KRI and detection coverage

![Python](https://img.shields.io/badge/Python-0f172a?style=flat-square&logo=python&logoColor=22d3ee)
![GitLab](https://img.shields.io/badge/GitLab_CI-0f172a?style=flat-square&logo=gitlab&logoColor=22d3ee)
![Wazuh](https://img.shields.io/badge/Wazuh-0f172a?style=flat-square&logo=wazuh&logoColor=22d3ee)
![Grafana](https://img.shields.io/badge/Grafana-0f172a?style=flat-square&logo=grafana&logoColor=22d3ee)

</td>
<td width="50%" valign="top">

#### 🤖 Autonomous AI Agent for Sigma Rule Synthesis
`Detection Engineering × LLM`

- Adversary emulation with **CALDERA** → Sysmon telemetry into **Elasticsearch**
- **Shuffle SOAR** pipeline sanitizing attack artifacts into JSON
- **FastAPI + Groq LLM** agent generating MITRE ATT&CK-mapped Sigma rules, shipped through GitLab CI/CD

![FastAPI](https://img.shields.io/badge/FastAPI-0f172a?style=flat-square&logo=fastapi&logoColor=22d3ee)
![Elastic](https://img.shields.io/badge/Elasticsearch-0f172a?style=flat-square&logo=elasticsearch&logoColor=22d3ee)
![Sigma](https://img.shields.io/badge/Sigma-0f172a?style=flat-square&logoColor=22d3ee)
![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-0f172a?style=flat-square&logoColor=22d3ee)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏗️ SOC Architecture & Distributed SIEM Platform
`Infrastructure × SOAR`

- Isolated SOC architecture behind **pfSense**, agents (Sysmon, Auditd, Wazuh) deployed with **Ansible**
- Full-stack dashboard (**FastAPI / React**) for alert mapping and MTTD tracking
- Automated incident response with **Shuffle** and remediation Ansible playbooks

![Ansible](https://img.shields.io/badge/Ansible-0f172a?style=flat-square&logo=ansible&logoColor=22d3ee)
![React](https://img.shields.io/badge/React-0f172a?style=flat-square&logo=react&logoColor=22d3ee)
![pfSense](https://img.shields.io/badge/pfSense-0f172a?style=flat-square&logo=pfsense&logoColor=22d3ee)

</td>
<td width="50%" valign="top">

#### 🧬 LOLBins Attack Simulation & DFIR Investigation
`Forensics × Detection`

- Reproduction of attacks using native Windows binaries (**LOLBins**)
- Forensic analysis of **Sysmon** telemetry
- Custom **Sigma / Wazuh** detections validated and mapped to MITRE ATT&CK

![Sysmon](https://img.shields.io/badge/Sysmon-0f172a?style=flat-square&logo=windows&logoColor=22d3ee)
![PowerShell](https://img.shields.io/badge/PowerShell-0f172a?style=flat-square&logo=powershell&logoColor=22d3ee)
![DFIR](https://img.shields.io/badge/DFIR-0f172a?style=flat-square&logoColor=22d3ee)

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════ PINNED REPOS ═══════════════════════════ -->

## `> repositories`

<div align="center">

<a href="https://github.com/akram-zerbane/automated-incident-response-pipeline">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=akram-zerbane&repo=automated-incident-response-pipeline&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=14b8a6" alt="automated-incident-response-pipeline" />
</a>
<a href="https://github.com/akram-zerbane/agent-dac">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=akram-zerbane&repo=agent-dac&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=14b8a6" alt="agent-dac" />
</a>
<a href="https://github.com/akram-zerbane/incident-response-ransomware-analysis">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=akram-zerbane&repo=incident-response-ransomware-analysis&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=14b8a6" alt="incident-response-ransomware-analysis" />
</a>
<a href="https://github.com/akram-zerbane/Use-Case-Validation-Framework">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=akram-zerbane&repo=Use-Case-Validation-Framework&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=14b8a6" alt="Use-Case-Validation-Framework" />
</a>

</div>

<br/>

<!-- ═══════════════════════════ TECH STACK ═══════════════════════════ -->

## `> tech_stack`

<div align="center">

**SOC & Threat Intelligence**

<img src="https://img.shields.io/badge/Wazuh-0f172a?style=for-the-badge&logo=wazuh&logoColor=22d3ee" />
<img src="https://img.shields.io/badge/Elastic_Stack-0f172a?style=for-the-badge&logo=elastic&logoColor=22d3ee" />
<img src="https://img.shields.io/badge/TheHive-0f172a?style=for-the-badge&logoColor=22d3ee" />
<img src="https://img.shields.io/badge/MISP-0f172a?style=for-the-badge&logoColor=22d3ee" />
<img src="https://img.shields.io/badge/Suricata-0f172a?style=for-the-badge&logoColor=22d3ee" />
<img src="https://img.shields.io/badge/Shuffle_SOAR-0f172a?style=for-the-badge&logoColor=22d3ee" />
<img src="https://img.shields.io/badge/Atomic_Red_Team-0f172a?style=for-the-badge&logoColor=22d3ee" />
<img src="https://img.shields.io/badge/CALDERA-0f172a?style=for-the-badge&logoColor=22d3ee" />
<img src="https://img.shields.io/badge/MITRE_ATT%26CK-0f172a?style=for-the-badge&logoColor=22d3ee" />

**Networks, Cloud & DevOps**

<img src="https://skillicons.dev/icons?i=linux,docker,terraform,ansible,azure,aws,gitlab,git,vmware,bash&theme=dark" />

**Development & Data**

<img src="https://skillicons.dev/icons?i=python,fastapi,react,nodejs,c,cpp,postgres,grafana,powershell,sklearn&theme=dark" />

</div>

<br/>

<!-- ═══════════════════════════ EXPERIENCE ═══════════════════════════ -->

## `> experience`

| Period | Role | Highlights |
|:--|:--|:--|
| **Jul – Aug 2026** | **Cybersecurity & SOC Intern** — Eurafric Information | Designed a structured **Use Case Factory** for SOC detection lifecycle management; mapped business processes and cross-functional roles (CTI · SIRT · SOC Engineering); defined **KPI/KRI** and deployed a monitoring dashboard |
| **Jul 2025** | **Introductory Intern** — CAPVALUE | Web application vulnerability analysis (**OWASP Top 10**), exploitation of **IDOR / BOLA** flaws |

<br/>

<!-- ═══════════════════════════ CERTIFICATIONS ═══════════════════════════ -->

## `> certifications`

<div align="center">

![CyberOps](https://img.shields.io/badge/Cisco-CyberOps_Associate-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![DevNet](https://img.shields.io/badge/Cisco-DevNet_Associate-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![NetSec](https://img.shields.io/badge/Cisco-Network_Security-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Ethical](https://img.shields.io/badge/Cisco-Ethical_Hacker-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
<br/>
![Ansible](https://img.shields.io/badge/Red_Hat-Ansible_RH294-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
![Linux](https://img.shields.io/badge/Red_Hat-Linux_RH124_%2F_RH134-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_Academy-Cloud_Security_Foundations-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![ISO](https://img.shields.io/badge/ISO%2FIEC-27001_Associate-0f766e?style=for-the-badge)

</div>

<br/>

<!-- ═══════════════════════════ GITHUB STATS ═══════════════════════════ -->

## `> github_analytics`

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=akram-zerbane&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=14b8a6&text_color=c9d1d9&ring_color=22d3ee&count_private=true" alt="GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=akram-zerbane&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=22d3ee&text_color=c9d1d9" alt="Top languages" />

<br/>

<img src="https://streak-stats.demolab.com?user=akram-zerbane&theme=tokyonight&hide_border=true&background=0D1117&ring=22D3EE&fire=14B8A6&currStreakLabel=22D3EE" alt="Streak" />

<br/><br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=akram-zerbane&bg_color=0d1117&color=22d3ee&line=14b8a6&point=ffffff&area=true&area_color=22d3ee&hide_border=true" alt="Activity graph" />

</div>

<br/>

<!-- ═══════════════════════════ SNAKE ═══════════════════════════ -->
<!-- Requires the workflow in .github/workflows/snake.yml (provided separately) -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/akram-zerbane/akram-zerbane/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/akram-zerbane/akram-zerbane/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/akram-zerbane/akram-zerbane/output/github-snake-dark.svg" />
</picture>

</div>

<br/>

<!-- ═══════════════════════════ CONTACT ═══════════════════════════ -->

## `> let's_connect`

<div align="center">

Currently looking for a **final-year engineering internship (PFE) starting in February** within a **SOC**: threat hunting, alert analysis, SIEM and incident response.

<br/>

<a href="https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME">
  <img src="https://img.shields.io/badge/Let's_Talk-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=akram-zerbane&label=Profile+Views&color=0e7490&style=for-the-badge" alt="Profile views" />

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,50:0f766e,100:020617&height=120&section=footer" alt="Footer" />

</div>
