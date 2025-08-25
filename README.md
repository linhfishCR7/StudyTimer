# Study Timer

Pomodoro timer and study session management with focus tracking and break reminders

## 📱 App Information

- **Package Name:** `com.lehau.StudyTimer`
- **Category:** education
- **Platform:** Android (Apache Cordova)
- **Version:** 1.0.0

## 🚀 Features

- Pomodoro technique
- Study sessions
- Break reminders
- Progress tracking

## 🛠️ Build Instructions

### Prerequisites

- Node.js (v16 or higher)
- Apache Cordova CLI: `npm install -g cordova`
- Android SDK and Android Studio

### Local Development

1. **Clone and setup:**
   ```bash
   git clone <repository-url>
   cd StudyTimer
   npm install
   ```

2. **Add Android platform:**
   ```bash
   cordova platform add android
   ```

3. **Build for development:**
   ```bash
   cordova build android
   ```

4. **Run on device/emulator:**
   ```bash
   cordova run android
   ```

5. **Build for production:**
   ```bash
   cordova build android --release
   ```

### CI/CD with Codemagic

This project includes a `codemagic.yaml` configuration for automated builds:

1. Connect your repository to [Codemagic](https://codemagic.io)
2. The build will automatically:
   - Install dependencies
   - Add Android platform
   - Build release APK/AAB
   - Generate artifacts

## 📦 Plugins Used

- `cordova-plugin-local-notification`
- `cordova-plugin-vibration`
- `cordova-plugin-background-mode`

## 🏗️ Project Structure

```
StudyTimer/
├── www/                 # Web assets
│   ├── css/            # Stylesheets
│   ├── js/             # JavaScript files
│   ├── img/            # Images and icons
│   └── index.html      # Main HTML file
├── platforms/          # Platform-specific code (auto-generated)
├── plugins/            # Cordova plugins (auto-generated)
├── config.xml          # Cordova configuration
├── package.json        # Node.js dependencies
├── codemagic.yaml      # CI/CD configuration
└── README.md           # This file
```

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**LinhFish Development Team**
- Email: dev@linhfish.com

---

Built with ❤️ using Apache Cordova and the Cordova App Generator