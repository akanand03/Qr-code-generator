# QR Code Generator in Python

## Overview

This Python script generates QR codes for input data using the `qrcode` library. QR codes are widely used for encoding various types of data, such as URLs, plain text, or contact information.

## Features

- Generate QR codes for text data
- Save QR codes as image files (PNG format)

## Requirements

- Python 3.x
- `qrcode` library

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/qr-code-generator.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script with the desired data:

    ```bash
    python qr_code_generator.py --data "Your Data Here"
    ```

2. The script will generate a QR code and save it as a PNG file in the `output` directory.

## Command Line Options

- `--data`: The data to be encoded in the QR code.
- `--output`: The output directory for saving the generated QR code image.

```bash
python qr_code_generator.py --data "Hello, World!" --output output_directory
