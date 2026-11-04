<p align="center">
  <img src="../../assets/OG-Banner-1200x630.png" alt="NidoOffice — Local-First AI Office Suite" width="100%" />
</p>

<h1 align="center">NidoOffice</h1>

<p align="center"><b>Bộ Ứng Dụng Văn Phòng AI Nội Bộ (Local-First AI Office Suite) cho macOS, Windows 10/11 & Linux</b></p>

<p align="center">
  <a href="https://github.com/stevedat/nidooffice-releases/releases/latest"><img src="https://img.shields.io/github/v/release/stevedat/nidooffice-releases?label=Release&color=10b981" alt="Latest Release" /></a>
  <a href="https://apps.microsoft.com/detail/9PDPX3W5J6D3"><img src="https://img.shields.io/badge/Microsoft_Store-9PDPX3W5J6D3-0078D4?logo=microsoft" alt="Microsoft Store" /></a>
  <a href="https://github.com/stevedat/homebrew-tap"><img src="https://img.shields.io/badge/Homebrew-stevedat%2Ftap%2Fnidooffice-FBB040?logo=homebrew" alt="Homebrew Cask" /></a>
  <a href="https://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache--2.0-38bdf8" alt="License" /></a>
</p>

<p align="center">
  🌐 <a href="../../README.md">English</a> · <b>Tiếng Việt</b> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.zh-TW.md">繁體中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.de.md">Deutsch</a> · <a href="README.pt-BR.md">Português (Brasil)</a> · <a href="README.ru.md">Русский</a>
</p>

**NidoOffice** là bộ ứng dụng văn phòng máy tính tốc độ cao, ưu tiên xử lý cục bộ (**Local-First**) dành cho **macOS, Windows 10/11 và Linux**. Hỗ trợ tạo mới, xem, biên tập và tự động hóa bằng AI trên đầy đủ 6 định dạng: **Word (`.docx`), Excel (`.xlsx`), PowerPoint (`.pptx`), PDF (kèm OCR tiếng Việt trên thiết bị), Markdown (`.md`) và HTML**.

---

## 📦 Tải Nhanh Bộ Cài Mới Nhất (Evergreen Links)

Các liên kết dưới đây luôn tự động trỏ tới phiên bản chính thức mới nhất (`Latest Release`):

| Hệ điều hành / Platform | Kiến trúc | Bộ cài trực tiếp / Direct Download | Ghi chú |
| :--- | :--- | :--- | :--- |
| **macOS (Apple Silicon)** | `arm64` (M1 / M2 / M3 / M4) | [**NidoOffice-mac-arm64.dmg**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-mac-arm64.dmg) | Đã ký số & Apple Notarized (`.dmg`) |
| **macOS (Intel)** | `x64` | [**NidoOffice-mac-x64.dmg**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-mac-x64.dmg) | Đã ký số & Apple Notarized (`.dmg`) |
| **Windows 10 / 11** | `x64` (64-bit) | [**NidoOffice-win-x64.exe**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-x64.exe) | Bộ cài chuẩn NSIS (`.exe`) |
| **Windows 10 / 11 (Portable)** | `x64` (Không cần quyền Admin) | [**NidoOffice-win-x64-portable.zip**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-x64-portable.zip) | Giải nén chạy ngay (`.zip`) |
| **Windows 11 on ARM** | `arm64` (Snapdragon / Surface) | [**NidoOffice-win-arm64.exe**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-win-arm64.exe) | Bộ cài gốc ARM64 (`.exe`) |
| **Windows Store (MSIX)** | `x64` & `arm64` | [**Microsoft Store — NidoOffice**](https://apps.microsoft.com/detail/9PDPX3W5J6D3) | Tự động cập nhật qua Microsoft Store |
| **Linux** | `arm64` | [**NidoOffice-linux-arm64.AppImage**](https://github.com/stevedat/nidooffice-releases/releases/latest/download/NidoOffice-linux-arm64.AppImage) | Gói độc lập `AppImage` |

---

## ⚡ Cài Đặt Qua Homebrew (macOS)

```bash
brew install --cask stevedat/tap/nidooffice
```

Cập nhật lên phiên bản mới:
```bash
brew update && brew upgrade --cask nidooffice
```

---

## 🌐 Cách Chuyển Ngôn Ngữ Giao Diện Trong Ứng Dụng (Hỗ Trợ 22 Ngôn Ngữ)

NidoOffice tích hợp sẵn **22 ngôn ngữ giao diện**:
> **Tiếng Việt**, **English**, **简体中文**, **繁體中文**, **日本語**, **한국어**, **Español**, **Français**, **Deutsch**, **Português (Brasil)**, **Русский**, **العربية**, **Italiano**, **Nederlands**, **Polski**, **Čeština**, **Bahasa Indonesia**, **Bahasa Melayu**, **ไทย**, **हिन्दी**, **עברית**, và **Türkçe**.

**Thao tác đổi ngôn ngữ trong ứng dụng:**
1. Mở **NidoOffice**, nhấn biểu tượng **Cài đặt (`⚙️` / Settings)** ở góc dưới bên trái màn hình chính (hoặc nhấn phím tắt `Cmd + ,` trên macOS / `Ctrl + ,` trên Windows & Linux).
2. Tại mục **Chung (General)**, chọn ô **Ngôn ngữ (Language)** ở dòng đầu tiên.
3. Chọn **Tiếng Việt**, **English** hoặc ngôn ngữ mong muốn (hoặc **Mặc định hệ thống / System default**) — toàn bộ giao diện sẽ chuyển đổi tức thì mà không cần khởi động lại ứng dụng.

---

## ✨ Năng Lực Cốt Lõi

- **Soạn thảo Văn bản (`.docx` / `.odt`):** Bảo toàn cấu trúc OOXML cấp độ byte, theo dõi thay đổi của AI (`Tracked AI Diffs`) cho phép chấp nhận hoặc hoàn tác từng đoạn bằng 1 cú nhấp, menu chuột phải **`Tác vụ nhanh AI ▸`** và kệ **6 mẫu tài liệu Offline (`Starter templates`)** chuẩn văn phòng & giáo dục Việt Nam.
- **Bảng tính Tốc độ Cao (`.xlsx`):** Vận hành bởi nhân tính toán gốc viết bằng **Rust (`xlsx-sidecar`)**, hỗ trợ hơn 400 hàm Excel, Pivot Table, biểu đồ, định dạng có điều kiện và xử lý hàng trăm nghìn dòng mượt mà trên cả `x64` và `arm64`.
- **Trình chiếu Chuyên nghiệp (`.pptx` / `.odp`):** Thiết kế Slide Master, hình khối vector, ghi chú diễn giả, chế độ thuyết trình và trích dẫn AI `[Slide N]` nhấp nhảy trang tức thì.
- **PDF Studio, OCR Tiếng Việt & Trình đọc Thuế XML (`eTax`):** Chỉnh sửa văn bản PDF trực tiếp bằng nhân PDFium, nhận diện chữ OCR ngay trên thiết bị và đọc tờ khai/hóa đơn điện tử `.xml`.
- **Truyền tệp Nội bộ `NidoDrop` (Auto-Stop TTL) & Bộ gõ `Sen Việt` (`VieLotusIM`):** Chia sẻ file giữa máy tính và điện thoại qua mã QR Wi-Fi nội bộ với cơ chế tự ngắt sau 15 phút / 30 phút / 1 giờ / 4 giờ; tích hợp sẵn bộ gõ tiếng Việt tốc độ cao.
- **29 Công cụ MCP Server & Đa Nhà Cung Cấp AI:** Kết nối trực tiếp với Nido AI, các CLI cục bộ (Claude Code, Codex, Antigravity, Kiro), Local LLM (Ollama, LM Studio, vLLM) hoặc khóa API riêng (BYOK).

---

## 💎 Mô Hình Sử Dụng & Tài Khoản Đồng Hành Đa Nền Tảng (`Educenter.app`)

| Tính năng | Bản Tiêu Chuẩn (Tải về Miễn phí 100%) | Gói Đồng Hành (`Educenter.app` / Store Pro) |
| :--- | :---: | :---: |
| **Trình biên tập `.docx`, `.xlsx` (Rust), `.pptx`, `.pdf`, `.md`, `.html`** | ✅ Miễn phí trọn đời | ✅ |
| **6 Mẫu tài liệu Offline (`Starter templates`: CV 5512, Đề thi, Sổ điểm...)** | ✅ Miễn phí trọn đời | ✅ |
| **Truyền tệp nội bộ `NidoDrop` (QR Wi-Fi + Auto-Stop TTL) & Bộ gõ `VieLotusIM`** | ✅ Miễn phí trọn đời | ✅ |
| **Kết nối AI qua CLI cục bộ / Ollama / Khóa API cá nhân (BYOK) & 29 MCP Tools** | ✅ Miễn phí trọn đời | ✅ |
| **Kích hoạt AI đám mây tức thì không cần tự cấu hình API Key** | 🔒 | ✅ **Tự động kích hoạt** |
| **Đồng bộ quyền lợi giữa Mac App Store, Microsoft Store & Bản tải Web** | 🔒 | ✅ **Liên kết 1 tài khoản** |
| **46+ Kỹ năng AI chuyên ngành & Kho học liệu / hồ sơ gốc Master (`Educenter.app`)** | 🔒 | ✅ **Đồng bộ đầy đủ** |

---

## 🔐 Kiểm Chứng Toàn Vẹn Tệp (SHA-256 Checksums)

Mỗi bản phát hành đều đính kèm tệp [`SHA256SUMS.txt`](https://github.com/stevedat/nidooffice-releases/releases/latest/download/SHA256SUMS.txt). Bạn có thể kiểm tra chữ ký băm sau khi tải về:

```bash
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

- 📦 **Danh sách toàn bộ các bản phát hành:** [GitHub Releases](https://github.com/stevedat/nidooffice-releases/releases)
- 🌐 **Nền tảng Học liệu & Đồng Hành:** [https://educenter.app](https://educenter.app)
- 🐛 **Báo lỗi & Hỗ trợ kỹ thuật:** [GitHub Issues](https://github.com/stevedat/nidooffice-releases/issues)
