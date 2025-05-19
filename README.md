# 🔐 OTP Verification System in Python

## 📌 Project Overview

This project implements a **One-Time Password (OTP) Verification System** using Python. The system generates a 6-digit OTP, simulates sending it to the user’s email, and validates the entered OTP. It includes robust error handling and user prompts, with optional support for retry attempts and a GUI interface.

---

## 🧩 Problem Statement

Develop a secure OTP verification system that:

- Generates a random 6-digit OTP
- Sends the OTP to a user (simulated)
- Prompts the user to enter the OTP
- Validates the OTP and grants or denies access
- Handles errors and allows retry attempts

---

## ✅ Features

- Random 6-digit OTP generation  
- Simulated OTP email delivery  
- User-friendly input prompt and validation  
- Access granted/denied based on OTP match  
- Retry attempts on incorrect input  
- Clear error messages and edge case handling  
- *(Optional)* Simple GUI interface using `tkinter`  

---

## ⚙️ How It Works

1. **OTP Generation:** A secure 6-digit OTP is created using Python’s `random` module.
2. **Simulated Email Sending:** The OTP is displayed as a simulated email for testing.
3. **User Input:** The user is prompted to enter the OTP.
4. **Verification:** The system checks whether the entered OTP matches the generated one.
5. **Access Decision:** Access is granted or denied based on the match.
6. **Retry Option:** The user can retry if the OTP is incorrect.

---


