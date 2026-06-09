# QR Generator

A simple Node.js application that generates QR codes from URLs and saves them as PNG images. The application provides a command-line interface for converting website URLs into scannable QR codes.

## Features

* Generate QR codes from URLs
* Save QR codes as PNG images
* Store the input URL in a text file
* Simple command-line interface
* Lightweight and beginner-friendly

## Technologies Used

* Node.js
* Inquirer
* qr-image
* File System (fs) Module

## Project Structure

```
QR-Generator
│
├── index.js
├── package.json
├── package-lock.json
├── qr_img.png
├── URL.txt
├── README.md
└── .gitignore
```

## Installation

Clone the repository:

```bash
git clone https://github.com/anushachinthakayala0064/QR-Generator.git
```

Navigate to the project directory:

```bash
cd QR-Generator
```

Install dependencies:

```bash
npm install
```

## Usage

Run the application:

```bash
node index.js
```

Enter a URL when prompted:

```
https://www.google.com
```

The application generates:

* `qr_img.png` – QR code image
* `URL.txt` – stores the entered URL

## Future Enhancements

* Add URL validation
* Support custom QR code colors
* Export QR codes in multiple formats
* Develop a web-based interface

GitHub: https://github.com/anushachinthakayala0064/QR-Generator.git
