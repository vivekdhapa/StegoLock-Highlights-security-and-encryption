A Python-based steganography tool that enables secure data hiding within images using AES encryption and OpenCV. This project combines cryptographic security with steganographic techniques to ensure confidential data remains hidden and undetectable. Provides a covert method for secure digital communication.

# **StegoShield: Secure Image Steganography 🔒🖼️**  
A Python-based steganography tool that enables secure data hiding within images using **AES encryption** and **OpenCV**. This project ensures that sensitive information remains covert and accessible only to authorized receivers.  

## **🚀 Features**  
✅ **Dual-layer Security** – Combines AES encryption with steganography for enhanced protection.  
✅ **Low Detectability** – Ensures minimal distortion, making it hard to detect hidden data.  
✅ **Supports Multiple Formats** – Works with **PNG, JPEG, BMP** images.  
✅ **Cross-Platform** – Runs on **Kali Linux**, but can be adapted for Windows and MacOS.  
✅ **Data Extraction Security** – Only users with the correct key can decode the hidden message.  

## **🛠️ Technologies Used**  
- **Programming Language:** Python  
- **Libraries:** OpenCV, Stegano, Cryptography, NumPy, PIL (Pillow)  
- **Tools:** Kali Linux, Steghide, OpenStego  
- **Encryption Algorithm:** AES (Advanced Encryption Standard)  

## **📌 How It Works**  
1. **Encrypt the Message** – Before embedding, the secret message is encrypted using AES.  
2. **Embed in Image** – The encrypted data is hidden within an image file.  
3. **Send Securely** – The modified image can be shared without revealing any signs of hidden data.  
4. **Extract & Decrypt** – The correct receiver, using the extraction script and key, retrieves the hidden message.  

**Example Workflow:**  
🔹 **Original Image** → 🔹 **Message Embedded Using Script** → 🔹 **Modified Image (Visually Unchanged)** → 🔹 **Extraction Process** → 🔹 **Decoded Secret Message**  


### **📌 Prerequisites & Installation Guide**  
---
## **🔧 Prerequisites**  

### **1️⃣ Install Python**  
Ensure you have Python **3.x** installed. Download it from the official website:  
🔗 [Python Download](https://www.python.org/downloads/)  

Check if Python is installed by running:  
```bash
python --version
```

---

### **2️⃣ Install Required Python Libraries**  
Run the following command to install all dependencies:  
```bash
pip install opencv-python numpy pillow cryptography stegano
```

Or install them individually:  
```bash
pip install opencv-python    # OpenCV for image processing  
pip install numpy            # NumPy for array operations  
pip install pillow           # PIL (Pillow) for image handling  
pip install cryptography     # AES encryption for secure data hiding  
pip install stegano          # Steganography library for embedding data  
```

---

### **3️⃣ Install Additional Tools (Optional but Recommended)**  
For enhanced functionality, install additional steganography tools:  

🔹 **For Kali Linux Users:**  
```bash
sudo apt update && sudo apt install steghide
```
- `steghide` – Useful for alternative steganographic techniques.  

🔹 **For Windows Users (If Needed):**  
- Install **[OpenStego](https://www.openstego.com/)** – A GUI-based steganography tool.  

---

## **📥 Cloning the Repository**  
Clone the GitHub repository to your local system:  
```bash
git clone <GitHub_Repo_Link>
cd <Repo_Folder_Name>
```

---

## **▶️ Running the Project**  

### **1️⃣ Hide a Secret Message in an Image**  
```bash
python hide_message.py
```
- This script takes an image and embeds a secret message securely.  

### **2️⃣ Extract the Hidden Message from the Image**  
```bash
python extract_message.py
```
- This script extracts and decrypts the hidden message from the modified image.  

💡 **Ensure you have an image file ready for embedding the message!**  

---

## **🚀 You're All Set!**  
Now, you can securely hide and extract messages within images using steganography.  

## **👥 End Users**  
- **Cybersecurity Professionals & Ethical Hackers**  
- **Journalists & Whistleblowers** (for secure information exchange)  
- **Intelligence Agencies & Digital Forensics Experts**  
- **Banking & Healthcare Sectors** (for secure record keeping)  
- **Privacy Advocates & Researchers**  

