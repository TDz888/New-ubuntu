🧠 NEURAL MASTER SYSTEM v3.0 - ULTRA STABLE

🌟 Giới Thiệu

NEURAL MASTER SYSTEM là một hệ thống triển khai đa nền tảng tự động, cho phép bạn tạo và quản lý các máy chủ từ xa trên nhiều hệ điều hành khác nhau chỉ với một cú nhấp chuột.

⚡ "Một hệ thống thần kinh nhân tạo - Kết nối vạn nơi, vận hành tự động"

---

🎯 Tính Năng Chính

Tính năng Mô tả Trạng thái
🪟 Windows 11 Tự động cấu hình RDP, tạo user, mở firewall ✅ Hoạt động
🐧 Ubuntu 22.04/24.04 Cài đặt SSH, tạo user, cấu hình bảo mật ✅ Hoạt động
🐍 Debian 12 Container SSH với host keys tự động ✅ Hoạt động
📦 CentOS 9 Xử lý đặc biệt không curl conflict ✅ Hoạt động
🔷 AlmaLinux 9 Container SSH ổn định ✅ Hoạt động
📱 Telegram Bot Gửi thông tin đăng nhập tự động ✅ Hoạt động
⏱️ Runtime Manager Đếm ngược thời gian hoạt động ✅ Hoạt động
🧹 Auto Cleanup Tự động xóa dữ liệu sau khi kết thúc ✅ Hoạt động

---

🚀 Các Phương Thức Kết Nối

```
┌─────────────────────────────────────────────────────────────────┐
│                    🌐 PHƯƠNG THỨC KẾT NỐI 🌐                     │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   🪟 WINDOWS      →  Remote Desktop (RDP) - Port 3389          │
│   🐧 LINUX        →  SSH Secure Shell - Port 22                │
│   📱 TELEGRAM     →  Nhận thông tin tự động                     │
│   🌍 IP SOURCES   →  5 nguồn IP dự phòng                       │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

📋 Cấu Trúc Hệ Thống

```
NEURAL MASTER SYSTEM v3.0
│
├── 🧠 MASTER BRAIN
│   ├── Tạo session ID
│   ├── Quản lý thời gian
│   └── Điều phối worker
│
├── 🖥️ WORKER CORES
│   ├── Windows 11 Cortex
│   ├── Ubuntu 22.04 Cortex
│   ├── Ubuntu 24.04 Cortex
│   ├── Debian 12 Cortex
│   ├── CentOS 9 Cortex
│   └── AlmaLinux 9 Cortex
│
├── 📡 CONTROL HUB
│   ├── Telegram Notification
│   └── Status Reporting
│
└── 🧹 MEMORY PURGE
    ├── Auto Cleanup
    └── Data Wipe
```

---

🛠️ Cách Sử Dụng

1. Trigger Workflow

Vào tab Actions → Chọn NEURAL MASTER SYSTEM → Run workflow

2. Cấu Hình Parameters

Parameter Lựa chọn Mặc định Mô tả
⏱️ Duration 30m, 1h, 2h, 4h, 6h 2h Thời gian hoạt động
🎯 Target OS windows, ubuntu22, ubuntu24, debian, centos, almalinux, all windows Hệ điều hành đích
⚡ Performance balanced, performance, quantum balanced Chế độ hiệu suất
📱 Telegram true/false true Bật/tắt thông báo
🧹 Auto Cleanup true/false true Tự động dọn dẹp

3. Nhận Thông Tin Kết Nối

Sau khi chạy, Telegram sẽ nhận được tin nhắn với đầy đủ:

· 🌐 Địa chỉ IP
· 🔌 Cổng kết nối
· 👤 Tên đăng nhập
· 🔐 Mật khẩu
· 💻 Lệnh kết nối mẫu

---

🔧 Các Vấn Đề Đã Được Xử Lý

STT Vấn đề Giải pháp
1 CentOS curl conflict Dùng wget thay thế + --skip-broken
2 Container không có systemd Start SSH trực tiếp bằng /usr/sbin/sshd
3 Thiếu SSH host keys Tự động tạo bằng ssh-keygen -A
4 Không lấy được IP 5 nguồn IP dự phòng
5 YAML syntax error Loại bỏ @ và EOF
6 RDP không hoạt động Cấu hình registry + firewall

---

📊 Luồng Hoạt Động

```
┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│   START      │────▶│  MASTER      │────▶│  DEPLOY      │
│  Workflow    │     │  BRAIN       │     │  WORKER      │
└──────────────┘     └──────────────┘     └──────────────┘
                                                  │
                                                  ▼
┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│   CLEANUP    │◀────│  RUNTIME     │◀────│  TELEGRAM    │
│   MEMORY     │     │  MANAGER     │     │  NOTIFY      │
└──────────────┘     └──────────────┘     └──────────────┘
```

---

🔐 Bảo Mật

Tính năng Mô tả
🔑 Password ngẫu nhiên 24 ký tự, bao gồm chữ hoa, thường, số
👤 User ngẫu nhiên Tên user unique mỗi lần chạy
🧹 Auto cleanup Xóa toàn bộ dữ liệu sau khi kết thúc
🔒 No persistent data Không lưu trữ thông tin

---

📱 Ví Dụ Telegram Message

```
🧠 NEURAL MASTER SYSTEM v3.0

╔════════════════════════════════════════╗
📋 Session: NEURAL-20241215-143052-7842
⏱️ Duration: 2h
⏰ Ends: 2024-12-15 16:30:52 UTC
⚡ Mode: balanced
╚════════════════════════════════════════╝

🪟 WINDOWS 11
──────────────────
🌐 IP: 123.45.67.89:3389
👤 User: neural_5847
🔐 Pass: aB3dEf9gHiJkLmNoPqRsTu
💻 RDP: Remote Desktop Connection

✨ Neural System Online ✨
```

---

🎨 Icon Legend

Icon Ý nghĩa
🧠 Master Brain / Hệ thống chính
🪟 Windows OS
🐧 Ubuntu OS
🐍 Debian OS
📦 CentOS OS
🔷 AlmaLinux OS
📱 Telegram Notification
⏱️ Runtime Manager
🧹 Memory Purge / Cleanup
🌐 Network / IP
🔐 Password / Security
👤 User Account
✅ Success / Hoàn thành
❌ Error / Thất bại

---

📝 Yêu Cầu Hệ Thống

GitHub Secrets Cần Cấu Hình

Secret Mô tả Bắt buộc
TELEGRAM_BOT_TOKEN Bot Token từ BotFather ✅ Có (nếu dùng Telegram)
TELEGRAM_CHAT_ID Chat ID Telegram ✅ Có (nếu dùng Telegram)

Cách lấy Telegram Credentials

1. Tạo bot: @BotFather → /newbot
2. Lấy token: 1234567890:ABCdefGHIjklMNOpqrsTUVwxyz
3. Lấy chat ID: @userinfobot → gửi tin nhắn bất kỳ
4. Thêm vào GitHub Secrets

---

🐛 Xử Lý Sự Cố Thường Gặp

Vấn đề Nguyên nhân Cách khắc phục
Job bị skip Condition sai Chọn đúng target_os
Không kết nối được RDP Firewall chặn Kiểm tra port 3389
SSH timeout Container network Dùng IP từ Telegram
CentOS failed Curl conflict Đã fix trong code mới

---

📈 Phiên Bản

Version Ngày Thay đổi
v3.0.0 2024-12-01 Release đầu tiên
v3.0.5 2024-12-10 Fix CentOS systemd
v3.0.6 2024-12-12 Thêm host keys
v3.0.8 2024-12-15 Ultra stable, đa IP source

---

🙏 Cảm Ơn

Cảm ơn bạn đã sử dụng NEURAL MASTER SYSTEM!

🧠 "Kết nối không giới hạn - Vận hành không ngừng"

---

📞 Hỗ Trợ

Nếu gặp bất kỳ vấn đề nào, hãy kiểm tra:

1. Logs trong GitHub Actions
2. Telegram notification
3. Cấu hình Secrets

---

Made with 🧠 by Neural Master Team
