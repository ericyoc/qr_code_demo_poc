# QR Code Generator and Modifier

This Python code demonstrates how to generate, modify, and read QR codes using the `qrcode` and `pyzbar` libraries. QR codes (Quick Response codes) are two-dimensional barcodes that can store various types of information, such as text, URLs, contact information, and more. They are widely used for quick and easy data sharing, product tracking, marketing campaigns, and various other applications.

## Features

- Generate QR codes with custom data (up to 40 characters)
- Generate QR codes with a custom logo image
- Change the color scheme of the QR code
- Apply a random pattern to the QR code
- Apply a random gradient to the QR code
- Read and decode QR codes from image files

## Requirements

- Python 3.x
- qrcode library
- pyzbar library
- Pillow (PIL) library
- matplotlib library

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/qr-code-generator.git
   ```

2. Install the required libraries:
   ```
   pip install qrcode pyzbar pillow matplotlib
   ```

## Usage

1. Run the Python script:
   ```
   python qr_code_generator.py
   ```

2. Follow the menu options to generate, modify, and read QR codes:
   - Option 1: Generate a QR code with custom data (up to 40 characters)
   - Option 2: Generate a QR code with a custom logo image
   - Option 3: Change the color scheme of the QR code
   - Option 4: Apply a random pattern to the QR code
   - Option 5: Apply a random gradient to the QR code
   - Option 6: Read and decode a QR code from an image file
   - Option 7: Quit the program

3. The generated QR codes will be saved as "qr_code.jpg" in the same directory as the script.

## QR Code Modifications

The code demonstrates different ways to modify QR codes:

- **Custom Logo**: You can generate a QR code with a custom logo image by providing the path to the logo image file. The logo will be resized and placed at the center of the QR code.

- **Color Scheme**: You can change the color scheme of the QR code by selecting from predefined options (red and white, blue and white, yellow and black) or by specifying custom fill and background colors.

- **Random Pattern**: You can apply a random pattern to the QR code, which adds random lines and shapes to the code for a unique visual effect.

- **Random Gradient**: You can apply a random gradient to the QR code, creating a smooth color transition from one random color to another.

These modifications allow you to customize the appearance of the QR code while maintaining its functionality and readability.

## Disclaimer

This repository is for educational and research purposes only. The code provided is a demonstration of QR code generation and modification techniques and should be used responsibly. The authors and contributors of this repository are not responsible for any misuse or illegal activities performed using this code. Please ensure that you comply with all applicable laws and regulations when using QR codes.
