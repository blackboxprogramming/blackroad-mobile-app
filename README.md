# BlackRoad Mobile App 📱

iOS and Android mobile app for BlackRoad - built with React Native!

## Features

- **Dashboard** - View all deployments
- **API Playground** - Test API endpoints
- **Analytics** - Real-time metrics
- **Notifications** - Push notifications for deployments
- **Dark Mode** - Beautiful dark theme

## Screenshots

[Add screenshots here]

## Installation

```bash
npm install
```

### iOS

```bash
cd ios && pod install
npx react-native run-ios
```

### Android

```bash
npx react-native run-android
```

## Build for Production

### iOS
```bash
cd ios
xcodebuild -workspace BlackRoad.xcworkspace -scheme BlackRoad archive
```

### Android
```bash
cd android
./gradlew assembleRelease
```

## Tech Stack

- React Native
- React Navigation
- AsyncStorage
- Axios

## License

MIT License

---

Part of the **BlackRoad Empire** 🚀
