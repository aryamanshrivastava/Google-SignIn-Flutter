# Flutter Google Sign-In 🚀

---

## Welcome to the _Fluttered Google_ Experience! 🎉

Ever thought of integrating Google Sign-In with your Flutter app with a touch of elegance and simplicity? Search no more. Dive into our solution and flutter your way into your user's Google accounts. (With permission, of course 😉)

![Flutter and Google Sign-In](https://user-images.githubusercontent.com/4372065/84383242-8d170280-ac09-11ea-8f7e-e162197c791b.png)

---

## 🌟 Features:
- **Smooth & Fast**: Designed for top-notch performance.
- **Customizable UI**: Tailor-made to suit your design needs.
- **Security First**: Google authentication at its safest.

---

## 🛠 Setup & Installation:

1. **Get the package**:
    ```yaml
    dependencies:
      flutter_google_signin_package: latest_version
    ```

2. **Install it**:
    ```bash
    $ flutter pub get
    ```

3. **Import it**:
    ```dart
    import 'package:flutter_google_signin_package/flutter_google_signin_package.dart';
    ```

---

## 💼 Usage:

1. **Initialize**:
    ```dart
    final GoogleSignIn googleSignIn = GoogleSignIn();
    ```

2. **Sign In**:
    ```dart
    GoogleSignInAccount? user = await googleSignIn.signIn();
    ```

3. **Get User Data**:
    ```dart
    print(user!.displayName);
    print(user!.photoUrl);
    ```

---

## ✨ Customization:
Check our docs to see how you can paint this canvas!

---

## 🔐 Security:
Our package is fully compliant with Google's standards. Handle the OAuth tokens securely!

---

## 🙌 Contribution:
Contributions are more than welcome. Open a pull request!

---

Made with ❤️ and a dash of Flutter magic!
