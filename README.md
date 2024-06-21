#QR Code Generator
This project is a simple command-line application that generates QR codes from user-provided URLs. The application prompts the user to enter a URL, converts the URL into a QR code image, and saves both the QR code and the URL to files. It leverages the inquirer package for user input, the qr-image package for QR code generation, and the native fs module for file operations.

Features:-
User Input Prompt: Uses the inquirer package to prompt the user for a URL.
QR Code Generation: Converts the entered URL into a QR code image using the qr-image package.
File Creation: Saves the generated QR code as an image file (qr_img.png) and stores the URL in a text file (URL.txt).
Error Handling: Handles potential errors during file creation and user input prompts.
Easy to Use: Provides a simple command-line interface for quick QR code generation.

Installation

Clone the repository:
git clone https://github.com/yourusername/qr-code-generator.git
cd qr-code-generator
Install the dependencies:
npm install
Usage
Run the application:
node index.js
Follow the prompt to enter the URL you want to convert into a QR code.

Example
Type in your URL: https://example.com
The file has been saved!
This will generate a QR code image file (qr_img.png) and a text file (URL.txt) containing the URL.

Dependencies:-
inquirer
qr-image
fs (File System)

License
This project is licensed under the MIT License. See the LICENSE file for details.
