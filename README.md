<div align="center">
  <img src="https://raw.githubusercontent.com/WebHackerTeam/.github/main/assets/matrix-banner.gif" width="100%" alt="Banner" />
</div>

<br />

<!-- 模拟终端窗口头部 -->
<div style="background-color: #1e1e1e; border: 1px solid #333; border-radius: 6px 6px 0 0; padding: 8px 12px; margin-bottom: 0;">
  <span style="color: #ff5f56; font-size: 12px;">●</span>
  <span style="color: #ffbd2e; font-size: 12px; margin-left: 6px;">●</span>
  <span style="color: #27c93f; font-size: 12px; margin-left: 6px;">●</span>
  <span style="color: #999; font-size: 12px; margin-left: 12px;">webhacker@team:~</span>
</div>

<div align="left" style="background-color: #0d1117; border: 1px solid #333; border-top: 0; border-radius: 0 0 6px 6px; padding: 20px; font-family: 'Courier New', Courier, monospace; color: #c9d1d9;">

```
webhacker@team:~$ ssh root@webhacker-team.org

███████╗███████╗ ██████╗██╗   ██╗██████╗ ██╗████████╗██╗   ██╗
██╔════╝██╔════╝██╔════╝██║   ██║██╔══██╗██║╚══██╔══╝╚██╗ ██╔╝
███████╗█████╗  ██║     ██║   ██║██████╔╝██║   ██║    ╚████╔╝ 
╚════██║██╔══╝  ██║     ██║   ██║██╔══██╗██║   ██║     ╚██╔╝  
███████║███████╗╚██████╗╚██████╔╝██║  ██║██║   ██║      ██║   
╚══════╝╚══════╝ ╚═════╝ ╚═════╝ ╚═╝  ╚═╝╚═╝   ╚═╝      ╚═╝   

Last login: Thu May 27 03:14:15 2026 from 192.168.1.100
```

```
webhacker@team:~$ cat /etc/motd
```

> [!IMPORTANT]
> **我们正在寻找 0-day 猎手。**
> 如果你擅长 Web / Binary / IoT 漏洞挖掘，欢迎加入我们的远程团队。
> 邮箱已在下方公开，随时欢迎投递你的 POC。

```
webhacker@team:~$ ls -la /opt/arsenal/
```

| 🧠 漏洞挖掘 | ⚔️ 渗透测试 | 🔬 逆向工程 | ☁️ 云安全 |
|:-----------|:-----------|:-----------|:---------|
| `IDA Pro` `GDB/WinDbg` `CodeQL` | `Burp Suite` `Metasploit` `Nmap` | `Ghidra` `Frida` `dnSpy` | `K8s` `Docker` `AWS/Azure` |

```
webhacker@team:~$ cat /var/log/cve_disclosure.log
```

<details open>
<summary><b>📋 点击折叠 | 共发现 22 个漏洞，所有漏洞均已修复</b></summary>

<br />

| CVE ID | 漏洞类型 | 影响产品 | 严重度 |
|--------|----------|----------|:------:|
| [![CVE](https://img.shields.io/badge/CVE--2024--7962-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2024-7962) | Arbitrary File Read | gaizhenbiao/chuanhuchatgpt | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2024--8029-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2024-8029) | Cross-Site Scripting | imartinez/privategpt | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2024--12923-low?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2024-12923) | Cross-Site Scripting | Photo Station | 🟢 |
| [![CVE](https://img.shields.io/badge/CVE--2024--50405-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2024-50405) | CRLF Injection | QuTS hero | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2024--50406-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2024-50406) | Cross-Site Scripting | License Center | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2024--53693-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2024-53693) | CRLF Injection | QuTS hero | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2024--56804-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2024-56804) | SQL Injection | Video Station | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2024--56805-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2024-56805) | Buffer Overflow | QNAP OS | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2025--22481-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-22481) | Command Injection | QNAP OS | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2025--22482-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-22482) | Format String | Qsync Central | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2025--29898-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-29898) | Denial of Service | Qsync Central | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2025--30264-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-30264) | Command Injection | QNAP OS | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2025--30265-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-30265) | Buffer Overflow | QNAP OS | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2025--3535-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-3535) | Denial of Service | BurpAPIFinder v2.0.2 | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2025--52867-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-52867) | Denial of Service | Qsync Central | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2025--52868-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-52868) | Buffer Overflow | Qsync Central | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2025--52869-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-52869) | Buffer Overflow | Qsync Central | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2025--52870-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2025-52870) | Buffer Overflow | Qsync Central | 🔴 |
| [![CVE](https://img.shields.io/badge/CVE--2026--40532-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2026-40532) | Forced Browsing | Synology DSM | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2026--40536-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2026-40536) | Path Traversal | Synology DSM | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2026--46686-medium?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2026-46686) | Cross-Site Scripting | emlog/emlog | 🟡 |
| [![CVE](https://img.shields.io/badge/CVE--2026--46687-high?style=flat-square)](https://cve.org/CVERecord/SearchResults?query=CVE-2026-46687) | Local File Inclusion | emlog/emlog | 🔴 |

</details>

```
webhacker@team:~$ python3 analyze.py --cve-stats
```

<div align="center">

| 严重度 | 数量 | 占比 | 进度条 |
|:------:|:----:|:----:|:------:|
| 🔴 HIGH | 12 | 54.5% | `████████████████████████████` |
| 🟡 MEDIUM | 9 | 40.9% | `██████████████████████` |
| 🟢 LOW | 1 | 4.6% | `██` |

</div>

```
webhacker@team:~$ cat contact.info
```

<div align="center">

| 📧 Email | 🐙 GitHub |
|:--------:|:---------:|
| **web_hacker@163.com** | [@WebHackerTeam](https://github.com/WebHackerTeam) |

</div>

```
webhacker@team:~$ exit
Connection to github.com closed.
```

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/heart.svg" width="15" /> <sub>We hack for security, not for chaos.</sub>
</div>
