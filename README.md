# QR Code Generator

 This project is a simple QR code generator built with Node.js. It utilizes the inquirer package for command-line prompts, the qr-image package to generate the QR code, and a native Node.js module for file handling.

## Features:
* **Interactive CLI:** Uses inquirer to prompt the user for input. ```npm package```
* **QR Code Generation:** Generates QR codes from user input using qr-image. ```npm package```
* **File Handling:** Saves the generated QR code as a PNG file using a ```native Node.js module```

## Prerequisites:

* Node.js (v12 or higher)
* npm (v6 or higher)


## Usage: 

1. Run the application:

```
node index.js
```

2. Follow the prompts to input the data you want to encode in the QR code.
3. The generated QR code will be saved as a PNG file in the project directory.

## Dependencies:

* **inquirer:** A collection of common interactive command-line user interfaces.
* **qr-image:** A simple QR code generator for Node.js.
* **Native Node.js modules:** Used for file handling.


## Example:
After running the application and providing input, you will find a file named ```qr_image.png``` in your project directory.
