# 🧠 NEURAL MASTER SYSTEM v3.0

═══════════════════════════════════════════════════════════════════════════════

📌 VERSION: 3.0.13 | ✅ STATUS: STABLE | 🖥️ PLATFORM: WINDOWS + LINUX | 🔗 TAILSCALE: ENABLED

═══════════════════════════════════════════════════════════════════════════════

🚀 Multi-OS Remote Access System | 🔗 Tailscale Integration | 🧹 Auto Cleanup

═══════════════════════════════════════════════════════════════════════════════

📋 FEATURES

┌─────────────────────────────────────────────────────────────────────────────┐
│ 🖥️ Multi-OS Support      │ Windows 11, Ubuntu 22.04, Ubuntu 24.04,          │
│                          │ Debian 12, CentOS 9, AlmaLinux 9                  │
├─────────────────────────────────────────────────────────────────────────────┤
│ 🔗 Tailscale Integration │ Automatic installation and connection            │
├─────────────────────────────────────────────────────────────────────────────┤
│ 📱 Telegram Notifications│ Receive connection credentials on Telegram       │
├─────────────────────────────────────────────────────────────────────────────┤
│ ⏱️ Session Management    │ Configurable duration: 30m to 6h                  │
├─────────────────────────────────────────────────────────────────────────────┤
│ 🧹 Auto Cleanup          │ Automatic credential destruction after session   │
├─────────────────────────────────────────────────────────────────────────────┤
│ 🌐 Dual Connection       │ Both public IP and Tailscale IP provided         │
└─────────────────────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════════════

🚀 QUICK START

📋 PREREQUISITES:

   1. GitHub Repository with Actions enabled
   2. Tailscale Account (free tier available)
   3. Telegram Bot (optional)

🔐 REQUIRED SECRETS:

   Go to: Repository → Settings → Secrets and variables → Actions → Add new secrets

   ┌──────────────────────┬────────────────────────────────────────────────┐
   │ TAILSCALE_AUTH_KEY   │ Your Tailscale authentication key              │
   │ TELEGRAM_BOT_TOKEN   │ Bot token from @BotFather (optional)           │
   │ TELEGRAM_CHAT_ID     │ Your Telegram chat ID (optional)               │
   └──────────────────────┴────────────────────────────────────────────────┘

🎯 ONE-CLICK DEPLOYMENT:

   Step 1: Navigate to Actions tab in your repository
   Step 2: Select "NEURAL MASTER SYSTEM v3.0"
   Step 3: Click "Run workflow"
   Step 4: Configure your session parameters
   Step 5: Click "Run workflow"

   ✨ Your remote machine will be ready in 30-60 seconds!

═══════════════════════════════════════════════════════════════════════════════

⚙️ CONFIGURATION

⏱️ SESSION DURATION OPTIONS:

   ┌─────────┬────────────────────────────────────────────────────────────┐
   │ 30m     │ 30 minutes                                                 │
   │ 1h      │ 1 hour                                                     │
   │ 2h      │ 2 hours (default)                                          │
   │ 4h      │ 4 hours                                                    │
   │ 6h      │ 6 hours                                                    │
   └─────────┴────────────────────────────────────────────────────────────┘

🎯 TARGET OS OPTIONS:

   ┌─────────────┬────────────────────────────────────────────────────────┐
   │ windows     │ Windows 11 only                                        │
   │ ubuntu22    │ Ubuntu 22.04 LTS only                                  │
   │ ubuntu24    │ Ubuntu 24.04 LTS only                                  │
   │ debian      │ Debian 12 only                                         │
   │ centos      │ CentOS Stream 9 only                                   │
   │ almalinux   │ AlmaLinux 9 only                                       │
   │ all         │ All supported operating systems                        │
   └─────────────┴────────────────────────────────────────────────────────┘

⚡ PERFORMANCE MODES:

   ┌─────────────┬────────────────────────────────────────────────────────┐
   │ balanced    │ Standard performance (default)                         │
   │ performance │ Optimized for speed                                    │
   │ quantum     │ Maximum resource allocation                            │
   └─────────────┴────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════════════

📱 TELEGRAM NOTIFICATION EXAMPLE

   🤖 NEURAL MASTER SYSTEM v3.0

   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

   📋 SESSION INFORMATION
   ────────────────────────────────────────────────────────────────────────
   🆔 Session ID: NEURAL-20241215-143022-4712
   ⏱️ Duration: 2h
   ⏰ Expires: 2024-12-15 16:30:22 UTC
   ⚡ Mode: balanced

   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

   🪟 WINDOWS 11
   ────────────────────────────────────────────────────────────────────────
   🌍 Public RDP: 172.182.224.164:3389
   🔗 Tailscale RDP: 100.64.0.1:3389
   👤 Username: neural_7838
   🔐 Password: QAR7D2FugGzC4x6dsSEV

   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

   ✅ System Online
   🔒 Connect via Tailscale for secure access

   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

═══════════════════════════════════════════════════════════════════════════════

🔌 CONNECTION METHODS

🌍 METHOD 1: DIRECT CONNECTION (PUBLIC IP)

   Windows RDP: 172.182.224.164:3389
   Linux SSH:   ssh user@172.182.224.164 -p 22

🔗 METHOD 2: TAILSCALE VPN (RECOMMENDED)

   Windows RDP: 100.64.0.1:3389
   Linux SSH:   ssh user@100.64.0.1 -p 22

💡 WHY TAILSCALE?

   Tailscale creates an encrypted mesh VPN, eliminating the need for port 
   forwarding and providing secure access even behind NAT. It's like having 
   your own private network!

═══════════════════════════════════════════════════════════════════════════════

🖥️ SUPPORTED OPERATING SYSTEMS

   ┌─────────────┬──────────────────┬──────────────────┬────────────┐
   │ OS          │ Version          │ Access Method    │ Status     │
   ├─────────────┼──────────────────┼──────────────────┼────────────┤
   │ Windows 11  │ 22H2+            │ RDP (Port 3389)  │ 🟢 Stable  │
   │ Ubuntu      │ 22.04 LTS        │ SSH (Port 22)    │ 🟢 Stable  │
   │ Ubuntu      │ 24.04 LTS        │ SSH (Port 22)    │ 🟢 Stable  │
   │ Debian      │ 12 Bookworm      │ SSH (Port 22)    │ 🟢 Stable  │
   │ CentOS      │ Stream 9         │ SSH (Port 22)    │ 🟢 Stable  │
   │ AlmaLinux   │ 9                │ SSH (Port 22)    │ 🟢 Stable  │
   └─────────────┴──────────────────┴──────────────────┴────────────┘

═══════════════════════════════════════════════════════════════════════════════

🛡️ SECURITY FEATURES

   ┌─────────────────────────┬────────────────────────────────────────────┐
   │ 🔄 Auto Credential      │ New random credentials for each session    │
   │    Rotation             │                                            │
   ├─────────────────────────┼────────────────────────────────────────────┤
   │ ⏰ Session Timeout      │ Automatic termination after duration       │
   ├─────────────────────────┼────────────────────────────────────────────┤
   │ 🧹 Memory Purge         │ Complete cleanup of all temporary data     │
   ├─────────────────────────┼────────────────────────────────────────────┤
   │ 🔒 Tailscale Encryption │ End-to-end encrypted connections           │
   ├─────────────────────────┼────────────────────────────────────────────┤
   │ 🚫 No Port Forwarding   │ Secure access without exposing ports       │
   └─────────────────────────┴────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════════════

🔧 TROUBLESHOOTING

❌ TAILSCALE CONNECTION ISSUES

   Step 1: Verify your TAILSCALE_AUTH_KEY is valid and not expired
   Step 2: Ensure the key has not been used on too many devices
   Step 3: Regenerate a new key from the Tailscale admin console

📱 NO TELEGRAM NOTIFICATION

   Step 1: Check that TELEGRAM_BOT_TOKEN and TELEGRAM_CHAT_ID are set
   Step 2: Ensure the bot has started a conversation with your chat ID
   Step 3: Verify the bot has permission to send messages

🔌 CONNECTION REFUSED

   Step 1: Wait 30-60 seconds for services to fully initialize
   Step 2: Verify Tailscale is connected (tailscale status)
   Step 3: Check if the session duration has expired

🪟 WINDOWS DEPLOYMENT FAILS

   Step 1: Ensure runner is windows-latest
   Step 2: Check firewall rules are applied correctly
   Step 3: Verify Terminal Services are running

🐧 LINUX SSH CONNECTION FAILS

   Step 1: Check if SSH service is running (systemctl status ssh)
   Step 2: Verify password authentication is enabled
   Step 3: Ensure port 22 is open

═══════════════════════════════════════════════════════════════════════════════

📊 SYSTEM ARCHITECTURE

   ┌─────────────────────────────────────────────────────────────────────────┐
   │                         GITHUB ACTIONS                                   │
   │  ┌───────────┐    ┌───────────┐    ┌───────────┐                       │
   │  │  MASTER   │───▶│  WINDOWS  │───▶│   LINUX   │                       │
   │  │   BRAIN   │    │ DEPLOYMENT│    │ DEPLOYMENT│                       │
   │  └───────────┘    └───────────┘    └───────────┘                       │
   │       │                │                │                               │
   │       ▼                ▼                ▼                               │
   │  ┌─────────────────────────────────────────────────────────────────┐   │
   │  │                      TAILSCALE NETWORK                           │   │
   │  │                 Encrypted Mesh VPN Connection                    │   │
   │  └─────────────────────────────────────────────────────────────────┘   │
   │       │                │                │                               │
   │       ▼                ▼                ▼                               │
   │  ┌─────────────────────────────────────────────────────────────────┐   │
   │  │                        TELEGRAM BOT                              │   │
   │  │                   Send Connection Credentials                    │   │
   │  └─────────────────────────────────────────────────────────────────┘   │
   └─────────────────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════════════

📝 LICENSE

   MIT License - Free for personal and commercial use

   Copyright (c) 2024 Neural Master System

   Permission is hereby granted, free of charge, to any person obtaining a copy
   of this software and associated documentation files...

═══════════════════════════════════════════════════════════════════════════════

🙏 ACKNOWLEDGMENTS

   🏆 Tailscale      - Excellent VPN technology
   🏆 GitHub Actions - Powerful automation platform
   🏆 Telegram       - Great messaging API

═══════════════════════════════════════════════════════════════════════════════

📞 SUPPORT

   📧 Email:  support@neuralmaster.com
   🐛 Issues: https://github.com/your-repo/issues
   💡 Ideas:  https://github.com/your-repo/discussions

═══════════════════════════════════════════════════════════════════════════════

<div align="center">

**🧠 NEURAL MASTER SYSTEM v3.0**

*Built for remote access automation*

</div>

═══════════════════════════════════════════════════════════════════════════════
