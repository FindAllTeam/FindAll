<div align="center">
  <img src="https://github.com/FindAllTeam/findallteam.github.io/blob/master/public/logo.svg" alt="FindAll Logo" width="300px"/>
  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version 1.0.0"/>
    <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="MIT License"/>
    <img src="https://img.shields.io/badge/platform-Windows%20|%20Linux%20|%20macOS-lightgrey.svg" alt="Platform: Windows, Linux, macOS"/>
  </p>
</div>
<h1>🔍 FindAll</h1>
  <p>
    本工具是专为网络安全蓝队设计的应急响应工具，旨在帮助团队成员有效地应对和分析网络安全威胁。工具集成了先进的信息搜集和自动化分析功能，以提高安全事件应对的效率和准确性。
    FindAll采用客户端-服务器（CS）架构，特别适用于那些无法直接登录远程主机进行安全检查的场景。在这种情况下，拥有相应权限的运维人员只需在目标主机上运行FindAll的Agent组件来收集必要的数据。
    随后，将数据下载到本地，供安全专家通过FindAll的直观图形用户界面（GUI）进行深入分析。
    FindAll的界面设计简洁明了，用户无需深入了解复杂的命令行操作，大大降低了使用门槛。
    这使得即使是网络安全领域的新手也能够轻松上手，有效地进行数据分析和安全事件排查。此外，通过减少对跳板机或其他潜在风险接入点的依赖，FindAll还提升了整个安全检查过程的安全性和效率，一键分析预览异常情况，快速定位相应的风险项。
  </p>
  <div align="center">
     <img src="https://github.com/FindAllTeam/FindAll/assets/93359280/0f9124a1-0ea2-411b-9815-839b1ea4ce4d" alt="FindAll Logo" width="800px"/>
  </div>
 
## 🌟 核心特点

### 📊 综合信息搜集
- **系统基本信息**: 除了输出系统详细信息以外，还会检查系统配置和补丁，识别可利用的漏洞。
- **网络信息**: 分析当前网络连接，如果填写了微步API即可轻松识别异常网络，本产品会根据异常网络情况找到对应的进程然后进行分析和识别。
- **开机启动项**: 审查启动时自动执行的程序。
- **计划任务**: 检测可能隐藏的恶意计划任务。
- **进程排查**: 识别和分析运行中的可疑或异常进程，快速定位后门文件。
- **敏感目录排查**: 检查关键文件和目录的异常变更。
- **日志排查**: 深入分析系统和应用日志，寻找安全事件的痕迹，会根据日志进行汇总方便人员进行分析。
- **账户检测**: 识别各个场景下创建的隐藏账户、克隆账户。

### 🤖 自动化威胁分析(填写微步API后)
- 自动识别异常IP、进程和文件，显著提高分析效率。
- 突出显示异常情况，使得团队成员能够集中关注重点进程。

### ⚡ 快速异常识别与响应
- 提供即时的异常检测和响应建议，帮助蓝队迅速应对威胁。

### 🖥️ 用户友好界面
- 界面设计简洁直观，适合各水平的蓝队成员。

## ⚙️ 安装与使用

### 🏗 架构
FindAll采用客户端-服务器（CS）架构，可以在本地进行一键扫描，也可以使用Agent进行扫描然后录入扫描结果，适用于无法直接登录远程主机进行安全检查的场景。

### 🛠 安装步骤
1. **安装包安装即可**：
   - 远程扫描：Agent位于C:\Program Files\FindAll\resources\buildResources，结果位于C:\\Findall\\result.hb
   - 本地扫描：一键扫描即可

### 🖥️ 界面设计
- 简洁明了，适合各水平用户，包括网络安全领域新手。
- 支持一键分析预览异常情况，快速定位风险项。


### 💻 系统支持
- 客户端支持Windows 10及以上版本。
- 服务器支持Windows Server 2008及以上版本。
- 其他系统需自行测试兼容性。
