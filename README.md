<p align="center">
  <img src="assets/OG-Banner-1200x630.png" alt="NidoOffice — Local-First AI Office Suite" width="100%" />
</p>

<h1 align="center">NidoOffice</h1>

<p align="center"><b>The Local-First AI Office Suite for macOS, Windows 10/11 & Linux</b></p>

<p align="center">
  <a href="https://github.com/stevedat/nidooffice-releases/releases/latest"><img src="https://img.shields.io/github/v/release/stevedat/nidooffice-releases?label=Release&color=10b981" alt="Latest Release" /></a>
  <a href="https://apps.microsoft.com/detail/9PDPX3W5J6D3"><img src="https://img.shields.io/badge/Microsoft_Store-9PDPX3W5J6D3-0078D4?logo=microsoft" alt="Microsoft Store" /></a>
  <a href="https://github.com/stevedat/homebrew-tap"><img src="https://img.shields.io/badge/Homebrew-stevedat%2Ftap%2Fnidooffice-FBB040?logo=homebrew" alt="Homebrew Cask" /></a>
  <a href="https://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache--2.0-38bdf8" alt="License" /></a>
</p>

<p align="center">
  🌐 <b>English</b> · <a href="docs/i18n/README.vi.md">Tiếng Việt</a> · <a href="docs/i18n/README.zh-CN.md">简体中文</a> · <a href="docs/i18n/README.zh-TW.md">繁體中文</a> · <a href="docs/i18n/README.ja.md">日本語</a> · <a href="docs/i18n/README.ko.md">한국어</a> · <a href="docs/i18n/README.es.md">Español</a> · <a href="docs/i18n/README.fr.md">Français</a> · <a href="docs/i18n/README.de.md">Deutsch</a> · <a href="docs/i18n/README.pt-BR.md">Português (Brasil)</a> · <a href="docs/i18n/README.ru.md">Русский</a>
</p>

**NidoOffice** is a high-performance, **Local-First** desktop office suite for **macOS, Windows 10/11, and Linux**. Create, view, edit, and automate with AI across all 6 native formats: **Word (`.docx`), Excel (`.xlsx`), PowerPoint (`.pptx`), PDF (with on-device OCR), Markdown (`.md`), and HTML**.

---

## 📦 Direct Downloads (Evergreen Latest Links)

All links below automatically point to the latest official release (`Latest Release`):

| Platform / OS | Architecture | Direct Installer Link | Notes |
| :--- | :--- | :--- | :--- |
| **macOS (Apple Silicon)** | `arm64` (M1 / M2 / M3 / M4) | [**NidoOffice-mac-arm64.dmg**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-mac-arm64.dmg) | Code-Signed & Apple Notarized (`.dmg`) |
| **macOS (Intel)** | `x64` | [**NidoOffice-mac-x64.dmg**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-mac-x64.dmg) | Code-Signed & Apple Notarized (`.dmg`) |
| **Windows 10 / 11 (Recommended)** | `x64` & `arm64` | [**NidoOffice-Store-Setup.exe**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-Store-Setup.exe) | Signed by Microsoft Corporation — 0 SmartScreen (`.exe`) |
| **Windows 10 / 11 (Offline)** | `x64` (64-bit) | [**NidoOffice-win-x64.exe**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-x64.exe) | Standard Offline NSIS Installer (`.exe`) |
| **Windows 10 / 11 (Portable)** | `x64` (No Admin Required) | [**NidoOffice-win-x64-portable.zip**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-x64-portable.zip) | Extract & run immediately (`.zip`) |
| **Windows 11 on ARM** | `arm64` (Snapdragon / Surface) | [**NidoOffice-win-arm64.exe**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-arm64.exe) | Native ARM64 Installer (`.exe`) |
| **Microsoft Store (MSIX)** | `x64` & `arm64` | [**Microsoft Store — NidoOffice**](https://apps.microsoft.com/detail/9PDPX3W5J6D3) | Auto-updates via Microsoft Store |
| **Linux** | `arm64` | [**NidoOffice-linux-arm64.AppImage**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-linux-arm64.AppImage) | Self-contained `AppImage` |

---

## ⚡ Install via Homebrew (macOS)

```bash
brew install --cask stevedat/tap/nidooffice
```

Upgrade to the latest version:
```bash
brew update && brew upgrade --cask nidooffice
```

---

## 🌐 Switching App Interface Language (22 Languages Supported)

NidoOffice supports **22 interface languages** out of the box:
> **English**, **Tiếng Việt**, **简体中文**, **繁體中文**, **日本語**, **한국어**, **Español**, **Français**, **Deutsch**, **Português (Brasil)**, **Русский**, **العربية**, **Italiano**, **Nederlands**, **Polski**, **Čeština**, **Bahasa Indonesia**, **Bahasa Melayu**, **ไทย**, **हिन्दी**, **עברית**, and **Türkçe**.

**How to switch language inside the app:**
1. Open **NidoOffice** and click the **Settings (`⚙️`)** icon in the bottom-left corner of the Home screen (or press `Cmd + ,` on macOS / `Ctrl + ,` on Windows & Linux).
2. In the **General** tab, locate **Language** (first option).
3. Select your preferred language (or **System default**) — the interface updates immediately without restarting.

---

## ✨ Core Capabilities

- **Word Processor (`.docx` / `.odt`):** Byte-preserving OOXML engine, **Tracked AI Diffs** with one-click accept/reject per paragraph, right-click **`AI Quick Actions ▸`** context menu, and **6 Offline Starter Templates** for business, administration, and education.
- **High-Speed Spreadsheets (`.xlsx`):** Powered by a native **Rust (`xlsx-sidecar`)** calculation engine supporting 400+ Excel formulas, Pivot Tables, charts, conditional formatting, and hundreds of thousands of rows on both `x64` and `arm64`.
- **Presentations (`.pptx` / `.odp`):** Slide Master editor, vector shapes, speaker notes, presenter view, and clickable `[Slide N]` AI citations.
- **PDF Studio, On-Device OCR & XML eTax Reader:** Edit PDF text directly in place via PDFium, convert scanned PDFs to Word/Excel/PowerPoint with on-device OCR, and inspect electronic tax/invoice `.xml` files.
- **`NidoDrop` Local Wi-Fi File Transfer (Auto-Stop TTL) & `VieLotusIM` Input Method:** Share files between PC and phone over local Wi-Fi QR code with automatic session shutoff (15m / 30m / 1h / 4h); built-in Vietnamese input method.
- **29 MCP Server Tools & Multi-Provider AI:** Connect with Nido AI, local coding CLIs (Claude Code, Codex, Antigravity, Kiro), Local LLMs (Ollama, LM Studio, vLLM), or Bring Your Own Key (BYOK).

---

## 💎 Edition & Cross-Platform Companion Account (`Educenter.app`)

| Feature | Standard Edition (100% Free Download) | Companion Pro (`Educenter.app` / Store Subscription) |
| :--- | :---: | :---: |
| **Native `.docx`, `.xlsx` (Rust), `.pptx`, `.pdf`, `.md`, `.html` Editors** | ✅ Free Forever | ✅ |
| **6 Offline Starter Templates & On-Device Format Conversions** | ✅ Free Forever | ✅ |
| **`NidoDrop` Local QR Transfer (Auto-Stop TTL) & `VieLotusIM`** | ✅ Free Forever | ✅ |
| **Local CLI / Ollama / Personal API Key (BYOK) & 29 MCP Tools** | ✅ Free Forever | ✅ |
| **Zero-Config Cloud AI (Claude, GPT, Gemini via Nido AI)** | 🔒 | ✅ **Instant Activation** |
| **Cross-Device Sync (Mac App Store, Microsoft Store & Direct Web Builds)** | 🔒 | ✅ **Unified Cloud Account** |
| **46+ Specialized AI Skills & `Educenter.app` Master Resource Library** | 🔒 | ✅ **Full Access** |

---

## 🔐 Verify SHA-256 Checksums

Every release includes [`SHA256SUMS.txt`](https://github.com/stevedat/nidooffice-releases/releases/latest/download/SHA256SUMS.txt). Verify your downloaded installer with:

```bash
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

- 📦 **All Releases:** [GitHub Releases](https://github.com/stevedat/nidooffice-releases/releases)
- 🌐 **Companion Platform:** [https://educenter.app](https://educenter.app)
- 🐛 **Bug Reports & Support:** [GitHub Issues](https://github.com/stevedat/nidooffice-releases/issues)
