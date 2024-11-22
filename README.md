# QRSC
Quantum-Resistant Symmetric Cipher

# Overview
This project presents a custom symmetric key block cipher designed to be resistant to both classical and quantum computer attacks. Implemented in a single HTML file with embedded JavaScript, CSS, and HTML, the cipher employs a 512-bit block size and a 512-bit key, featuring 16 rounds of substitution and permutation.

# Features
 Symmetric Key Encryption: Utilizes the same key for both encryption and decryption.

Quantum Resistance: Designed to withstand attacks from quantum computers using large key sizes and secure hash functions.

User-Friendly Interface: A simple web interface for encrypting and decrypting text.

Cipher Information Modal: Provides detailed explanations of the cipher's operation and design.

# Installation
No installation is required. Simply open the cipher.html file in a modern web browser that supports the Web Crypto API, such as Chrome or Firefox.

# Usage
Encrypting Text:

Enter the plaintext in the "Plaintext" textarea.

Provide a 128-character hexadecimal key in the "Key" textarea.

Click the Encrypt button.

The ciphertext will appear in the "Ciphertext" textarea.

Decrypting Text:

Enter the ciphertext in the "Ciphertext" textarea.

Use the same key as during encryption.

Click the Decrypt button.

The decrypted text will appear in the "Decrypted Text" textarea.

Cipher Information:

Click the Cipher Information button to view a modal explaining the cipher's design and operation.

Close the modal by clicking the × button or outside the modal area.

# Cipher Design and Security
S-box and Permutation: Currently uses placeholder values; future work includes replacing them with cryptographically secure designs.

Key Schedule: Utilizes SHA-384 to generate round keys, ensuring each round uses a unique and secure key.

Rounds: 16 rounds of substitution, permutation, and key mixing to ensure thorough diffusion and confusion.

# Future Work
S-box and Permutation Improvement: Replace placeholders with more secure and optimized designs.

Performance Optimization: Enhance the cipher's efficiency for real-world applications.

Cryptanalysis: Conduct thorough analysis to identify and address potential vulnerabilities.

# License
This project is licensed under the GNU3 License - see the LICENSE file for details.

# Contact
For questions or further information, please contact 
