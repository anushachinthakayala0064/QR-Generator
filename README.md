# 🚀 QR Generator

A Node.js application that converts URLs into QR codes and saves them as PNG images.

## ✨ Features

* Generate QR codes from URLs
* Save QR codes as PNG images
* Store the entered URL in a text file
* Interactive command-line interface

## 🛠️ Technologies Used

* Node.js
* Inquirer
* qr-image
* File System (fs)

## 📦 Installation

```bash
git clone https://github.com/anushachinthakayala0064/QR-Generator.git
cd QR-Generator
npm install
```

## ▶️ Usage

Run the application:

```bash
node index.js
```

Enter a URL when prompted. The application generates:

* `qr_img.png` – QR code image
* `URL.txt` – stores the entered URL

## 📁 Project Structure

```text
QR-Generator
├── index.js
├── package.json
├── package-lock.json
├── qr_img.png
├── URL.txt
├── README.md
└── .gitignore
```

## 🔮 Future Improvements

* Add URL validation
* Support custom QR code colors
* Develop a web interface

---

Built while learning Node.js and npm packages.
