# secure-totp-login
🔐 Secure TOTP Login – A simple, front-end-only 2FA system using 🕒 TOTP and 📱 QR codes. Register with a username, scan the QR with Google Authenticator, and log in securely – all in your browser! ⚡
# 🔐 Secure TOTP Login (HTML + JavaScript + LocalStorage)

This project demonstrates a simple, front-end-only implementation of **Two-Factor Authentication (2FA)** using **Time-based One-Time Passwords (TOTP)**. It uses JavaScript libraries like [`otplib`](https://github.com/yeojz/otplib) for TOTP generation/validation and [`qrcodejs`](https://github.com/davidshimjs/qrcodejs) to generate a QR code for Google Authenticator scanning.

> ⚠️ This project uses **localStorage** to store user data, and is meant for **educational/demonstration purposes only**. Do not use this in production environments.

---

## 🧰 Features

- 🔐 TOTP-based authentication (RFC 6238 compliant)
- 📱 QR code generation for scanning with Google Authenticator or Authy
- 🛠 No server or backend – everything runs in the browser
- 🗃 User data saved locally in browser `localStorage`
- ✨ Clean and responsive UI with basic CSS

---

## 📸 Screenshots

| Register & Scan QR | Enter OTP to Login | Welcome |
|--------------------|--------------------|---------|
| ![QR Example](https://i.imgur.com/9NmnN6Z.png) | ![OTP Login](https://i.imgur.com/n6hMfuH.png) | ![Welcome](https://i.imgur.com/gMbb8Ag.png) |

---

## 🚀 How to Run

1. Clone or download the repository:
   ```bash
   git clone https://github.com/your-username/secure-totp-login.git
   cd secure-totp-login

