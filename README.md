# scpy-first-cipher

## Vigenère Cipher Implementation 🔐
A simple Python program to encrypt and decrypt text using the Vigenère Cipher, a method of encrypting text based on a keyword.

## 📌 How It Works
This program takes a message and a custom key to perform encryption and decryption.
- Encryption: Each letter is shifted based on the corresponding letter in the key.
- Decryption: The process is reversed to retrieve the original message.

## 🚀 Features
- ✔ Encrypts and decrypts messages using the Vigenère Cipher
- ✔ Supports custom keys for stronger encryption
- ✔ Preserves spaces and punctuation
- ✔ Uses modulo arithmetic to wrap around the alphabet

## 🛠 Installation
- 1️⃣ Clone the repository
  ```bash
  git clone https://github.com/daffapramata/scpy-first-cipher.git
- 2️⃣ Navigate into the directory
  ```bash
  cd scpy-first-cipher
- 3️⃣ Run the script
  ```bash
  python vigenere.py

## 📝 Code Explanation
🔹 Functions
- vigenere(message, key, direction=1) → Core function that handles both encryption and decryption.
- encrypt(message, key) → Encrypts the given message.
- decrypt(message, key) → Decrypts the given text.

🔹 Algorithm Steps
- 1️⃣ Convert the message to lowercase
- 2️⃣ Loop through each character in the message
- 3️⃣ Find the corresponding key character
- 4️⃣ Calculate the new position using modulo arithmetic
- 5️⃣ Append non-alphabet characters unchanged

## 💡 Why Vigenère Cipher?
The Vigenère Cipher is a polyalphabetic cipher, making it more secure than a simple Caesar Cipher. It uses a repeating key to shift letters, reducing pattern recognition in frequency analysis.

## 📜 License
This project is licensed under the MIT License – feel free to modify and use it!

## 👨‍💻 Author
Daffa – Passionate about cryptography, Python, and problem-solving 🚀

## 🌟 Contribute
Found a bug or want to improve the code? Feel free to fork the repo and submit a pull request!
