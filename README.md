# QR Code Generator and Scanner Django Project

A Django-based web application that allows users to **generate** QR codes from text or URLs and **scan/decode** QR codes easily.  
This project is built with Django and organized using two apps:

- **core** – main app for project logic and QR code generation
- **scanner** – handles QR code scanning/decoding functionality

---

## Features

- Generate QR codes from text, links, or custom input
- Scan and decode QR codes
- Clean Django project structure
- Separate apps for better modularity
- Beginner-friendly project for learning Django

---

## Project Structure

```bash
djangoqr/
│
├── core/          # Main app for QR code generation
├── scanner/       # App for QR code scanning
├── djangoqr/      # Project settings and configuration
├── manage.py
└── README.md
