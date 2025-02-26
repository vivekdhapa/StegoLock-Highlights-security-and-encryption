# **StegoShield: Advanced Image Steganography 🔒🖼️**

A **Python-powered tool** for embedding confidential data inside images using **AES encryption** and **OpenCV**. This ensures that sensitive messages remain protected and can only be accessed by authorized individuals.

## **🚀 Key Features**  
✅ **Enhanced Security** – Combines **AES encryption** and **steganography** for strong data protection.  
✅ **Stealth Mode** – Embeds data with minimal visual distortion, making it hard to detect.  
✅ **Broad Compatibility** – Supports **PNG, JPEG, BMP** formats.  
✅ **Multi-Platform Support** – Works on **Kali Linux**, with adaptability for **Windows and macOS**.  
✅ **Secure Data Retrieval** – Only those with the correct decryption key can extract hidden messages.  

## **🛠️ Technologies Used**  
- **Language:** Python  
- **Libraries:** OpenCV, Stegano, Cryptography, NumPy, PIL (Pillow)  
- **Tools:** Kali Linux, Steghide, OpenStego  
- **Encryption Standard:** AES (Advanced Encryption Standard)  

## **📌 How It Works**  
1. **Encrypt the Message** – The secret text is encrypted using **AES** before embedding.  
2. **Hide in Image** – The encrypted message is discreetly inserted into an image file.  
3. **Share Securely** – The modified image appears unchanged, preventing suspicion.  
4. **Extract & Decrypt** – The receiver retrieves and decrypts the message using the appropriate script and key.  

### **Workflow Example:**  
📷 **Original Image** → 🔐 **Embed Message with Script** → 🖼️ **Modified Image (Visually Identical)** → 🔎 **Extraction Process** → 🔓 **Decrypted Secret Message**  

---

## **📌 Setup & Installation Guide**  

### **🔧 Prerequisites**  

#### **1️⃣ Install Python**  
Ensure Python **3.x** is installed. Get it from:  
🔗 [Python Official Site](https://www.python.org/downloads/)  

Check installation by running:  
```bash
python --version
```

---

#### **2️⃣ Install Required Dependencies**  
Install all necessary libraries with:  
```bash
pip install opencv-python numpy pillow cryptography stegano
```
Or install them one by one:  
```bash
pip install opencv-python    # Image processing  
pip install numpy            # Data manipulation  
pip install pillow           # Image handling  
pip install cryptography     # AES encryption  
pip install stegano          # Steganography processing  
```

---

#### **3️⃣ Optional Tools for Extra Functionality**  
To extend capabilities, install additional steganography tools:  

🔹 **For Kali Linux Users:**  
```bash
sudo apt update && sudo apt install steghide
```
- `steghide` – Useful for alternative data hiding techniques.  

🔹 **For Windows Users:**  
- Install **[OpenStego](https://www.openstego.com/)** – A GUI-based steganography tool.  

---

## **📥 Cloning the Project**  
Download the repository locally:  
```bash
git clone <GitHub_Repo_Link>
cd <Repo_Folder_Name>
```

---

## **▶️ Running the Project**  

### **1️⃣ Conceal a Secret Message in an Image**  
```bash
python hide_message.py
```
- This script securely embeds a hidden message inside an image.  

### **2️⃣ Retrieve the Hidden Message**  
```bash
python extract_message.py
```
- Extracts and decrypts the concealed message from the image.  

💡 **Ensure you have an image file ready before embedding!**  

---

## **🚀 Ready to Go!**  
You can now securely hide and extract messages inside images using this tool.  

## **👥 Target Users**  
- **Cybersecurity Experts & Ethical Hackers**  
- **Journalists & Whistleblowers** (for discreet communication)  
- **Intelligence & Digital Forensics Professionals**  
- **Banking & Healthcare Sectors** (for secure data storage)  
- **Privacy Advocates & Researchers**  

---

## **📄 License**  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  

## **🤝 Contributing**  
Contributions are welcome! Feel free to fork this repository and submit pull requests.  

## **📞 Contact**  
For any inquiries or suggestions, reach out via GitHub Issues.
