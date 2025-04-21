# 📱 React Native QR Code Scanner

This is a simple and lightweight React Native application that scans QR codes and displays the scanned content on the screen.

## 🚀 Features

- Built with **React Native**
- QR code scanning using the device camera
- Displays scanned content in real-time
- Minimal and clean user interface

## 🛠 Requirements

- [Node.js](https://nodejs.org/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- Android or iOS device/emulator

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/aliakbar-zohour/reactnative-QrCode-scanner.git
cd reactnative-QrCode-scanner
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npx expo start
```

4. **Run the app**

- Scan the QR code using the Expo Go app on your device
- Or press `a` to launch the Android emulator, `i` for iOS (Mac only)


## 📚 Dependencies

- `expo-camera`
- `react-native-qrcode-scanner`
- `react-native-permissions` (if needed)

## 🧠 How It Works

- The camera is opened using Expo Camera or QR Scanner package.
- Once a QR code is detected, its content is extracted and displayed below the scan box.

## 💡 Example Use Cases

- Reading links, IDs, or messages from QR codes
- Educational or demo projects
- QR-based login or verification apps

## 🧹 Reset or Clear Data

No data is stored persistently. Closing the app resets the state.

## 🛑 Troubleshooting

- Make sure your camera permissions are enabled.
- If using Expo, ensure the required packages are installed properly.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Happy Scanning! 🎉
