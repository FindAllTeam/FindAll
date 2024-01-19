<div align="center">
  <img src="https://github.com/FindAllTeam/findallteam.github.io/blob/master/public/logo.svg" alt="FindAll Logo" width="300px"/>
  <h1>🔍 FindAll</h1>
  <p>
    本工具是专为网络安全蓝队设计的应急响应工具，旨在帮助团队成员有效地应对和分析网络安全威胁。工具集成了先进的信息搜集和自动化分析功能，以提高安全事件应对的效率和准确性。
  </p>
  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version 1.0.0"/>
    <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="MIT License"/>
    <img src="https://img.shields.io/badge/platform-Windows%20|%20Linux%20|%20macOS-lightgrey.svg" alt="Platform: Windows, Linux, macOS"/>
  </p>
</div>

## 🌟 核心特点

### 📊 综合信息搜集
- **系统基本信息**: 检查系统配置和补丁，识别可利用的漏洞。
- **网络信息**: 分析当前网络连接和历史网络活动。
- **开机启动项**: 审查启动时自动执行的程序。
- **计划任务**: 检测可能隐藏的恶意计划任务。
- **进程排查**: 识别和分析运行中的可疑或异常进程，快速定位后门文件。
- **敏感目录排查**: 检查关键文件和目录的异常变更。
- **日志排查**: 深入分析系统和应用日志，寻找安全事件的痕迹。
- **账户检测**: 识别非授权或被篡改的用户账户。

### 🤖 自动化威胁分析
- 自动识别异常IP、进程和文件，显著提高分析效率。
- 突出显示异常情况，使得团队成员能够集中关注重点进程。

### ⚡ 快速异常识别与响应
- 提供即时的异常检测和响应建议，帮助蓝队迅速应对威胁。

### 🖥️ 用户友好界面
- 界面设计简洁直观，适合各水平的蓝队成员。

## ⚙️ 安装与使用

### 🏗 架构
FindAll采用客户端-服务器（CS）架构，适用于无法直接登录远程主机进行安全检查的场景。

### 🛠 安装步骤
1. **在目标主机上运行Agent**：
   - 拥有相应权限的运维人员在目标主机上运行FindAll的Agent组件以收集数据。
2. **数据传输**：
   - 收集到的数据可以轻松地被传输回本地。
3. **使用FindAll GUI进行分析**：
   - 安全专家通过FindAll的直观图形用户界面（GUI）进行深入分析。

### 🖥️ 界面设计
- 简洁明了，适合各水平用户，包括网络安全领域新手。
- 支持一键分析预览异常情况，快速定位风险项。

### 📦 安装包
- 直接下载安装包进行安装。
- 可选填写微步API进行自动化上传分析。

### 💻 系统支持
- 客户端支持Windows 10及以上版本。
-
