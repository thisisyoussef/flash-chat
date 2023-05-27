# Flash-Chat

## Project Overview

Flash-Chat is a real-time chat application built with Flutter, a UI toolkit that allows building natively compiled applications for mobile, web, and desktop. The app features a beautiful UI, backend-connected user authentication, and real-time messaging functionality with Firestore database integration.

## Installation Instructions

1. Clone the repository
   ```
   git clone https://github.com/thisisyoussef/flash-chat.git
   ```
2. Change directory to the project folder
   ```
   cd flash-chat
   ```
3. Install dependencies
   ```
   flutter pub get
   ```
4. Open the project with your favorite IDE (Android Studio, Visual Studio Code, etc.)

## Usage Guide

1. Set up a new project on Firebase, and enable Google authentication and Cloud Firestore
2. Configure the project with your firebase credentials. Add your `google-services.json` and `GoogleService-Info.plist` files to the `android/app` and `ios/Runner` folders, respectively
3. Run the app on your emulator or physical device using your IDE's run button or by executing the following command in your terminal:
   ```
   flutter run
   ```

## Features and Functionality

- User authentication using Google Sign-In
- Real-time messaging functionality
- Firestore database integration
- Beautiful, responsive UI with smooth animations
- Supports both Android and iOS platforms

## Contributing Guidelines

We welcome contributions from fellow developers. To contribute, please take the following steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature_branch`)
3. Commit your changes (`git commit -m 'Added a new feature'`)
4. Push to the branch (`git push origin feature_branch`)
5. Create a Pull Request

Please ensure your code is properly formatted and follows the best practices.

## Technologies and Tools

- **Flutter:** The UI toolkit used to build natively compiled applications for mobile, web, and desktop from a single codebase
- **Dart:** The programming language used along with Flutter
- **Firebase:** Backend services for user authentication and real-time messaging functionality
- **Firestore:** A NoSQL cloud database to store and sync data, providing real-time data synchronization for the chat functionality

These technologies enable Flash-Chat to offer high performance, beautiful UI, seamless real-time messaging capabilities, and easy scalability.

## License Information

This project is licensed under the MIT License. For more information, refer to the LICENSE file in the repository.

## Contact Information

If you have any questions or suggestions, please feel free to reach out.

- GitHub: [thisisyoussef](https://github.com/thisisyoussef)
- Email: youssef@example.com