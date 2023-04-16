# python-substitution_cipher.py
A simple python program for Encryption and Decryption of a text message

<h2>Substitution Cipher Encryption and Decryption Program</h2>
                                                      
This program uses a simple substitution cipher to encrypt and decrypt messages provided by the user. The program generates a random key by shuffling a list of characters that includes punctuation marks, digits, and letters.


***Getting Started***
1. Clone the repository or download the source code files.
2. Ensure that you have Python 3 installed on your computer.
3. Open a command prompt or terminal window in the directory where the program files are located.
4. Run the program by typing python substitution_cipher.py and pressing enter.


***How to Use the Program***
1. The program will display the chars and key lists that it generates at startup.
2. The program will prompt the user to choose whether to encrypt or decrypt a message.
3. If the user chooses to encrypt a message, they will be prompted to enter the message they want to encrypt.
4. The program will display the original message and the encrypted message.
5. If the user chooses to decrypt a message, they will be prompted to enter the message they want to decrypt.
6. The program will display the encrypted message and the decrypted message.
7. The program will prompt the user to choose whether to encrypt/decrypt another message or exit the program.


***Program Structure***

The substitution_cipher.py file contains the main program code. It defines two functions:

->encrypt(message, chars, key): Encrypts a message using the substitution cipher.

->decrypt(cipher_text, chars, key): Decrypts a message using the substitution cipher.

The main() function is the entry point for the program. It generates the chars and key lists, prompts the user for input, and calls the encrypt() or decrypt() function depending on the user's choice. The main() function also handles user input validation and looping.


***Limitations***

This program is a basic implementation of the substitution cipher and is not intended for use in sensitive or high-security applications. The program only handles ASCII characters and does not support Unicode or other character encodings. The program does not provide any key management or storage features.
