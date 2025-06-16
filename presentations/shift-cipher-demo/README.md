# Understanding and Breaking Shift Ciphers (Caesar Cipher)

📅 **Date:** May 3, 2025  
🎓 **Course:** CSIA 440 – Secure Software Development  
🎥 **Presentation Link:** [Watch on YouTube (Unlisted)](https://www.youtube.com/watch?v=f23vYx7cqss&list=PLRX0EcV0YK7poUuMPa5CTAkxD_I7qLKIv&index=8)

## 🧠 Overview

This presentation introduces the fundamentals of **shift ciphers**, with a focus on the **Caesar Cipher**, one of the oldest and simplest encryption techniques. It also includes a live demo of a custom-built **Google Sheets tool** designed to break Caesar-encrypted messages using brute-force.

## 🔑 Key Topics Covered

- **What is a Shift Cipher?**  
  Substitution cipher that shifts each letter by a fixed number of positions (mod 26).  
  Example: `HELLO` with a shift of 3 becomes `KHOOR`.

- **How It Works**  
  - Encryption: `E(x) = (x + n) mod 26`  
  - Decryption: `D(x) = (x - n) mod 26`

- **Why It’s Insecure**  
  - Only 25 possible shift keys  
  - Easy to brute-force  
  - No frequency obfuscation or key management  

- **What is a Caesar Cipher?**  
  A specific shift cipher with a fixed key of 3, famously used by Julius Caesar for military communications.

- **Live Cipher Tool Demo**  
  - Spreadsheet tool automates brute-force decryption  
  - Shows all 25 possible shifts  
  - Input: `KHOOR` → Output: `HELLO` at Shift 3

## ✅ Takeaways

Caesar Ciphers are foundational in understanding cryptography but are easily breakable. They serve as a learning tool rather than a secure method in modern applications. This presentation illustrates their structure and vulnerabilities with a practical demo.

## 🛠 Tool Download

Download the Caesar Cipher brute-force tool demonstrated in the video:

📄 [`Cipher Tool CSIA 440.xlsx`](./Cipher%20Tool%20CSIA%20440.xlsx)

---

**Created by:** Sam Mendez  
**Format:** Video presentation with interactive slide deck and custom-built decryption tool  
