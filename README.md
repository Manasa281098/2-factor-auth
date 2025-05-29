# 🔐 Two-Factor Authentication (2FA) with Python and Twilio

This Python project implements a simple **Two-Factor Authentication (2FA)** mechanism using:

1. Password authentication
2. One-Time Password (OTP) sent via **SMS** using the Twilio API

It’s ideal for learning purposes or as a lightweight security layer in internal tools.

---

## 📦 Features

- 🔐 Password-based login
- 🔁 Limited number of login attempts
- 🔢 Secure 6-digit OTP generation using Python's `secrets` module
- 📲 OTP sent to the user’s phone via Twilio SMS API
- 🛡️ Basic error handling and lockout mechanism

---

## 📋 Prerequisites

Ensure you have the following:

- Python 3.7 or higher
- A [Twilio](https://www.twilio.com/) account with:
  - Account SID
  - Auth Token
  - Verified phone numbers (both sender and recipient)
- Internet connection (for Twilio API)

---
