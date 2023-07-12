# Flutter Google Docs Clone

A Google Docs clone built with Flutter for the frontend and Node.js, Express, MongoDB, Mongoose, Socket.IO for the backend.

## Description

The Flutter Google Docs Clone is a real-time collaborative document editing application that mimics the functionality of Google Docs. It allows multiple users to simultaneously edit and collaborate on documents in real-time. The frontend is developed using Flutter and Riverpod for state management. The backend is built with Node.js and uses Express as the web framework, MongoDB as the database, and Mongoose as the Object Data Modeling (ODM) library. Socket.IO is used for real-time communication between the clients and the server.

## Features

- User authentication and authorization
- Real-time collaboration and synchronization of document changes
- Document sharing and access control
- Rich text editing with formatting options
- User presence and activity indicators
- Document version history and revision tracking

## Technologies Used

### Frontend
- Flutter: A UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase.
- Riverpod: A state management library for Flutter that provides a simple way to manage application state and dependencies.

### Backend
- Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- Express: A fast, unopinionated, and minimalist web framework for Node.js.
- MongoDB: A document-oriented NoSQL database.
- Mongoose: An Object Data Modeling (ODM) library for MongoDB.
- Socket.IO: A library that enables real-time, bidirectional communication between clients and the server.

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Node.js: [Install Node.js](https://nodejs.org)

### Installation

1. Clone the repository: `git clone https://github.com/soorjya/flutter_google_docs_clone.git`
2. Navigate to the backend directory: `cd flutter_google_docs_clone/backend`
3. Install backend dependencies: `npm install`
4. Set up the environment variables by creating a `.env` file and providing the required configurations (e.g., MongoDB connection URL, JWT secret key, etc.).
5. Start the backend server: `npm start`
6. Open another terminal window and navigate to the frontend directory: `cd ../frontend`
7. Install frontend dependencies: `flutter pub get`
8. Start the Flutter development server: `flutter run`

## Usage

1. Open the Flutter app on your device or simulator/emulator.
2. Create an account or sign in using your existing credentials.
3. Create a new document or select an existing document to collaborate on.
4. Share the document URL with others to invite them to collaborate.
5. Make edits to the document and see the changes reflected in real-time.
6. Explore other features like text formatting, user presence indicators, version history, etc.
7. Enjoy collaborating on documents with other users!

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or new features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name` or `git checkout -b bugfix/your-bug-name`
3. Make the necessary changes and commit them: `git commit -m 'Add some feature'` or `git commit -m 'Fix some bug'`
4. Push your changes to your forked repository: `git push origin feature/your-feature-name` or `git push origin bugfix/your-bug-name`
5. Submit a pull request, explaining the changes you have made and their purpose.

Please ensure that your contributions adhere to the coding conventions and follow the project's guidelines.

## License

[MIT License]

[The MIT license gives express permission for users to reuse code for any purpose, sometimes even if code is part of proprietary software. As long as users include the original copy of the MIT license in their distribution, they can make changes or modifications to the code to suit their own needs.]

## Authors

- [Soorjyakanta](https://github.com/soorjya): Project developer and maintainer


