

---

# Caesar Cipher Implementation

This repository contains a Python script that implements the Caesar Cipher, a simple and well-known encryption technique. The script allows users to encrypt or decrypt messages using a specified shift value.

## Features

- Encrypt messages using the Caesar Cipher
- Decrypt messages using the Caesar Cipher
- Analyze messages to check for correctness
- Input messages and shift values securely using `getpass` to hide input

## Usage

### Running the Script

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/Caesar-Cipher-Implementation.git
   ```
2. **Navigate to the Project Directory:**
   ```sh
   cd Caesar-Cipher-Implementation
   ```
3. **Run the Script:**
   ```sh
   python Caesar-Cipher-Implementation.py
   ```

### Example Usage

When you run the script, you will be prompted to choose whether you want to encrypt or decrypt a message. You will also need to provide the message and the shift value.

1. **Choose Action:**
   ```plaintext
   Do you want to encrypt or decrypt a message? Input 'e' for encryption, 'd' for decryption, or 'q' to quit: e
   ```

2. **Enter the Message (Input will be hidden):**
   ```plaintext
   Enter the message (invisible, type carefully):
   ```

3. **Analyze the Message:**
   ```plaintext
   Please check whether the message you provided was correct or not using the following hints:

   First and last characters of the message: H***o
   Total number of characters entered: 11
   Number of alphabetical letters: 8
   Number of digits: 2
   Number of special characters: 1
   Special characters are present in the message.
   ```

4. **Enter the Shift Value (Input will be hidden):**
   ```plaintext
   Enter the shift value (invisible, type carefully):
   ```

5. **View the Encrypted/Decrypted Message:**
   ```plaintext
   Encrypted Message: Khoor Zruog
   ```

### Exiting the Script

To exit the script, you can input `q` when prompted to choose an action.

```plaintext
Do you want to encrypt or decrypt a message? Input 'e' for encryption, 'd' for decryption, or 'q' to quit: q
Exiting the program. Goodbye!
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

These projects were developed as part of the Prodigy InfoTech Internship program.

---

