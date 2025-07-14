🐬 Bruce Firmware – Flipper Zero UI Mod 🐬
- This repository contains a modified version of the Bruce firmware, where the default look has been replaced with a Flipper Zero-inspired UI. The goal is to give Bruce firmware a fun, modern look with familiar Flipper-style visuals.

## 💛 If you like this project please leave a star

## 🚩 This version of Bruce-Firmware is maded only for LilyGo T-Embed's

🔧 What's Modified:
- Custom IR Reading
- Custom TV-B-GONE
- Custom RFID reading

❔ What's comming next?
- Custom File System
- Custom RF
- Also more

## 🎈 How to set it up?
- Download the src folder
- Go to [Bruce-Main](https://github.com/pr3y/Bruce/tree/main) and download the code
- Replace the updated src file in the original [Bruce-Main](https://github.com/pr3y/Bruce/tree/main) folder
- Build the apliaction
- Command to build it -> `pio run -e lilygo-t-embed-cc1101 -t upload --upload-port ((Your COM port)CHANGE ME!)`
- |_ for example -> `pio run -e lilygo-t-embed-cc1101 -t upload --upload-port COM4`

📦 Based On:
- Original Bruce firmware: [Bruce-Main](https://github.com/pr3y/Bruce/tree/main)

⚠️ This firmware is intended for educational purposes only. The author is not responsible for any misuse or illegal use.
