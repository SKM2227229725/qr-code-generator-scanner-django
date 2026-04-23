# QR Code Generator & Scanner (Django)

A Django-based web application that allows users to generate QR codes from text or URLs and scan/decode QR codes easily.

---

## 🚀 Features

- Generate QR codes from text, links, or custom input  
- Scan and decode QR codes  
- Clean and modular Django project structure  
- Separate apps for better scalability  
- Beginner-friendly project  

---
## 📸 Screenshots

> Add screenshots of your application here (QR generation page, scanner page, result output).

Example:
- QR Code Generation UI
- QR Scanner Result Outpu

----
## 🛠️ Tech Stack

- Python  
- Django  
- HTML, CSS, JavaScript   and  talwind css
- Libraries:
  - qrcode
  - pyzbar
  - Pillow
  - OpenCV (optional for advanced scanning)

---

## 📂 Project Structure
djangoqr/
│
├── core/ # QR code generation
├── scanner/ # QR code scanning
├── djangoqr/ # Project settings
├── manage.py
└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
git clone https://github.com/SKM2227229725/qr-code-generator-scanner-django.git

cd qr-code-generator-scanner-django

---

### 2️⃣ Create virtual environment
python -m venv venv
venv\Scripts\activate
---

### 3️⃣ Install dependencies


pip install django
pip install qrcode
pip install pillow
pip install pyzbar
pip install opencv-python


---

### 4️⃣ Run the server


python manage.py runserver


---

## ⚠️ Important (Windows Users)

For QR scanning, install **ZBAR library**:

1. Download ZBAR  
2. Add this path to Environment Variables:


C:\Program Files (x86)\ZBar\bin


---

## 📌 About

This project demonstrates how to build a real-world Django application with QR code generation and scanning functionality using external libraries.

---

## 👨‍💻 Author

Shailesh Kumar  
GitHub: https://github.com/SKM2227229725
