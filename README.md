<p align="center">
  <img src="https://raw.githubusercontent.com/habanada/CryptoBadger/refs/heads/main/CryptoBadger.png" alt="CryptoBadger Logo" width="300">
</p>
#  CryptoBadger

**Version:** 1.0 (Crypto) 
**Author:** [Selahattin Erkoc](https://github.com/habanada) 
**License:** [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) 
**Year:** 2025 

---

##  Overview

**CryptoBadger** is a browser-based text encryption tool for **securely encrypting and decrypting messages** directly on your device. 
It supports modern cryptographic algorithms such as **AES-GCM** and **ChaCha20-Poly1305**, plus a simple **XOR mode** for demonstration purposes. 

Built with a focus on:
- Modern **Web Crypto API** encryption
- **User-friendly UI** with Dark/Light mode
- **Multilingual support (EN/DE)**
- Fully **offline operation** - no data ever leaves your browser

---

##  Features

- ️ **AES-GCM** with selectable key sizes (128 / 192 / 256 bit) 
-  **ChaCha20-Poly1305** for high-security modern encryption 
-  **XOR mode** (educational, not secure) 
-  **Dark/Light theme** with automatic system detection 
- ️ **Languages:** English 🇬🇧 & German 🇩🇪 
-  **Copy button** for easy export 
-  100% **client-side encryption**

---

##  How It Works

All encryption and decryption happen **entirely in the browser** - 
no data or passwords are transmitted to any server. 

Keys are derived using **PBKDF2 (SHA-256, 100,000 iterations)** for strong password-based encryption.

### Output Format

| Algorithm | Format |
|------------|--------|
| AES-GCM | `AES1:[KeySize]:[Salt_b64]:[IV_b64]:[Data_b64]` |
| ChaCha20-Poly1305 | `CHACHA1:[Salt_b64]:[IV_b64]:[Data_b64]` |
| XOR (unsafe) | `XOR1:[Data]` |

---

## ️ Installation & Usage

###  Local Usage
1. Download the file **`CryptoBadger.html`**. 
2. Open it directly in your browser (double-click). 
3. No installation or server required.

###  Hosting on GitHub Pages
To make CryptoBadger available online:

```bash
git clone https://github.com/habanada/cryptobadger.git
cd cryptobadger
````

Then go to your **GitHub Repository → Settings → Pages → Source → main / root** and enable it.

Your live tool will be available at:

```
https://<username>.github.io/cryptobadger/
```

---

##  Technical Details

| Component | Technology |
| ------------ | ---------------------------------------------- |
| Frontend | HTML5, TailwindCSS, JavaScript (ES6+) |
| Crypto API | Web Crypto API |
| Localization | English / German |
| Frameworks | None |
| Storage | LocalStorage (for theme and language settings) |

---

## ️ Security Notice

* The **XOR encryption mode is NOT secure** - for demonstration only.
* For real-world use, always choose **AES-GCM** or **ChaCha20-Poly1305**.
* The author assumes **no liability** for data loss or misuse.

---

##  License

This project is licensed under the
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**

️ You are free to:

* Use, share, and modify this software
* **For non-commercial purposes only**

️ You must:

* Give attribution:
 **"CryptoBadger by Selahattin Erkoc"**
 (based on *Base64Badger UI*)

️ Commercial use requires **explicit permission** from the author.

---

##  Contact

**Selahattin Erkoc**
GitHub: [@habanada](https://github.com/habanada)
For license requests or feedback, please use GitHub Issues.

---

###  CryptoBadger - Secure your words.


