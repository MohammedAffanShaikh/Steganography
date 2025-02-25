# Secure Data Hiding in Images Using Steganography

## 🔒 About the Project
This project implements **secure data hiding** within images using **steganography**. Steganography is the practice of concealing messages or information within other non-secret data. This tool allows users to **embed secret messages** inside images in a way that is **invisible to the human eye** but can be extracted later with the right decryption method.

## 🚀 Features
- 🔹 **Hide Text in Images** – Encrypt and embed text messages into images.
- 🔹 **Extract Hidden Messages** – Retrieve embedded messages securely.
- 🔹 **Support for Multiple Image Formats** – Works with PNG, JPEG, BMP, etc.
- 🔹 **Password Protection** – Optionally encrypt hidden messages.
- 🔹 **Easy-to-Use Interface** – Command-line or GUI-based usage.

## 📌 Technologies Used
- **Python** 🐍
- **OpenCV** (Image processing)
- **NumPy** (Data manipulation)
- **Cryptography** (Optional for encryption)

## 🛠 Installation
To get started, clone the repository and install the required dependencies:

```sh
# Clone the repository
git clone https://github.com/your-username/secure-steganography.git
cd secure-steganography

# Install dependencies
pip install -r requirements.txt
```

## 📖 Usage
### 🔹 Hide a Message
```sh
python steganography.py --hide --input image.png --output stego_image.png --message "Your secret message here" --password mypassword
```

### 🔹 Extract a Message
```sh
python steganography.py --extract --input stego_image.png --password mypassword
```
### Input Code
![op1](https://github.com/user-attachments/assets/90b4ced5-3e8d-46c5-9ad4-383061cf65a7)
![op3](https://github.com/user-attachments/assets/170a21af-e3c3-40d3-abd2-a385ab9fd668)

### Output

![op2](https://github.com/user-attachments/assets/39bc6da2-d134-49df-b054-b2b35ed1b8e8)








## 🛡 Security Considerations
- **Encryption is optional** but recommended for added security.
- The image should not be compressed or resized after hiding the message, as it may distort the hidden data.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

## 📩 Contact
For any inquiries, reach out to me at: [your.email@example.com](mailto:your.email@example.com)

---
_⭐ If you find this project helpful, please give it a star on GitHub! ⭐_
