# 📷 QR Code Generator – Interactive Node.js CLI Tool

QR Code Generator is a command-line application built with **Node.js** that allows users to generate QR codes interactively. It uses **inquirer** for user prompts and **qrcode** to create and save QR codes as image files.

---

## 🌐 Project Overview

This project enables users to:
- Input any **text** or **URL** through an interactive terminal prompt.
- Automatically generate a corresponding **QR code**.
- Save the QR code as an image (`qr_img.png`) and store the input text in a file (`URL.txt`).

---

## 📌 Features

- 🔵 **Interactive Command-Line Interface**: Input text/URL through an elegant CLI prompt.
- 📩 **Real-Time QR Code Generation**: Instantly generates a QR code based on user input.
- 🖼️ **Image Output**: Saves the generated QR code as an image file.
- 📄 **Input Logging**: Stores the entered URL/text into `URL.txt`.
- 📱 **Minimal, Fast, and User-Friendly**.

---

## 🛠️ Tech Stack

- **Node.js** – JavaScript runtime
- **JavaScript (ES6)** – Scripting language
- **npm Packages**:
  - **qr-image** – To generate QR code images
  - **inquirer** – To interactively prompt user input via terminal

---

## 📦 Dependencies

To install required dependencies:

```bash
npm install inquirer qr-image 
```

---

## 📂 Project Structure

```
Qr-code-Project/
├── index.js
├── package.json
├── package-lock.json
├── qr_img.png (Generated after running)
├── URL.txt (Generated after running)
└── README.md
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/RazeelBuilds/Qr-code-Project.git
```

### 2. Navigate into the Project Directory

```bash
cd Qr-code-Project
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Run the Application

```bash
node index.js
```

- Enter your text or URL when prompted.
- Your QR code will be saved as `qr_img.png` inside the project folder.
- Your input will be saved in `URL.txt`.

---

## 👨‍💻 Developer

**Razeel Kapdi**

- **GitHub**: [RazeelBuilds](https://github.com/RazeelBuilds/)
- **LinkedIn**: [Razeel Kapdi](https://www.linkedin.com/in/razeel-kapdi-698955267/)

---

Bring your links, messages, and ideas to life—one QR code at a time! 📷✨
