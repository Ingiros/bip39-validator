# 🚧 In Progress: BIP-39 Seed Phrase Validator in C

This project is a low-level BIP-39 mnemonic validator written entirely in C — with no Python, JavaScript, or high-level dependencies.

## 🔍 Purpose
The goal is to build a **real recovery tool** for BIP-39 wallets using only the C language.  
It's not just for practice — the focus is on real-world efficiency and security.

## ✅ Current Features
- [x] Input of 11 known words
- [x] Brute-force search of the 12th word
- [x] Validation using checksum
- [ ] PBKDF2-HMAC-SHA512 integration
- [ ] Seed generation from mnemonic
- [ ] Multi-word recovery (10, 9, 8 known words)

## 🗓️ Development Timeline
- **May 22** – Repository created
- **May 24** – Added 11-word input + brute-force logic
- **May 28** – SHA-512 + PBKDF2 implementation in progress

## 💡 What's Next
- Implement PBKDF2-HMAC-SHA512 using OpenSSL
- Generate and display the resulting 512-bit seed
- Expand recovery logic for fewer known words (10, 9, 8...)
- Add command-line options and usage documentation

## 🤝 Contribution
Right now this is a solo educational + practical project.  
Later I may consider opening it for collaboration.

## 🧾 License

This project is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).  
You may view and study this code for personal or educational purposes,  
but you may **not** use it commercially or distribute modified versions without permission.

---

💬 *This project is part of my deep dive into cryptography, systems programming, and secure wallet recovery. Stay tuned — it’s only the beginning.*

## Author  
🛡️ **Ingiros** — building tools that matter  
🔗 GitHub: [github.com/Ingiros](https://github.com/Ingiros)

## ☕ Support This Project

If you like this project, consider supporting it.  
Every cup of tea fuels more open-source work! 🍵

[![Donate](https://img.shields.io/badge/Donate-support-green)](https://donate.example.com)
