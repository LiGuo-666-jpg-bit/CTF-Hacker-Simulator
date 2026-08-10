# 🕶️ CTF Hacker Simulator

一个**完全离线、单文件**的 CTF（夺旗赛）黑客模拟器。打开浏览器就能玩，零依赖、零安装。

## ✨ 特性

- 🔒 **单文件 HTML** — 下载即用，无需服务器、无需联网
- 🧩 **10 个关卡** — 覆盖侦察、Web渗透、加密、逆向、Pwn、取证、SQL注入、隐写、提权、终极挑战
- ⌨️ **真实终端体验** — 支持 Tab 补全、虚拟文件系统、命令解析
- 🎨 **赛博朋克 UI** — 绿色终端、ASCII 艺术、动画启动序列
- 🏆 **积分系统** — 完成任务获得分数，追踪进度

## 🚀 快速开始

### 方式一：直接打开
双击 `hacker_simulator.html` 即可在浏览器中运行。

### 方式二：本地服务器（推荐）
```bash
# Python 3
python3 -m http.server 8080

# 然后访问 http://localhost:8080/hacker_simulator.html
```

### 方式三：部署到 GitHub Pages
1. Fork 本仓库或上传到你的 GitHub
2. Settings → Pages → Source 选 `main`
3. 访问 `https://你的用户名.github.io/CTF_Hacker_Simulator/hacker_simulator.html`

## 🎮 玩法

| 命令 | 说明 |
|------|------|
| `help` | 查看所有可用命令 |
| `missions` | 查看任务列表 |
| `intel` | 获取当前任务提示 |
| `nmap -sn 10.0.0.0/24` | 扫描网络（任务1） |
| `cat 文件名` | 查看文件内容 |
| `ls` / `cd` / `pwd` | 文件导航 |
| `Tab` | 命令自动补全 |
| `Konami Code` | 🎮 试试 ↑↑↓↓←→←→BA |

## 📋 任务列表

| # | 名称 | 难度 | 奖励 |
|---|------|------|------|
| 01 | 靶场侦察 | EASY | 100 |
| 02 | 网页渗透 | EASY | 200 |
| 03 | 加密拦截 | MEDIUM | 300 |
| 04 | 逆向工程 | MEDIUM | 350 |
| 05 | 缓冲区溢出 | HARD | 500 |
| 06 | 取证分析 | MEDIUM | 400 |
| 07 | SQL注入 | EASY | 250 |
| 08 | 隐写术 | MEDIUM | 350 |
| 09 | 权限提升 | HARD | 450 |
| 10 | 终极挑战 | HARD | 1000 |

## 🛠️ 技术细节

- 纯原生 JavaScript，无框架依赖
- CSS 变量驱动主题，方便自定义配色
- 虚拟文件系统模拟真实 Linux 目录结构
- 所有"漏洞"和"Flag"均为模拟，不涉及真实系统

## 📜 License

MIT License — 随便玩，随便改，随便分享。

## ⚠️ 免责声明

本模拟器仅供**教育目的**。所有内容均为虚构，不涉及任何真实系统的攻击。请在法律允许的范围内学习网络安全知识。

---
Made with ☕ and `0x00` bytes.
