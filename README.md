Seamless Loop Player — Electron Desktop App

How to run (local development):
1. Extract this ZIP to your computer.
2. Open terminal in this folder.
3. Run:
   npm install
   npm start

How to build distributable installers:
   npm run dist
The installers will be output to the 'dist/' folder.

Notes:
- This package uses electron-builder. For macOS builds you need to run on macOS for DMG/notarization.
- For Windows, you can build on Windows or use cross-platform builds with proper setup.
