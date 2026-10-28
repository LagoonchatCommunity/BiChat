[README.md](https://github.com/user-attachments/files/34070104/README.md)
# BiChat

BiChat is a chat platform available for Android and the web. It is designed to help people stay connected, chat with friends, and communicate in communities.

The project is still being developed, with a focus on making the app easy to use and keeping the Android and web versions working together.

## Features

- Chat with other users
- Add and manage friends
- Create and manage servers
- Send messages and supported files
- View and edit user profiles
- Voice and video calls
- Notifications for messages and other activity
- A simple interface for Android and web users

Some features may still be under development or require additional server configuration.

## Technologies Used

BiChat uses several technologies for its Android app, website, and backend.

- **Kotlin** for the Android app
- **Android SDK** and **Gradle** for building the app
- **HTML, CSS, and JavaScript** for the web interface
- **Node.js** for the backend server

## Getting Started

### Android App

To build the Android app, you need Android Studio and a compatible Android SDK.

1. Clone or download the project.
2. Open the Android project in Android Studio.
3. Wait for Gradle to finish syncing.
4. Connect an Android device or start an emulator.
5. Build and run the app.

You can also build a debug APK from the project directory.

On Windows:

```powershell
.\gradlew.bat assembleDebug
```

On Linux or macOS:

```bash
./gradlew assembleDebug
```

The APK is usually created at:

`app/build/outputs/apk/debug/app-debug.apk`

### Web and Backend

To run the web platform and backend, you need the project source code and a compatible version of Node.js.

1. Download or clone the web and backend project.
2. Install the required dependencies if a package configuration is provided.
3. Set up the server configuration.
4. Start the backend using the command documented by the project.

The exact setup may depend on the current server configuration.

## Development

BiChat is an ongoing project. New features, improvements, and bug fixes are added as development continues.

The goal is to make messaging, file sharing, friendships, and calls work reliably across Android and the web.

## Security

Please keep passwords, private keys, access tokens, and other sensitive information out of public repositories.

For public deployments, use HTTPS and make sure that user input, file uploads, and account access are handled securely.

## Contributing

Suggestions, bug reports, and improvements are welcome.

If you want to contribute, create a separate branch for your changes, test them, and submit a pull request with a short explanation of what you changed.

## License

No license has been added yet. Until a license is chosen, please do not assume that the source code is free to reuse or redistribute.

---

BiChat is being built to make chatting and staying connected simple and convenient.
