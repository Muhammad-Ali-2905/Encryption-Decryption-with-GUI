# RSA-Based Secure Data Handling with GUI

## Project Overview
This project implements a secure data encryption and decryption system using the RSA algorithm, complemented by a user-friendly graphical interface. It is designed to handle sensitive information with high security by leveraging RSA for cryptographic operations.

## Key Features
- **RSA Encryption and Decryption**
  - Utilizes the RSA algorithm, a widely recognized asymmetric encryption technique, to ensure robust data security.
  - Encrypts data with a public key and decrypts data with the corresponding private key.
- **Key Management**
  - Automatically generates RSA key pairs (public and private keys) for the encryption/decryption processes.
- **User Interface**
  - Intuitive GUI in **C#** to manage RSA keys and perform encryption/decryption operations.

## Technical Implementation

### RSA Algorithm
- **Public Key Encryption:** Encrypts data using the RSA public key so only the holder of the private key can decrypt it.
- **Private Key Decryption:** Restores the original data using the RSA private key.

### C# Application
The primary GUI is developed in **C#**. It handles key management and integrates with RSA cryptographic functions implemented in C++.

### C++ Library
Core RSA cryptographic operations are implemented in a **C++** library, which the C# application calls for encryption and decryption.

## Workflow
1. **Key Generation**
2. **Encryption Process**
3. **Decryption Process**
