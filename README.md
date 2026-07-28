# QR Code Generator

A simple Python script that generates a QR code from any URL and saves it as a PNG image.

## Features

- Takes a URL as input from the user
- Generates a QR code using the `qrcode` library
- Saves the QR code as a PNG image file

## Requirements

- Python 3.x
- `qrcode` library
- `Pillow` (installed automatically as a dependency of `qrcode`)

Install the dependency with:

```bash
pip install qrcode[pil]
```

## Usage

1. Run the script:

```bash
python qr_generator.py
```

2. Enter a URL when prompted.
3. The QR code image will be saved to the specified file path.
4. Open the saved PNG to view and scan your QR code.

## Example

```
Enter the URL: https://github.com
Your QR CODE Is Generated
```

## Future Improvements

- Make the save location dynamic (currently hardcoded to a specific path) so it works on any machine, e.g. save to the same folder as the script using a relative path
- Let the user choose the file name and save location
- Add input validation to check if the entered text is a valid URL
- Support generating QR codes for other data types (Wi-Fi credentials, contact info, plain text)
- Add a simple GUI or web interface (e.g. with Flask or Streamlit)

## License

This project is open source and available under the [MIT License](LICENSE).
