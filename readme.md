# 🗳️ Online Voting System with Homomorphic Encryption

An advanced and privacy-preserving Online Voting System developed using the Paillier Cryptosystem, a form of Homomorphic Encryption. The project aims to simulate a real-world digital voting process where vote integrity, anonymity, and security are crucial.

Built with Python (Flask), this project allows voters to register, vote securely, and ensures the admin can tally results without decrypting individual votes—a key property of homomorphic encryption.
---

## 🔐 Key Features

✅ Paillier Homomorphic Encryption: Votes are encrypted before being stored, and only aggregated encrypted values are decrypted to reveal final results.
🔐 End-to-End Security: Every step from registration to result display respects data integrity and privacy.
👥 User Roles: Separate login flows and panels for voters and admins.
💻 User-Friendly Interface: Clean UI built with HTML, CSS, and Flask.
📊 Live Result Panel: Admin sees tally updates in encrypted form until decryption.
🔏 Authentication & Authorization: Basic login and session management.
📁 Screenshot Uploads: Voting confirmation and user dashboard screenshots.
🧩 SQLite Database: Lightweight and quick local data management.

---

## 🖥️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python (Flask), SQLite
- **Encryption**: Paillier Cryptosystem (Custom Python Implementation)
- **Database**: SQLite
- **Libraries**: Flask, Cryptography, PyCryptodome

---

## 📸 Screenshots

### 🔐 Login Page
<img src="uploads/Screenshot_login.png" width="600"/>

### 🧑‍💼 Admin Panel
<img src="uploads/Screenshot_admin.png" width="600"/>

### 📈 Result Panel (Decryption View)
<img src="uploads/Screenshot_result.png" width="600"/>

### 🧾 Vote Confirmation Preview
<img src="uploads/IMG_vote_preview.jpg" width="600"/>

---


