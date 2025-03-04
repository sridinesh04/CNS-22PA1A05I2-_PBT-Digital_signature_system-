# CNS-22PA1A05I2-_PBT-Digital_signature_system-
🔐 Digital Signature System using RSA | Python This project implements a Digital Signature System using RSA cryptography in Python. It allows users to securely sign messages and verify their authenticity using public-private key pairs.
🚀 How It Works
Generate Keys 🔑 → Creates RSA key pairs and stores them in files.
Sign a Message ✍️ → Encrypts the message hash using the private key.
Verify Signature ✅ → Decrypts the signature using the public key and checks authenticity.
📂 File Structure
bash
Copy
Edit
📁 Digital-Signature-System/
│── 🔑 public_key.pem       # Stores Public Key
│── 🔑 private_key.pem      # Stores Private Key
│── 📝 signature.txt        # Stores Digital Signature
│── 🖥️ digital_signature.py # Main Python Script
│── 📄 README.md            # Project Documentation
🛠️ Setup & Installation
🔹 1. Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-username/Digital-Signature-System.git
cd Digital-Signature-System
🔹 2. Install Dependencies
sh
Copy
Edit
pip install rsa
🔹 3. Run the Program
sh
Copy
Edit
python digital_signature.py
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
🖼️ Example Output
mathematica
Copy
Edit
🔹 Welcome to Digital Signature System 🔹

Options:
1️⃣ Sign a Message
2️⃣ Verify a Signature
3️⃣ Exit

Enter your choice (1/2/3): 1

Enter the message to sign: Secure transaction initiated.

✅ Digital Signature Generated and Saved!

🔹 Digital Signature: 5f8d8b0c97...

Options:
1️⃣ Sign a Message
2️⃣ Verify a Signature
3️⃣ Exit

Enter your choice (1/2/3): 2

Enter the original message: Secure transaction initiated.

✅ Signature is VALID! Message is authentic.
📖 Concepts Used
Public Key Cryptography (RSA)
SHA-256 Hashing for Integrity
Digital Signatures for Authentication
File-Based Key Management
Python Error Handling & Security Best Practices
💡 Future Enhancements
🔹 GUI using Tkinter for a better user experience
🔹 Database Storage for managing keys & signatures
🔹 Support for Multiple Signature Algorithms (DSA, ECDSA)

🛡️ Security Considerations
✅ Uses SHA-256 Hashing for strong cryptographic integrity.
✅ Keys are stored securely in .pem files.
✅ Prevents tampering by verifying signature validity.

📜 License
This project is licensed under the MIT License. Feel free to modify and use it.

💙 Contributing
Want to improve this project? Feel free to fork, submit PRs, or suggest features! 🚀

