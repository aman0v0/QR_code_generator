# QR_code_generator
This project generates a QR code for a given URL using the Python qrcode library. The QR code can be used to easily share links by scanning it with a smartphone.
# QR Code Generator

## Overview
This project generates a QR code for a given URL using the Python `qrcode` library. The QR code can be used to easily share links by scanning it with a smartphone.

## Features
- Generates a QR code from a provided URL or text.
- Customizable QR code properties such as version, box size, and border.
- Saves the generated QR code as an image file (`test.png`).

## Requirements
To run this project, you need to have Python installed along with the following dependencies:

```
pip install qrcode[pil]
pip install image
```

## Installation & Usage
1. Clone or download this repository.
2. Install dependencies using the command above.
3. Run the Python script to generate the QR code:

```
python qr_generator.py
```

4. The generated QR code will be saved as `test.png` in the project directory.

## Code Explanation

- **`qrcode.QRCode`**: Creates a QR code object with defined parameters.
- **`add_data(data)`**: Adds the given data (URL) to the QR code.
- **`make(fit=True)`**: Optimizes the QR code size.
- **`make_image(fill, back_color)`**: Generates the QR code image.
- **`img.save("test.png")`**: Saves the image file.

## Output
After running the script, a QR code image named `test.png` will be created. This QR code, when scanned, will redirect to the given URL.

## License
This project is open-source and free to use.

## Author
**Mohammed Aman**

