# AUTHENTICATION-_ENCRYPTION
Project Title
Secure File Encryption, Decryption & Digital Signature Verification System
📌 Project Description
This project is a Flask-based web application designed to provide secure file handling through encryption, decryption, and digital signature verification. The system ensures data confidentiality, integrity, and authenticity by combining cryptographic techniques with a user-friendly interface.
The application allows users to log in securely and upload files for processing. For encryption and decryption, the system uses a custom XOR-based encryption algorithm, where the user provides a secret key. Before encryption, a unique header is added to the file to ensure correct decryption and prevent unauthorized access with incorrect keys. The system also displays important file metadata such as file size, creation time, and modification time after processing.
For data integrity and authentication, the project implements digital signature generation and verification using RSA algorithm. When signing a file, a custom hashing function is applied to the file content, and the hash is encrypted using the RSA private key to generate a digital signature. During verification, the signature is decrypted using the RSA public key and compared with the hash of the uploaded file to confirm whether the file is authentic and unchanged.
Additionally, the project includes session-based authentication (login/logout system) to restrict access to authorized users only. The system handles file uploads, key management, and result generation efficiently, storing outputs such as encrypted files and signatures for download.
Overall, this project demonstrates the practical implementation of cryptography concepts like hashing, symmetric encryption, and asymmetric encryption, making it highly useful for secure data transmission and storage applications.
⚙️ Key Features
🔑 User Login Authentication
🔐 File Encryption & Decryption (XOR-based)
✍️ Digital Signature Generation (RSA Private Key)
✔️ Signature Verification (RSA Public Key)
📂 File Upload & Download System
📊 File Metadata Display
🛡️ Data Integrity & Security Assurance
🚀 Project Objective
The main objective of this project is to build a secure platform for protecting sensitive files, ensuring that:
Data remains confidential (via encryption)
Data is not altered (via hashing)
Sender authenticity is verified (via digital signatures)
