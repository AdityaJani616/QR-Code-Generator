# QR Code Generator

A simple Node.js project to generate QR codes from textual input. This application uses `qr-image` to create QR codes, `inquirer` for interactive user prompts, and `fs` to save the QR code as an image file.

## Features

- Generate QR codes from user-inputted text
- Save generated QR codes as image files
- Interactive command-line interface

## Requirements

- Node.js
- npm (Node Package Manager)

## Installation and Usage

```bash
# Clone the repository and navigate to the project directory
git clone https://github.com/AdityaJani616/QR-Code-Generator.git
cd QR-Code-Generator

# Install the required dependencies
npm install

# Run the application
node index.js

# Follow the on-screen prompts to enter the text you want to encode in the QR code and specify the file name for the output image
