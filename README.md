<!-- Premium Animated GitHub Profile README -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0f172a,30:0ea5e9,70:06b6d4,100:22d3ee&text=Chandraprakash%20C&fontColor=ffffff&fontSize=42&fontAlignY=35&desc=SOC%20Analyst%20(L1)%20%7C%20Blue%20Team%20%7C%20Threat%20Detection%20%7C%20Incident%20Response&descAlignY=56&animation=twinkling" alt="header" />

<p align="center">
  <img src="Animated_Video.gif" alt="SOC Analyst Banner" width="92%" />
</p>

<h1 align="center">👋 Hey, I'm Chandraprakash C</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=22&pause=1000&color=22D3EE&center=true&vCenter=true&width=900&lines=SOC+Analyst+(L1)+%E2%80%A2+Open+to+Work;Splunk+%E2%80%A2+Sysmon+%E2%80%A2+Zeek+%E2%80%A2+Velociraptor;Threat+Detection+%E2%80%A2+Incident+Response+%E2%80%A2+IOC+Enrichment;Built+ThreatLens+%26+SecOps+Console;TryHackMe+Top+1%25+%E2%80%A2+3%C3%97+Industry+Certified" alt="typing intro" />
</p>

<p align="center">
  <a href="https://tryhackme.com/p/0xchandru"><img src="https://img.shields.io/badge/TryHackMe-Top_1%25-red?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe" /></a>
  <a href="https://linkedin.com/in/chandraprakash-soc"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://chandraprakash.me"><img src="https://img.shields.io/badge/Portfolio-chandraprakash.me-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:cyberchandru87@gmail.com"><img src="https://img.shields.io/badge/Email-Hire_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<!-- <p align="center">
  <img src="https://komarev.com/ghpvc/?username=0xchandru&label=Profile%20Views&color=0ea5e9&style=flat-square" alt="profile views" />
  <img src="https://img.shields.io/github/followers/0xchandru?label=Followers&style=flat-square&color=22c55e" alt="followers" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-14b8a6?style=flat-square" alt="open to work" />
</p> -->

---

## ⚡ Executive Snapshot

```yaml
Name: Chandraprakash C
Role: SOC Analyst (L1)
Focus: Blue Team | Threat Detection | Incident Response | SOC Operations
Location: Tamil Nadu, India
Status: Open to Work
Strength: Hands-on SOC lab + real investigations + analyst tooling projects
```

### Why recruiters and hiring managers should notice this profile

- 🛡️ **Built and run a self-managed SOC home lab** with **Splunk, Sysmon, Zeek, and Velociraptor**
- 🔎 Completed **structured end-to-end investigations** with **SPL queries, evidence timelines, IOC enrichment, and MITRE ATT&CK mapping**
- ⚙️ Built **ThreatLens** and **SecOps Console** to improve analyst speed, triage, and workflow automation
- 🏆 Ranked in the **Top 1% on TryHackMe** and completed **3 industry-recognized cybersecurity credentials**
- 📄 Strong documentation mindset: investigations are written for **reviewability, reproducibility, and technical clarity**

---

## 🧠 Who I Am

I’m a **B.Sc. Computer Science graduate** focused on becoming a high-impact **SOC Analyst / Security Analyst**.

What makes me different is simple: I didn’t stop at coursework and certificates. I built a realistic security operations environment, used it to investigate attack scenarios, and created supporting tools that reflect real SOC workflows.

I enjoy working across the full analyst cycle:

- alert triage
- log investigation
- IOC validation
- endpoint and network correlation
- incident documentation
- ATT&CK mapping
- workflow automation

---

## 🚀 Featured Work


<table>
  <tr>
    <td valign="top">
      <h3>🏠 SOC Home Lab</h3>
      <p><strong>Detection and investigation lab</strong> built to simulate real SOC workflows across endpoint and network telemetry.</p>
      <ul>
        <li>Splunk Enterprise + Universal Forwarder for SIEM pipeline</li>
        <li>Windows 10 VM with Sysmon, Script Block Logging, and Velociraptor</li>
        <li>Zeek telemetry using <code>conn.log</code>, <code>dns.log</code>, and <code>http.log</code></li>
        <li>SOAR workflow integration with Shuffle, Jira, and Slack</li>
      </ul>
      <p><strong>Example scenarios:</strong> Brute Force, PowerShell C2 Callback, Lateral Movement, Ransomware Simulation, and additional investigation workflows.</p>
      <a href="https://github.com/0xchandru/soc-homelab">
        <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="SOC Homelab Repo" />
      </a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔍 ThreatLens</h3>
      <p><strong>Multi-source IOC enrichment platform</strong> built for faster analyst decision-making.</p>
      <ul>
        <li>Queries 5 intelligence sources in parallel using <code>asyncio.gather</code></li>
        <li>Returns a weighted composite threat score for IPs, domains, and hashes</li>
        <li>Designed to reduce analyst context switching during triage</li>
      </ul>
      <p>
        <strong>Stack:</strong> FastAPI, Python, React, Vite, SQLite/PostgreSQL<br/>
        <strong>Sources:</strong> VirusTotal, AbuseIPDB, AlienVault OTX, URLhaus, GreyNoise
      </p>
      <a href="https://github.com/0xchandru/threatlens">
        <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="ThreatLens Repo" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>📡 SecOps Console</h3>
      <p><strong>SOC operations dashboard</strong> that centralizes enrichment, triage, and response workflow actions.</p>
      <ul>
        <li>Acts as a proxy/cache layer for ThreatLens enrichment</li>
        <li>Supports alert triage, IOC lookup, and case workflow visibility</li>
        <li>Integrates SOAR actions with Jira ticketing and Slack notification</li>
      </ul>
      <p>
        <strong>Stack:</strong> React, FastAPI, Python<br/>
        <strong>Workflow:</strong> Splunk Alert → Shuffle SOAR → Jira → Slack
      </p>
      <a href="https://github.com/0xchandru/secops-console">
        <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="SecOps Console Repo" />
      </a>
    </td>
  </tr>
</table>

---

## 🛡️ Core SOC Skills

### Detection & Investigation
<p>
  <img src="https://img.shields.io/badge/Splunk_SPL-000000?style=for-the-badge&logo=splunk&logoColor=white" alt="Splunk" />
  <img src="https://img.shields.io/badge/Sysmon-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Sysmon" />
  <img src="https://img.shields.io/badge/Zeek-00AEEF?style=for-the-badge&logoColor=white" alt="Zeek" />
  <img src="https://img.shields.io/badge/Velociraptor-FF6600?style=for-the-badge&logoColor=white" alt="Velociraptor" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
</p>

### Automation & SOAR
<p>
  <img src="https://img.shields.io/badge/Shuffle_SOAR-4B275F?style=for-the-badge&logoColor=white" alt="Shuffle" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" alt="Slack" />
</p>

### Threat Intelligence
<p>
  <img src="https://img.shields.io/badge/VirusTotal-394EFF?style=for-the-badge&logoColor=white" alt="VirusTotal" />
  <img src="https://img.shields.io/badge/AbuseIPDB-CC0000?style=for-the-badge&logoColor=white" alt="AbuseIPDB" />
  <img src="https://img.shields.io/badge/AlienVault_OTX-67B346?style=for-the-badge&logoColor=white" alt="AlienVault OTX" />
  <img src="https://img.shields.io/badge/URLhaus-FF4500?style=for-the-badge&logoColor=white" alt="URLhaus" />
  <img src="https://img.shields.io/badge/GreyNoise-4A90D9?style=for-the-badge&logoColor=white" alt="GreyNoise" />
</p>

### Languages & Development
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
</p>

---

## 🏅 Certifications & Achievements

| Credential | Provider | Status |
| --- | --- | --- |
| SOC Level 1 Learning Path | TryHackMe | ✅ Completed |
| Cybersecurity Professional Certificate | Google / Coursera | ✅ Completed |
| Cybersecurity Analyst Professional Certificate | IBM / Coursera | ✅ Completed |

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=0xchandru&theme=algolia&no-frame=true&row=1&column=6&margin-w=15&margin-h=15" alt="trophies" />
</p>

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=0xchandru&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=0xchandru&theme=tokyonight&hide_border=true" width="48%" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xchandru&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="40%" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=0xchandru&theme=react-dark&hide_border=true&area=true" width="95%" alt="activity graph" />
</p>

---

## 🤝 Let’s Connect

<p align="center">
  <a href="https://linkedin.com/in/chandraprakash-soc"><img src="https://img.shields.io/badge/LinkedIn-chandraprakash--soc-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://tryhackme.com/p/0xchandru"><img src="https://img.shields.io/badge/TryHackMe-0xchandru-red?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe" /></a>
  <a href="https://chandraprakash.me"><img src="https://img.shields.io/badge/Portfolio-chandraprakash.me-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://medium.com/@0xchandru"><img src="https://img.shields.io/badge/Medium-@0xchandru-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="mailto:cyberchandru87@gmail.com"><img src="https://img.shields.io/badge/Email-cyberchandru87%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <strong>Open to:</strong> L1 SOC Analyst • Security Analyst • Blue Team • Threat Detection Roles
</p>

<p align="center">
  <i>Built real tools. Ran real investigations. Ready for a real SOC.</i>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:0f172a,30:0ea5e9,70:06b6d4,100:22d3ee" alt="footer" />
