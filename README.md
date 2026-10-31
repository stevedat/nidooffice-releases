<p align="center">
  <img src="assets/OG-Banner-1200x630.png" alt="NidoOffice — Local-First AI Office Suite" width="100%" />
</p>

# NidoOffice — Bộ Ứng Dụng Văn Phòng AI Nội Bộ (Local-First AI Office Suite)

[![Latest Release](https://img.shields.io/github/v/release/stevedat/nidooffice-releases?label=Release&color=10b981)](https://github.com/stevedat/nidooffice-releases/releases/latest)
[![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-9PDPX3W5J6D3-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PDPX3W5J6D3)
[![Homebrew Cask](https://img.shields.io/badge/Homebrew-stevedat%2Ftap%2Fnidooffice-FBB040?logo=homebrew)](https://github.com/stevedat/homebrew-tap)
[![License](https://img.shields.io/badge/License-Apache--2.0-38bdf8)](https://www.apache.org/licenses/LICENSE-2.0)

**NidoOffice** là bộ ứng dụng văn phòng máy tính tốc độ cao, ưu tiên xử lý cục bộ (**Local-First**) dành cho **macOS, Windows 10/11 và Linux**. Hỗ trợ tạo mới, xem, biên tập và tự động hóa bằng AI trên đầy đủ 6 định dạng: **Word (`.docx`), Excel (`.xlsx`), PowerPoint (`.pptx`), PDF (kèm OCR tiếng Việt), Markdown (`.md`) và HTML**.

---

## 📦 Tải Nhanh Bộ Cài Mới Nhất / Direct Downloads (Evergreen Links)

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

## ✨ Năng Lực Cốt Lõi / Core Capabilities

- **Soạn thảo Văn bản (`.docx` / `.odt`):** Bảo toàn cấu trúc OOXML cấp độ byte, theo dõi thay đổi của AI (`Tracked AI Diffs`) cho phép chấp nhận hoặc hoàn tác từng đoạn bằng 1 cú nhấp, menu chuột phải **`Tác vụ nhanh AI ▸`** và kệ **6 mẫu tài liệu Offline (`Starter templates`)** chuẩn văn phòng & giáo dục Việt Nam.
- **Bảng tính Tốc độ Cao (`.xlsx`):** Vận hành bởi nhân tính toán gốc viết bằng **Rust (`xlsx-sidecar`)**, hỗ trợ hơn 400 hàm Excel, Pivot Table, biểu đồ, định dạng có điều kiện và xử lý hàng trăm nghìn dòng mượt mà trên cả `x64` và `arm64`.
- **Trình chiếu Chuyên nghiệp (`.pptx` / `.odp`):** Thiết kế Slide Master, hình khối vector, ghi chú diễn giả, chế độ thuyết trình và trích dẫn AI `[Slide N]` nhấp nhảy trang tức thì.
- **PDF Studio, OCR Tiếng Việt & Trình đọc Thuế XML (`eTax`):** Chỉnh sửa văn bản PDF trực tiếp bằng nhân PDFium, nhận diện chữ OCR ngay trên thiết bị và đọc tờ khai/hóa đơn điện tử `.xml`.
- **Truyền tệp Nội bộ `NidoDrop` (Auto-Stop TTL) & Bộ gõ `Sen Việt` (`VieLotusIM`):** Chia sẻ file giữa máy tính và điện thoại qua mã QR Wi-Fi nội bộ với cơ chế tự ngắt sau 15 phút / 30 phút / 1 giờ / 4 giờ; tích hợp sẵn bộ gõ tiếng Việt tốc độ cao.
- **29 Công cụ MCP Server & Đa Nhà Cung Cấp AI:** Kết nối trực tiếp với Nido AI, các CLI cục bộ (Claude Code, Codex, Antigravity, Kiro), Local LLM (Ollama, LM Studio, vLLM) hoặc khóa API riêng (BYOK).

---

## 💎 Mô Hình Sử Dụng / Edition & Companion Account (`Educenter.app`)

| Tính năng | Bản Tiêu Chuẩn (Tải về Miễn phí 100%) | Gói Đồng Hành (`Educenter.app` Companion Pro) |
| :--- | :---: | :---: |
| **Trình biên tập `.docx`, `.xlsx` (Rust), `.pptx`, `.pdf`, `.md`, `.html`** | ✅ Miễn phí trọn đời | ✅ |
| **6 Mẫu tài liệu Offline (`Starter templates`: CV 5512, Đề thi, Sổ điểm...)** | ✅ Miễn phí trọn đời | ✅ |
| **Truyền tệp nội bộ `NidoDrop` (QR Wi-Fi + Auto-Stop TTL) & Bộ gõ `VieLotusIM`** | ✅ Miễn phí trọn đời | ✅ |
| **Kết nối AI qua CLI cục bộ / Ollama / Khóa API cá nhân (BYOK) & 29 MCP Tools** | ✅ Miễn phí trọn đời | ✅ |
| **Kích hoạt AI tức thì không cần tự cấu hình API Key** | 🔒 | ✅ **Tự động kích hoạt** |
| **46+ Kỹ năng AI chuyên ngành & Kho học liệu / hồ sơ gốc Master (`Educenter.app`)** | 🔒 | ✅ **Đồng bộ đầy đủ** |

---

## 🔐 Kiểm Chứng Toàn Vẹn Tệp / Verify SHA-256 Checksums

Mỗi bản phát hành đều đính kèm tệp [`SHA256SUMS.txt`](https://github.com/stevedat/nidooffice-releases/releases/latest/download/SHA256SUMS.txt). Bạn có thể kiểm tra chữ ký băm sau khi tải về:

```bash
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

- 📦 **Danh sách toàn bộ các bản phát hành:** [GitHub Releases (`v0.12.2`, `v0.12.1`, ...)](https://github.com/stevedat/nidooffice-releases/releases)
- 🌐 **Nền tảng Học liệu & Đồng Hành:** [https://educenter.app](https://educenter.app)
- 🐛 **Báo lỗi & Hỗ trợ kỹ thuật:** [GitHub Issues](https://github.com/stevedat/nidooffice-releases/issues)
