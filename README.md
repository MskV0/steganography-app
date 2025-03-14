# Steganography App

## Overview

The Steganography App allows users to hide secret messages within images using a technique called steganography. This application provides a simple and user-friendly interface for encrypting and decrypting messages.

## Features

- **Encrypt Messages**: Hide a secret message within an image.
- **Decrypt Messages**: Retrieve the hidden message from an encrypted image.
- **User -Friendly Interface**: Easy to navigate and use.
- **Supports Multiple Image Formats**: Works with JPG, PNG, and BMP images.

## Requirements

- Windows operating system
- Python 3.x (if running the script directly)
- Required libraries: `cv2`, `tkinter`, `PIL` (Pillow)

## Installation

1. **Download the Executable**: Obtain the `steganography.exe` file from the provided source.
2. **Run the Application**: Double-click on the `steganography.exe` file to launch the application.

## Usage

### Encrypting a Message

1. **Select an Image**: Click on the "Browse" button to choose an image file (JPG, PNG, or BMP) where you want to hide the message.
2. **Enter the Secret Message**: Type the message you want to hide in the "Secret Message" field.
3. **Enter a Passcode**: Provide a passcode that will be required for decryption.
4. **Encrypt**: Click the "Encrypt" button. The application will save the encrypted image as `encryptedImage.png` in the same directory.

### Decrypting a Message

1. **Select the Encrypted Image**: Click on the "Browse" button to choose the encrypted image file.
2. **Enter the Passcode**: Type the passcode you used during encryption.
3. **Decrypt**: Click the "Decrypt" button. The application will display the hidden message in a pop-up window.

## Important Notes

- **Passcode**: Make sure to remember the passcode you used for encryption, as it is required for decryption.
- **Message Length**: The message must be short enough to fit within the image. If the message is too long, an error will be displayed.
- **Image Quality**: For best results, use images that are not heavily compressed, as this can affect the ability to retrieve the hidden message.

## Troubleshooting

- **Image Not Found**: Ensure that the image file path is correct and that the file exists.
- **Incorrect Passcode**: Double-check the passcode entered during decryption. It must match the one used during encryption.
- **Message Too Long**: If you receive an error stating that the message is too long, try using a shorter message.

## Future Enhancements

- Support for additional image formats.
- Improved security features for message encryption.
- User preferences for default save locations and settings.

## Contact

For any questions or feedback, please contact [ms9989] at [victorystarts640@gmail.com].
