# AES Encryption Tool

A simple Python implementation of AES encryption using EAX mode for secure message encryption and decryption.

## Features

- AES-128 encryption with EAX mode
- Authenticated encryption with integrity verification
- Random key generation using cryptographically secure methods
- Nonce-based encryption for enhanced security

## Requirements

- Python 3.x
- pycryptodome

## Installation

1. Clone this repository:
```bash
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the script:
```bash
python proj.py
```

Enter your message when prompted. The script will:
1. Encrypt your message
2. Display the encrypted ciphertext
3. Decrypt it back to verify integrity
4. Display the decrypted plaintext

## How It Works

- **Encryption**: Uses AES in EAX mode with a randomly generated 16-byte key
- **Authentication**: Includes a tag for message authentication
- **Nonce**: Each encryption uses a unique nonce for security
- **Verification**: Decryption includes integrity verification using the authentication tag

## Security Note

⚠️ This is a demonstration script. The encryption key is regenerated each time the script runs and is not persisted. For production use, implement proper key management and storage.

## License

MIT License - feel free to use and modify as needed.
