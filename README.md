# QR Code Generator

## Description
This Node.js application generates QR codes from user-input URLs. It uses the `inquirer` package for interactive command-line prompts, `qr-image` for QR code generation, and the native `fs` module for file operations.

## Installation
Ensure Node.js is installed on your system and follow these steps:

1. Clone the repository:
git clone https://github.com/shovo4/QRCode_Project

2. Install dependencies:
npm init -y
npm install inquirer qr-image

## Usage
Run the application with the following command:
node index.js

Follow the prompt to input a URL. The application will generate a QR code image (`qr_img.png`) and save the URL in a text file (`URL.txt`).
for example:
after putting https://shovo.ca it creates these 2 files :
- [View URL Text File](https://github.com/shovo4/QRCode_Project/blob/main/URL.txt)
- ![QR](https://github.com/shovo4/QRCode_Project/blob/main/qr_img.png)

## Features
- Command-line interaction with `inquirer`.
- QR code generation with `qr-image`.
- File operations with `fs`.




