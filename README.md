# 🧩 QR Code Generator

A simple Node.js application that generates a **QR code image** from any URL you provide.

---

## 📦 Technologies Used
- [Node.js](https://nodejs.org/)
- [inquirer](https://www.npmjs.com/package/inquirer) – for getting user input in the terminal  
- [qr-image](https://www.npmjs.com/package/qr-image) – for generating QR code images  
- Native `fs` module – for creating and writing files  

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/kristiana19/qr-code.git
   cd qr-code
   ```
2. Install dependencies:
    ```bash
   npm install inquirer qr-image
    ```
3. Make sure your project has "type": "module" in package.json (for ES6 imports).
4. Run the app in your terminal:
    ```bash
    node index.js
     ```
5. Enter any URL when prompted (for example https://www.google.com).
6. The program will:

    Generate a QR code image → qr_img.png

    Save your input URL in a text file → URL.txt

7. Open or scan the generated qr_img.png file using your phone camera 📱 — it will automatically open the website you entered.

   ![Demo](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2R4M3p4a2I/giphy.gif)

   

   
