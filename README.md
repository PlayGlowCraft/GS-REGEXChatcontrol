# GS-Regex – Chatcontrol

This repository contains a regex-based filter list designed for use with **ChatControl** (non-Pro).

## 📄 File Included

- `GS-REGEX-Chatcontrol.yml`: A curated list of regex rules to block offensive and obfuscated language in chat.

## 📥 How to Use

**Do NOT replace your entire configuration file.**  
Instead, open your existing file located at:
/plugins/ChatControl/rules/global.rs
Then **copy and paste the contents** of `GS-REGEX-Chatcontrol.yml` into the appropriate section — usually under `match:` or wherever regex rules are handled.

After updating the file, **reload ChatControl** or restart your server to apply the changes.

## ✅ Features

- Detects offensive and obfuscated terms
- Regex rules optimized for performance and compatibility
- Lightweight and easy to integrate
- Actively used and maintained

---

Maintained by **GlowCraft Studios**.  
Free to use, adapt, and share.
