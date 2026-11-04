<p align="center">
  <img src="../../assets/OG-Banner-1200x630.png" alt="NidoOffice — Local-First AI Office Suite" width="100%" />
</p>

<h1 align="center">NidoOffice</h1>

<p align="center"><b>适用于 macOS、Windows 10/11 与 Linux 的本地优先 AI 办公套件</b></p>

<p align="center">
  <a href="https://github.com/stevedat/nidooffice-releases/releases/latest"><img src="https://img.shields.io/github/v/release/stevedat/nidooffice-releases?label=Release&color=10b981" alt="Latest Release" /></a>
  <a href="https://apps.microsoft.com/detail/9PDPX3W5J6D3"><img src="https://img.shields.io/badge/Microsoft_Store-9PDPX3W5J6D3-0078D4?logo=microsoft" alt="Microsoft Store" /></a>
  <a href="https://github.com/stevedat/homebrew-tap"><img src="https://img.shields.io/badge/Homebrew-stevedat%2Ftap%2Fnidooffice-FBB040?logo=homebrew" alt="Homebrew Cask" /></a>
  <a href="https://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache--2.0-38bdf8" alt="License" /></a>
</p>

<p align="center">
  🌐 <a href="../../README.md">English</a> · <a href="README.vi.md">Tiếng Việt</a> · <b>简体中文</b> · <a href="README.zh-TW.md">繁體中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.de.md">Deutsch</a> · <a href="README.pt-BR.md">Português (Brasil)</a> · <a href="README.ru.md">Русский</a>
</p>

**NidoOffice** 是一款面向 **macOS、Windows 10/11 和 Linux** 的高性能、本地优先（**Local-First**）桌面 AI 办公套件。原生支持 **Word（`.docx`）、Excel（`.xlsx`）、PowerPoint（`.pptx`）、PDF（含本地 OCR）、Markdown（`.md`）和 HTML** 六大格式。

---

## 📦 直接下载最新版（Evergreen 永久链接）

| 操作系统 / 平台 | 架构 | 直接下载链接 | 说明 |
| :--- | :--- | :--- | :--- |
| **macOS (Apple Silicon)** | `arm64` (M1 / M2 / M3 / M4) | [**NidoOffice-mac-arm64.dmg**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-mac-arm64.dmg) | Apple 公证与签名 (`.dmg`) |
| **macOS (Intel)** | `x64` | [**NidoOffice-mac-x64.dmg**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-mac-x64.dmg) | Apple 公证与签名 (`.dmg`) |
| **Windows 10 / 11** | `x64` (64-bit) | [**NidoOffice-win-x64.exe**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-x64.exe) | 标准 NSIS 安装程序 (`.exe`) |
| **Windows 10 / 11 (便携版)** | `x64` (免管理员权限) | [**NidoOffice-win-x64-portable.zip**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-x64-portable.zip) | 解压即用 (`.zip`) |
| **Windows 11 on ARM** | `arm64` (Snapdragon / Surface) | [**NidoOffice-win-arm64.exe**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-arm64.exe) | 原生 ARM64 安装包 (`.exe`) |
| **Microsoft Store** | `x64` & `arm64` | [**Microsoft Store — NidoOffice**](https://apps.microsoft.com/detail/9PDPX3W5J6D3) | 通过微软商店自动更新 |
| **Linux** | `arm64` | [**NidoOffice-linux-arm64.AppImage**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-linux-arm64.AppImage) | 独立运行包 `AppImage` |

---

## ⚡ 通过 Homebrew 安装 (macOS)

```bash
brew install --cask stevedat/tap/nidooffice
```

---

## 🌐 如何切换应用界面语言（支持 22 种语言）

NidoOffice 内置 **22 种界面语言**（包括简体中文、繁體中文、English、Tiếng Việt、日本語、한국어 等）：
1. 打开 **NidoOffice**，点击主界面左下角的 **设置（`⚙️` / Settings）** 图标（或按快捷键 `Cmd + ,` / `Ctrl + ,`）。
2. 在 **常规（General）** 选项卡中找到第一项 **语言（Language）**。
3. 选择 **简体中文** 或任意目标语言，界面将立即切换，无需重启应用。

---

## 🔐 校验 SHA-256 哈希值

```bash
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

- 📦 **所有版本：** [GitHub Releases](https://github.com/stevedat/nidooffice-releases/releases)
- 🌐 **官方网站：** [https://educenter.app](https://educenter.app)
- 🐛 **问题反馈：** [GitHub Issues](https://github.com/stevedat/nidooffice-releases/issues)
