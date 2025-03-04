# CNS-22PA1A05I2-_PBT-Digital_signature_system-
🔐 Digital Signature System using RSA | Python This project implements a Digital Signature System using RSA cryptography in Python. It allows users to securely sign messages and verify their authenticity using public-private key pairs.
📌 Features
✅ Generate RSA Key Pair (Public & Private Keys)
✅ Save & Load Keys from Files (public_key.pem, private_key.pem)
✅ Digitally Sign Messages (SHA-256 Hashing & RSA Encryption)
✅ Verify Digital Signatures (Ensures Message Integrity & Authenticity)
✅ User-Friendly CLI Interface (Menu-based System)
✅ Handles Errors Gracefully (File Not Found, Invalid Signature, etc.)


🚀 How It Works
Generate Keys 🔑 → Creates RSA key pairs and stores them in files.
Sign a Message ✍️ → Encrypts the message hash using the private key.
Verify Signature ✅ → Decrypts the signature using the public key and checks authenticity.

📁 Digital-Signature-System/
│── 🔑 public_key.pem       # Stores Public Key
│── 🔑 private_key.pem      # Stores Private Key
│── 📝 signature.txt        # Stores Digital Signature
│── 🖥️ digital_signature.py # Main Python Script
│── 📄 README.md            # Project Documentation

📜 Usage
🔹 Generating RSA Keys
The program automatically generates and saves the keys when first executed.

🔹 Signing a Message
Choose "1️⃣ Sign a Message"
Enter a message (e.g., "Hello, Secure World!")
The program generates a digital signature and saves it.
🔹 Verifying a Signature
Choose "2️⃣ Verify a Signature"
Enter the original message.
The program checks if the signature is valid.

![Screenshot 2025-03-04 191716](https://github.com/user-attachments/assets/bab38c02-f545-4555-8ed1-feb21f95b5d5)
![Screenshot 2025-03-04 192001](https://github.com/user-attachments/assets/4e0f58c3-e051-4743-8165-381cba847a32)



