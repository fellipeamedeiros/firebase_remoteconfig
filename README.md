# Firebase Remote Config using flutter to A/B POC

## Credentials

Insert your Firebase Optins in the _main.dart_ file

```sh
await Firebase.initializeApp(
    options: FirebaseOptions(
      apiKey: 'API-KEY',
      appId: 'APP-ID',
      messagingSenderId: 'MESSAGESENDER-ID',
      projectId: 'PROJECT-ID',
      authDomain: 'AUTH-DOMAIN',
      storageBucket: 'STORAGE'
    ),
  );
```

## Installation

Application requires [Flutter](https://flutter.dev/) to run.

Create a parameter (Key: Text) in remote config on Firebase Console, and start the application.

```sh
flutter run -d chrome
```