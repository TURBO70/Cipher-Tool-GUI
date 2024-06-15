<h2>🧐 Features</h2>

Here're some of the project's best features:

* User-Friendly Interface: The application features a clean, light blue-themed interface with clear labels and inputs for ease of use.
  
* Multiple Cipher Support: Supports a wide range of ciphers including:
  
* Playfair
* Caesar
* Monoalphabetic
* Polyalphabetic
* Vigenère
* Rail Fence
* Row Transposition
* DES (Data Encryption Standard)
* AES (Advanced Encryption Standard)
  
* Dual Mode Operations: Allows users to choose between encryption and decryption modes for each cipher.
  
* Input Handling: Provides text input areas for plaintext and key, ensuring users can easily enter the data required for processing.
  
* Result Display: Shows the result of the encryption or decryption operation directly within the application.
  
* Error Handling: Includes error handling mechanisms to display appropriate error messages for invalid inputs or processing errors.
  
* Clear Functionality: Offers a button to clear all inputs, making it convenient to reset the form for new operations.
  
* GUI Components: Utilizes tkinter and ttk widgets for creating labels, text areas, buttons, and combo boxes.
  





## 🛠️ Cipher Implementations:

* Playfair Cipher: Implements character pairing and key table generation for both encryption and decryption.
* Caesar Cipher: Shifts characters based on a numeric key for simple substitution.
* Monoalphabetic Cipher: Uses a substitution key for character mapping.
* Polyalphabetic Cipher: Encrypts using a series of different Caesar ciphers based on a repeating key.
* Vigenère Cipher: Implements a polyalphabetic cipher using a keyword.
* Rail Fence Cipher: Transposes characters along a rail fence pattern.
* Row Transposition Cipher: Rearranges characters based on a numeric key.
* DES and AES: Utilizes external libraries (pyDes for DES and Crypto.Cipher for AES) to perform block cipher operations with appropriate padding and encoding.





## Usage
* Select Cipher: Choose the desired cipher from the dropdown menu.
* Choose Mode: Select either "Encrypt" or "Decrypt" mode.
* Enter Text: Input the plaintext or ciphertext in the provided text area.
* Enter Key: Input the key required for the selected cipher.
* Process: Click the "Process" button to execute the encryption or decryption operation.
* View Result: The result is displayed on the interface.
* Clear Inputs: Use the "Clear Inputs" button to reset all fields.
* Dependencies
* tkinter: For creating the graphical user interface.
* pyDes: For DES encryption and decryption.
* Crypto.Cipher: From the pycryptodome library, for AES encryption and decryption.
* base64: For encoding and decoding the AES ciphertext.
