# 🔐 I Cracked My Own Password in Seconds with Hashcat (GPU)

<p align="center">
  <img src="https://via.placeholder.com/1200x400/0d1117/00ff9c?text=HASHCAT+GPU+CRACKING" />
</p>

<p align="center">
  <a href="https://www.mediafire.com/folder/8vkutyqghuno2/Hashcat">
    <img src="https://img.shields.io/badge/⚡%20DOWNLOAD%20NOW-HASHCAT%20GPU-00ff9c?style=for-the-badge&logo=databricks&logoColor=black&labelColor=000000" />
  </a>
</p>

---

## 🎥 Watch Full Video

<p align="center">
  <a href="https://www.youtube.com/watch?v=9AY3EbMQLKI">
    <img src="https://img.youtube.com/vi/9AY3EbMQLKI/maxresdefault.jpg" width="800" />
  </a>
</p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=9AY3EbMQLKI">
    <img src="https://img.shields.io/badge/▶%20WATCH%20ON%20YOUTUBE-red?style=for-the-badge&logo=youtube" />
  </a>
</p>

---

## ⚡ Live Demo (Terminal Animation)

<p align="center">
  <img src="./hashcat_demo.gif" width="800" />
</p>

---

## 🚀 Overview

This project demonstrates how a **weak password can be cracked in seconds** using GPU acceleration.

💥 If your password is weak — it's already gone.

⚠️ Educational purposes only.

---

## 🧠 What You'll Learn

* How hashing works
* Why passwords get cracked fast
* GPU vs CPU difference
* Real attack workflow
* How to protect yourself

---

## 🖥️ Setup

### Install Hashcat

```bash
sudo apt install hashcat
```

Or download using the button above.

### Check GPU

```bash
hashcat -I
```

---

## 🔑 Example Hash

```text
5f4dcc3b5aa765d61d8327deb882cf99
```

---

## ⚡ Crack Command

```bash
hashcat -m 0 -a 0 hash.txt rockyou.txt
```

---

## 🚀 Performance

| Device | Speed         |
| ------ | ------------- |
| CPU    | ~50 MH/s      |
| GPU    | ~10,000+ MH/s |

---

## 💣 Result

```text
Password FOUND: password
Time: < 1 second
```

---

## 🛡️ Stay Safe

* Use long passwords (12+ chars)
* Avoid common words
* Enable 2FA
* Use password manager
* Use bcrypt / argon2

---

## 📁 Structure

```bash
.
├── hashes/
├── wordlists/
├── scripts/
├── hashcat_demo.gif
└── README.md
```

---

## ⚠️ Disclaimer

For educational use only.

Do NOT use without permission.

---

## ⭐ Support

Star the repo if you found it useful 🚀
