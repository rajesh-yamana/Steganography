# Steganography using XOR

A lightweight Python tool to hide and retrieve secret messages in images using XOR-based steganography. This project demonstrates a simple and effective method for secure message embedding within image files.

## 🔍 Overview

The script performs both encoding and decoding using a bitwise XOR approach. It modifies the least significant bits (LSBs) of an image to embed text and can later extract it using the same logic.

## 🛠️ Features

- Single script for both encoding and decoding  
- Message hidden using XOR logic  
- Minimal visual distortion to the image  
- Simple and easy-to-understand implementation

## 📂 Project Structure
```text
steganography-xor/
├── steganography.ipynb      # Main script for both encoding and decoding
├── sample_input.png         # Input image for encoding
├── encryption.png           # Sample Demonstration of Encryption 
├── decryption.png           # Sample Demonstration of Decryption
└── README.md                # Project documentation


```


## 💡 How It Works

1. **Encoding**: Converts message to binary and embeds it using XOR on pixel LSBs.  
2. **Decoding**: Applies XOR again to extract the original binary message from the image.

## 🚀 Getting Started

1. Install dependencies:  
   ```bash
   pip install pillow
2. Run the script and follow on-screen prompts:
   ```bash
   python steganography.py

## 📈 Use Cases

- 🔐 **Educational demonstrations** of steganography  
- 🖼️ **Securely embedding messages** in image files  
- 🧪 **Basic image-based data security** for academic or personal projects  
- 💬 **Concealing text** in plain sight for lightweight communication


## 👨‍💻 Author

**Rajesh Yamana**  
- [LinkedIn](https://www.linkedin.com/in/rajesh-yamana)  
- [GitHub](https://github.com/rajesh_yamana)

## 🙌 Feedback & Contributions

Have suggestions or want to contribute?  
Feel free to fork the repository, raise an issue, or drop a ⭐ if you found this useful!


