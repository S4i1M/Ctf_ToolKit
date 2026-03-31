# 🔐 CTF Crypto & Stego Toolkit

> A crypto & steganography toolkit for CTF challenges. Auto-identify encodings, decode Base64/Hex/Binary, crack classical ciphers, and get steganography hints — available as a **web tool**, **Python CLI** and **markdown cheatsheet**.

![MIT License](https://img.shields.io/badge/license-MIT-00ff9d?style=flat-square)
![Made for CTF](https://img.shields.io/badge/made%20for-CTF-ff4d6d?style=flat-square)
![Python](https://img.shields.io/badge/python-3.x-4db8ff?style=flat-square)

---

## 📦 What's Inside

| File | Description |
|------|-------------|
| `ctf-crypto-toolkit.html` | Browser-based interactive tool — no install needed |
| `ctf_toolkit.py` | Python CLI script — run in terminal during CTF |
| `CTF_CRYPTO_STEGO_CHEATSHEET.md` | Quick reference cheatsheet |

---

## ✨ Features

- **Auto Identifier** — paste any string and it guesses the encoding or hash type
- **Base Encoding** — Base64, Base32, Hex, Binary, URL encode/decode
- **Hash Tools** — generate MD5, SHA1, SHA256, SHA512 + identify hash type
- **Classical Ciphers** — Caesar (with brute force), ROT13, Atbash, Vigenère, Morse code
- **Stego Hints** — checklist and commands for image, audio and file steganography
- **Cheatsheet** — pattern recognition guide for instantly identifying encodings

---

## 🚀 Usage

### Web Tool
Just open `ctf-crypto-toolkit.html` in any browser. No internet or install needed.

### Python CLI
```bash
python3 ctf_toolkit.py
```
Requires Python 3. No external dependencies.

### Cheatsheet
Open `CTF_CRYPTO_STEGO_CHEATSHEET.md` directly on GitHub or in any markdown viewer.

---

## 🖼️ Quick Encoding Reference

| Pattern | Encoding |
|---------|----------|
| `A-Z`, `2-7`, ends with `=` | Base32 |
| `A-Za-z0-9+/`, ends with `=` | Base64 |
| `0-9`, `a-f`, even length | Hex |
| Only `0` and `1`, groups of 8 | Binary |
| Only `. - /` and spaces | Morse Code |
| `%xx` format | URL Encoded |
| 32 hex chars | MD5 Hash |
| 64 hex chars | SHA-256 Hash |

---

## 🛠️ Tools Referenced in Cheatsheet

- [CyberChef](https://cyberchef.org) — all-in-one, try this first
- [CrackStation](https://crackstation.net) — hash cracking
- [dcode.fr](https://dcode.fr) — cipher identification
- Audacity — spectrogram analysis for audio stego
- steghide, zsteg, binwalk, exiftool — image/file stego

---

## 👤 Author

**S4i1M**   
Cyber Security Student | CTF Competitor | Offensive Security Enthusiast

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.  
Free to use, modify and share. Just keep the credit. 🙂
