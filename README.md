<div align="center">
 
<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                         HERO SECTION                            -->
<!-- ═══════════════════════════════════════════════════════════════ -->
 
<img src="https://raw.githubusercontent.com/WebHackerTeam/.github/main/assets/matrix-banner.gif" width="100%" alt="Matrix Rain Banner" />
 
<h1 align="center">
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/shield-halved.svg" width="40" />
  <span>WEB HACKER TEAM</span>
</h1>
 
<p align="center">
  <i>$ whoami</i><br/>
  <code>>> Cybersecurity Research Collective | Est. 2024</code><br/>
  <code>>> We break things to make them stronger.</code>
</p>
 
<!-- 状态徽章 -->
<p align="center">
  <img src="https://img.shields.io/badge/🇨🇳_CHINA-009944?style=for-the-badge&logo=location-dot&logoColor=white" />
  <img src="https://img.shields.io/badge/⚡_STATUS-HUNTING-00ff00?style=for-the-badge&logo=target&logoColor=00ff00" />
  <img src="https://img.shields.io/badge/🎯_22+CVE-AF2C2E?style=for-the-badge&logo=shield-halved&logoColor=AF2C2E" />
  <img src="https://img.shields.io/badge/🚀_HIRING-9B59B6?style=for-the-badge&logo=linkedin&logoColor=9B59B6" />
</p>
 
<p align="center">
  <a href="https://github.com/WebHackerTeam">
    <img src="https://img.shields.io/github/followers/WebHackerTeam?style=for-the-badge&logo=github&label=Follow&color=00ff00" />
  </a>
  <a href="https://github.com/WebHackerTeam?tab=repositories">
    <img src="https://img.shields.io/github/stars/WebHackerTeam?style=for-the-badge&logo=github&label=Stars&color=ffcc00" />
  </a>
</p>
 
</div>
🔥 About Us
 
[!IMPORTANT]
WEB HACKER TEAM 成立于 2024 年，是一支专注于网络安全研究的精英团队。我们致力于漏洞挖掘、安全研究和负责任的漏洞披露。
截至目前，团队已向 QNAP、Synology、emlog 等知名厂商累计报送 22+ 个 CVE，发现并披露多个高危零日漏洞。
📡 Research Focus
 
<details open>
<summary><b>🔍 Research Domains | 点击展开查看详细研究方向</b></summary>
 
| Domain | Focus Areas | Threat Level |
|:------:|:------------|:------------:|
| 🌐 Web Security | SQLi · XSS · SSRF · Deserialization · RCE | ████████░░ CRITICAL |
| 💾 Binary / IoT | Buffer Overflow · Command Injection · Privesc | ███████░░░ HIGH |
| ☁️ Cloud / Network | NAS · Firewall Bypass · DoS | ██████░░░░ ELEVATED |
 
</details>
🛠️ Tech Stack
 
<p align="center">
 
| 🧠 Vulnerability Research | ⚔️ Penetration Testing | 🔬 Reverse Engineering | ☁️ Cloud Security |
|:-------------------------:|:----------------------:|:----------------------:|:-----------------:|
| IDA Pro | Burp Suite | Ghidra | Kubernetes |
| GDB / WinDbg | Metasploit | Frida | Docker |
| CodeQL | Nmap / Masscan | dnSpy / x64dbg | AWS / Azure |
| Pwntools | SQLMap | Radare2 | Terraform |
 
</p>
🏆 CVE Statistics
 
<div align="center">
 
| 🔴 High | 🟡 Medium | 🟢 Low | 📦 Total |
|:-------:|:---------:|:------:|:--------:|
| 12 | 9 | 1 | 22+ |
 
</div>
📂 CVE Database
 
<details open>
<summary><b>📋 Vulnerability Database | 共 22 个 CVE</b></summary>
🔴 High Severity
 
| CVE ID | Type | Affected Product |
|:-------|:-----|:-----------------|
| CVE-2024-7962 | Arbitrary File Read | gaizhenbiao/chuanhuchatgpt |
| CVE-2024-56804 | SQL Injection | QNAP Video Station |
| CVE-2024-56805 | Buffer Overflow | QNAP OS |
| CVE-2025-22481 | Command Injection | QNAP OS |
| CVE-2025-30264 | Command Injection | QNAP OS |
| CVE-2025-30265 | Buffer Overflow | QNAP OS |
| CVE-2025-3535 | Denial of Service | BurpAPIFinder v2.0.2 |
| CVE-2025-52868 | Buffer Overflow | Qsync Central |
| CVE-2025-52869 | Buffer Overflow | Qsync Central |
| CVE-2025-52870 | Buffer Overflow | Qsync Central |
| CVE-2026-46687 | Local File Inclusion | emlog/emlog |
🟡 Medium Severity
 
| CVE ID | Type | Affected Product |
|:-------|:-----|:-----------------|
| CVE-2024-8029 | Cross-Site Scripting | imartinez/privategpt |
| CVE-2024-50405 | CRLF Injection | QuTS hero |
| CVE-2024-50406 | Cross-Site Scripting | QNAP License Center |
| CVE-2024-53693 | CRLF Injection | QuTS hero |
| CVE-2025-22482 | Format String | Qsync Central |
| CVE-2025-29898 | Denial of Service | Qsync Central |
| CVE-2025-52867 | Denial of Service | Qsync Central |
| CVE-2026-40532 | Forced Browsing | Synology DSM |
| CVE-2026-40536 | Path Traversal | Synology DSM |
| CVE-2026-46686 | Cross-Site Scripting | emlog/emlog |
🟢 Low Severity
 
| CVE ID | Type | Affected Product |
|:-------|:-----|:-----------------|
| CVE-2024-12923 | Cross-Site Scripting | QNAP Photo Station |
 
</details>
📊 Threat Analytics
 
<details open>
<summary><b>📈 Visualization | 漏洞可视化分析</b></summary>
Severity Distribution
 
mermaid
pie title CVE Severity Distribution
    "🔴 High (12)" : 12
    "🟡 Medium (9)" : 9
    "🟢 Low (1)" : 1

Affected Vendors
 
mermaid
xychart-beta
    title "Affected Vendors"
    x-axis ["Qsync Central", "QNAP OS", "Synology", "emlog", "QuTS hero"]
    y-axis "CVE Count" 0 --> 6
    bar [5, 4, 2, 2, 2]

 
</details>
👥 Hiring
 
[!NOTE]
### 🚀 We Are Hiring!
我们正在寻找志同道合的 0-day 猎手：
🌐 Web 安全研究员 — SQLi / XSS / SSRF 专家
💾 二进制漏洞研究员 — 逆向工程 / 缓冲区溢出
📱 IoT 安全研究员 — 固件逆向 / 路由器安全
📬 Contact
 
<div align="center">
 
| 📧 Email | 🐙 GitHub |
|:--------:|:---------:|
| web_hacker@163.com | @WebHackerTeam |
 
Email
GitHub
 
</div>
<div align="center">
 

╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║     ██╗   ██╗ ██████╗ ██╗   ██╗██╗      ██████╗ ██╗    ██╗    ║
║     ╚██╗ ██╔╝██╔═══██╗██║   ██║██║      ██╔══██╗██║    ██║    ║
║      ╚████╔╝ ██║   ██║██║   ██║██║      ██║  ██║██║ █╗ ██║    ║
║       ╚██╔╝  ██║   ██║██║   ██║██║      ██║  ██║██║███╗██║    ║
║        ██║   ╚██████╔╝╚██████╔╝███████╗██████╔╝╚███╔███╔╝    ║
║        ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝╚═════╝  ╚══╝╚══╝     ║
║                                                               ║
║          ⚡ We hack for security, not for chaos. ⚡          ║
║                                                               ║
╚═══════════════════════════════════════════════════════════════╝

 
<sub>⚡ root@webhacker:~# exit</sub>
 
</div>
