# 🔐 I Cracked My Own Password in Seconds with Hashcat (GPU)

<p align="center">
  <img src="https://via.placeholder.com/1200x400/0d1117/00ff9c?text=HASHCAT+GPU+CRACKING" />
</p>

<p align="center">
  <a href="https://www.mediafire.com/folder/8vkutyqghuno2/Hashcat">
    <img src="https://img.shields.io/badge/⚡ DOWNLOAD HASHCAT-GPU POWER-00ff9c?style=for-the-badge&logo=databricks&logoColor=black" />
  </a>
</p>

---

## ⚡ Live Demo (Realistic Terminal Animation)

<p align="center">
  <img src="./hashcat_demo.gif" width="800" />
</p>

---

## 🚀 Overview

This project shows how a **weak password can be cracked in seconds** using GPU acceleration with Hashcat.

💥 Real takeaway: speed + bad password = instant compromise

⚠️ For **educational and ethical testing only**.

---

## 🧠 What You'll Learn

* How password hashing actually works
* Why most passwords are brutally insecure
* How GPUs destroy brute-force time
* Real-world cracking workflow
* How to fully protect yourself

---

## 🖥️ Setup

### 1. Install / Download

Use the button above or:

```bash
sudo apt install hashcat
```

### 2. Verify GPU

```bash
hashcat -I
```

---

## 🔑 Example Hash

```text
5f4dcc3b5aa765d61d8327deb882cf99
```

👉 This is a weak MD5 hash (very common in leaks)

---

## ⚡ Cracking Command

```bash
hashcat -m 0 -a 0 hash.txt rockyou.txt
```

### 🔍 Breakdown

| Flag          | Meaning           |
| ------------- | ----------------- |
| `-m 0`        | MD5               |
| `-a 0`        | Dictionary attack |
| `hash.txt`    | Target            |
| `rockyou.txt` | Wordlist          |

---

## 🚀 GPU vs CPU Reality

| Device | Speed         |
| ------ | ------------- |
| CPU    | ~50 MH/s      |
| GPU    | ~10,000+ MH/s |

💀 GPUs = instant destruction of weak passwords

---

## 💣 Result

```text
Password FOUND: password
Time: < 1 second
```

Yes... it was that easy.

---

## 🛡️ How To Stay Safe

* Use 12–16+ character passwords
* Avoid dictionary words
* Use password manager
* Enable 2FA everywhere
* Prefer bcrypt / argon2

---

## 📁 Project Structure

```bash
.
├── hashes/
├── wordlists/
├── scripts/
├── hashcat_demo.gif
└── README.md
```

---

## 🎥 Video

👉 Add your YouTube video here

---

## ⚠️ Disclaimer

This repository is strictly for:

* Security research
* Ethical hacking
* Education

❌ Do NOT use on systems without permission

---

## ⭐ Support

If this helped you — drop a ⭐ and share 🚀
