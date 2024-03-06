<div align="center">
  <img src="https://github.com/FindAllTeam/findallteam.github.io/blob/master/public/logo.svg" alt="FindAll Logo" width="300px"/>
  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/version-1.4.0-blue.svg" alt="Version 1.2.0"/>
    <img src="https://img.shields.io/github/downloads/FindAllTeam/FindAll/total" alt="downloads" />
    <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="MIT License"/>
    <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-lightgrey.svg" alt="Platform: Windows | macOS"/>
  </p>
</div>

English | [简体中文](./README_ZH.md)

<h1>🔍 FindAll</h1>
  <p>
FindAll is a dedicated emergency response tool designed for network security blue teams to help team members respond to and analyze network security threats effectively. It integrates advanced information gathering and automated analysis capabilities to improve the efficiency and accuracy of security incident response.

FindAll adopts a client-server (CS) architecture that is particularly suitable for scenarios where users cannot directly log in to remote hosts for security checks. In such cases, operators with appropriate permissions only need to run FindAll's Agent component on the target hosts to collect necessary data.

The data is then downloaded locally for in-depth analysis by security experts through FindAll's intuitive graphical user interface (GUI). FindAll's interface is clean and straightforward, allowing users without extensive knowledge of complex command lines to get started easily, greatly lowering the barrier to entry.

This enables even beginners in the network security field to easily get started and effectively perform data analysis and security incident investigation. In addition, by reducing reliance on jump servers or other potential risk access points, FindAll also enhances the overall security and efficiency of the security inspection process, providing one-click analysis and preview of anomalies to quickly identify corresponding risks.

  </p>
 
## 🌟 Key Features

### 📊 Comprehensive Information Gathering

- **System basics**: Outputs detailed system info and checks config and patches to identify vulnerabilities.
- **Network info**: Analyzes current network connections. With Threatbook API, easily identifies abnormal networks, locates corresponding processes for analysis.
- **Startup items**: Examines auto-start programs.
- **Scheduled tasks**: Detects potentially malicious scheduled tasks.
- **Process investigation**: Identifies and analyzes suspicious processes to quickly locate backdoors.
- **Sensitive directory checks**: Checks abnormal changes in critical files and directories.
- **Log analysis**: Deep log analysis of system and apps to find traces of security events, aggregated for easy analysis.
- **Account detection**: Identifies hidden and cloned accounts in various scenarios.

### 🤖 Automated Threat Analysis (with Threatbook API)

- Auto-identifies abnormal IP, processes and files to improve analysis efficiency.
- Highlights anomalies for focused investigation.
- Threatbook：https://www.threatbook.cn/next/en/index

### ⚡ Rapid Anomaly Detection & Response

- Provides real-time detection and response suggestions to enable swift response.

### 🖥️ User-Friendly Interface

- Clean and intuitive interface suitable for all skill levels.
- Concise and clear, suitable for beginners.
- One-click previews of anomalies to quickly identify risks.

## ⚙️ Installation & Usage

### 🏗 Architecture

Adopts client-server architecture for one-click local scans or remote scanning via Agent, suitable when direct remote login is not possible.

### 🛠 Installation Steps

1. **Download and install with one click**：https://github.com/FindAllTeam/FindAll/releases
2. **Tips**
   - Local scan: Simply click to scan (recommended for Windows), local scanning is not supported on macOS.
   - Remote scan: An Agent client is provided separately. Run the Agent client independently, and the results will be located at `C:\\Findall\\result.hb`. Then, upload the result file to the FindAll GUI client for analysis.

### 💻 System Support

- GUI Client supports supports Windows 10 and above, as well as macOS.
- Serve Agent supports Windows Server 2008 and above
- Other systems need to be tested for compatibility

## 📖 Official Documentation

<a href="https://findallteam.github.io" target="_blank">https://findallteam.github.io</a>

## 📷 Screenshot

<img src="https://findallteam.github.io/preview1_en.jpg" alt="preview1_en.jpg">
<img src="https://findallteam.github.io/preview2_en.jpg" alt="preview2_en.jpg">
<img src="https://findallteam.github.io/preview3_en.jpg" alt="preview3_en.jpg">

## 👥 Contributor

<a href="https://github.com/FindAllTeam/FindAll/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=FindAllTeam/FindAll" />
</a>

## 📢 Announce

<p>
  The launch of this tool will greatly enhance the capabilities of blue teams in responding to network security incidents. It will not only help improve response efficiency but also reduce work complexity. By providing comprehensive information gathering and efficient threat analysis, we can empower blue team members to maintain an advantage in complex network environments. However, incident response is an extremely complicated task, and this tool can only help blue team members collect some information. If any anomalies are discovered, in-depth analysis directly on the client's computer is still required. The tool cannot be compared to commercial forensic analysis software available on the market.

Since this product is still in trial use, bugs may exist. If you encounter situations where the tool cannot run properly, please go to the issues page or join our WeChat group for discussions. The road ahead is long; we shall seek tirelessly (a Chinese idiom meaning perseverance is key to any endeavor).

</p>

## 📱 WeChat group QR code

<img src="https://github.com/FindAllTeam/FindAll/blob/main/images/QR.jpg?raw=true" alt="QR.jpg" width="500">

WeChat download address：https://www.wechat.com/en/

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=FindAllTeam/FindAll&type=Date)](https://star-history.com/#FindAllTeam/FindAll&Date)
