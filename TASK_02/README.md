

---

# Image Encryption Tool

This repository contains a Python script that provides an image encryption and decryption tool using a specified key. The script utilizes the PIL library to handle image processing and NumPy for mathematical operations on image arrays.

## Features

- Encrypt images using a specified key
- Decrypt images using the same key
- Handles both local image files
- Ensures the encrypted and decrypted images are saved properly

## Prerequisites

- Python 3.x
- Required Python packages:
  - PIL (Pillow)
  - NumPy

### Installing Required Packages

You can install the required packages using pip:

```sh
pip install pillow numpy
```

## Usage

### Running the Script

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/Image-Encryption-Tool.git
   ```
2. **Navigate to the Project Directory:**
   ```sh
   cd Image-Encryption-Tool
   ```
3. **Run the Script:**
   ```sh
   python image_encryption_tool.py
   ```

### Example Usage

When you run the script, you will be prompted to choose whether you want to encrypt or decrypt an image. You will also need to provide the image location and the key.

1. **Choose Action:**
   ```plaintext
   Select an option:
   E - Encrypt image
   D - Decrypt image
   Q - Quit
   Your choice: E
   ```

2. **Enter the Encryption Key:**
   ```plaintext
   Enter encryption key: 1234
   ```

3. **Enter the Image Location:**
   ```plaintext
   Enter the location or URL of the image: path/to/your/image.png
   ```

4. **View the Encrypted Image:**
   ```plaintext
   Image encrypted successfully. Encrypted image saved at: encrypted_image.png
   ```

5. **Choose Action:**
   ```plaintext
   Select an option:
   E - Encrypt image
   D - Decrypt image
   Q - Quit
   Your choice: D
   ```

6. **Enter the Decryption Key:**
   ```plaintext
   Enter decryption key: 1234
   ```

7. **Enter the Encrypted Image Location:**
   ```plaintext
   Enter the location of the encrypted image: path/to/encrypted_image.png
   ```

8. **View the Decrypted Image:**
   ```plaintext
   Image decrypted successfully. Decrypted image saved at: decrypted_image.png
   ```

### Exiting the Script

To exit the script, you can input `Q` when prompted to choose an action.

```plaintext
Select an option:
E - Encrypt image
D - Decrypt image
Q - Quit
Your choice: Q
Exiting the program.
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

These projects were developed as part of the Prodigy InfoTech Internship program.

---


