## Finstagram
A social media application built with Flutter, replicating core features of Instagram, focusing on a clean UI and seamless user experience. This project serves as a learning exercise to explore Flutter's capabilities for building cross-platform mobile applications and integrating with backend services like Firebase.

## Features
User Authentication: Secure sign-up and login using email/password.
Photo Feed: Scrollable feed displaying posts from followed users.
Posting Photos: Users can upload new photos directly from their device.
User Profiles: View individual user profiles with their posts.
Firebase Integration: Utilizes Firebase for backend services (Authentication, Firestore, Storage).
Responsive UI: Designed to work across various screen sizes.
## Technologies Used
Flutter: The UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.
Dart: The programming language used by Flutter.
Firebase:
Firebase Authentication: For user registration and login.
Cloud Firestore: A flexible, scalable database for storing user data, posts, and comments.
Firebase Storage: For storing user-uploaded images.
Provider: For state management.
Image Picker: To allow users to select images from their gallery or camera.
## Getting Started
Follow these steps to get a local copy of the project up and running on your machine.

Prerequisites
Flutter SDK installed and configured.
VS Code (recommended IDE) with the Flutter extension.
A Firebase project set up and configured for your Flutter app (with GoogleService-Info.plist for iOS and google-services.json for Android).
Installation
Clone the repository:

Bash

git clone https://github.com/himanshu0696/finstagram-flutter-app.git
Navigate into the project directory:

Bash

cd finstagram-flutter-app
Install dependencies:

Bash

flutter pub get
Configure Firebase:

For Android: Place your google-services.json file in the android/app/ directory.
For iOS: Place your GoogleService-Info.plist file in the ios/Runner/ directory.
Ensure your Firebase project has Authentication, Firestore, and Storage enabled.
Run the application:

Bash

flutter run
This will launch the app on your connected device or emulator.

## Project Structure
finstagram-flutter-app/
├── android/               # Android specific project files
├── ios/                   # iOS specific project files
├── lib/                   # Dart source code
│   ├── main.dart          # Main entry point of the app
│   ├── pages/             # Different screens/pages of the app
│   ├── services/          # Services for Firebase interaction, etc.
│   └── ...
├── pubspec.yaml           # Project dependencies and metadata
├── README.md              # This file
├── .gitignore             # Files ignored by Git
└── ... (other Flutter generated files)
## Contributing
Contributions are welcome! If you find a bug or have an idea for an improvement, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact
Himanshu - [Your Email Address / LinkedIn Profile Link (Optional)]

Project Link: https://github.com/himanshu0696/finstagram-flutter-app

