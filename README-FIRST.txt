SKINLEDGER — START HERE

You do NOT need to copy the website code into different files. It has already been put in the correct files.

1. Install Node.js (LTS) from https://nodejs.org if it is not already installed. Choose the LTS download.
2. Extract/unzip the folder named skinledger-project.
3. Open Visual Studio Code. Click File > Open Folder. Select the extracted folder named skinledger-project.
4. In VS Code, click Terminal > New Terminal (top menu). A panel opens at the bottom.
5. Copy and paste this command, then press Enter:
   npm install
   Wait until it finishes.
6. Then copy and paste this command, then press Enter:
   npm run dev
7. The terminal will show a local address, usually http://localhost:5173/ . Hold Ctrl (Windows) or Command (Mac) and click it, or copy it into your browser.
8. Keep VS Code open and leave the terminal running while you use the website. To stop it, click the terminal and press Ctrl+C.

FILES:
- src/App.jsx = the full website code
- src/main.jsx = connects the website to React
- src/index.css = styling setup
- package.json = required libraries and commands
- vite.config.js = setup

IMPORTANT:
- The app saves data in your browser on this device using localStorage.
- The skin scanner in the provided code is a demo heuristic, not a medically validated AI skin diagnosis.
- Before making a GitHub repository public, make sure your friend agrees.
