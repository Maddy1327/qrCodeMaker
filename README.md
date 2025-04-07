This is a simple Node.js project that takes a user-inputted URL, generates a QR code from it, and saves both the QR image and the original URL in a text file.

## 📦 Built With

- [Node.js](https://nodejs.org/)
- [Inquirer](https://www.npmjs.com/package/inquirer) – for taking user input from the terminal
- [qr-image](https://www.npmjs.com/package/qr-image) – for generating QR codes
- [fs](https://nodejs.org/api/fs.html) – native module to handle file operations

## 🚀 How to Run

1. **Clone the repo**

   ```bash
   git clone https://github.com/maddy1327/qrCodeMaker.git
   cd qrCodeMaker
   
2. **Install Dependencies**

   ```bash
   npm install
   ```
   
3. **Run the App**

   ```bash
   node index.js
   ```

   
4. **Follow the Prompt**

   Type a URL when prompted.  
   ✅ The QR code will be saved as `qr_img.png`  
   ✅ The entered URL will be saved in `URL.txt`

## 📁 Project Structure

```
qrCodeMaker/
├── index.js           # Main logic
├── package.json       # Project metadata and dependencies
├── package-lock.json  # Exact dependency versions
├── .gitignore         # Files to ignore in git (e.g., node_modules)
├── URL.txt            # Stores the entered URL after running
├── qr_img.png         # The generated QR code image
```

## 👨‍💻 Author

Made with ❤️ and ☕ by [Madhav](https://github.com/maddy1327)
