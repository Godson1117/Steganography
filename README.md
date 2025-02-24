# 🖼️ Image Steganography - Hide Secret Messages in Images  

## 📌 Overview  
This project implements **image-based steganography**, where secret messages are embedded within an image by modifying pixel values. The encrypted image appears unchanged, ensuring **secure and discreet communication**.  

## ✨ Features  
- 🔒 **Stealthy Data Hiding** – Encodes messages in pixel values without visible distortion.  
- 🎨 **RGB Channel Utilization** – Spreads the message across Red, Green, and Blue channels.  
- 🔑 **Password-Protected Decryption** – Ensures only authorized users can retrieve the message.  
- 📷 **Minimal Image Distortion** – Keeps the image visually unchanged after encryption.  

## 🛠️ Technologies Used  
- **Python** – Programming language  
- **OpenCV (cv2)** – Image processing library  
- **NumPy** – Handling pixel data  
- **OS** – File handling operations  

## 🚀 Installation & Setup  
1. Install dependencies:  
   ```bash
   pip install opencv-python numpy
   ```

2. Place your image file (e.g., mypic.jpg) in the project directory.

3. Run the encryption script:
   ```bash
   python encrypt.py
   ```

## 🔐 Usage

### 📝 Encryption
1. Run encrypt.py.
2. Enter the secret message and a password.
3. The message is embedded in the image, and encryptedImage.jpg is saved.

### 🔓 Decryption
1. Run decrypt.py.
2. Enter the correct password.
3. The hidden message is extracted and displayed.

### 👥 End Users
1. Cybersecurity Professionals – Secure communication & data hiding.
2. Journalists & Whistleblowers – Protect sensitive information.
3. Government & Intelligence Agencies – Covert data transmission.
4. General Users – Hide personal messages securely.

### 📌 Conclusion
This project provides a discreet and secure way to hide messages in images using steganography. By utilizing pixel manipulation and password protection, it ensures confidentiality without altering the image's appearance.

### 👨‍💻 Contributors
Godson Sojan

### 📜 License
This project is licensed under the MIT License.