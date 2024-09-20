# Java Cryptography Application

This project is a Java-based cryptography application that implements three classic cipher algorithms: Vigenère, Playfair, and Hill. It provides a graphical user interface for encrypting and decrypting messages using these algorithms.

## Features

- Graphical User Interface (GUI) built with Java Swing
- Implementation of Vigenère, Playfair, and Hill ciphers
- Encryption and decryption functionality
- File upload support for .txt files
- Input validation for key length

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Java IDE (e.g., IntelliJ IDEA, Eclipse) or command-line compiler

### Running the Application

1. Clone this repository to your local machine.
2. Open the project in your Java IDE or navigate to the project directory in your terminal.
3. Compile and run the `CipherAppSwing` class in the `Main.java` file.

## Usage

1. Launch the application.
2. Enter your message in the "Pesan" field or use the "Unggah .txt File" button to load text from a file.
3. Enter a key (minimum 12 characters) in the "Kunci" field.
4. Select the desired cipher algorithm from the dropdown menu.
5. Click "Encrypt" to encrypt your message or "Decrypt" to decrypt a message.
6. The result will appear in the text area at the bottom of the window.

## Implemented Ciphers

### Vigenère Cipher

A polyalphabetic substitution cipher that uses a keyword to encrypt the plaintext.

### Playfair Cipher

A digraph substitution cipher that encrypts pairs of letters.

### Hill Cipher

A polygraphic substitution cipher based on linear algebra, using a key matrix to encrypt blocks of letters.

## Project Structure

- `Main.java`: Contains the `CipherAppSwing` class, which implements the GUI and main application logic.
- `CipherUtils.java`: Implements the encryption and decryption algorithms for all three ciphers.

## Contributing

Contributions to improve the project are welcome. Please feel free to fork the repository and submit pull requests.
