# Car Parking App 🚗🅿️

A cross-platform **Car Parking Game** with **Login, Profile Picture Upload, and Firebase Integration**.  
Built with **Flutter** so it works on both **iOS** and **Android**.

---

## 📌 Features
- **User Registration & Login** (First Name, Last Name, Password)
- **Profile Picture Upload** (from gallery or camera)
- **Remember Me** – automatic login
- **2D Car Parking Game** with:
  - Score system
  - Countdown timer
  - Random parking spots
- **Firebase Integration**:
  - Authentication
  - Firestore database for user data
  - Storage for profile pictures

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/car_parking_app.git
cd car_parking_app
```

### 2️⃣ Install dependencies
```bash
flutter pub get
```

### 3️⃣ Set up Firebase
1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project
3. Enable **Authentication** (Email/Password)
4. Create **Firestore Database**
5. Enable **Firebase Storage**
6. Download the config files:
   - `google-services.json` → place it in `android/app/`
   - `GoogleService-Info.plist` → place it in `ios/Runner/`

### 4️⃣ Run the app
```bash
flutter run
```

---

## 📂 Project Structure
```
lib/
 ├── main.dart          # Entry point
 ├── login_page.dart    # Login & registration
 ├── profile_page.dart  # Profile & avatar
 ├── game_page.dart     # Car Parking game
assets/
 ├── images/            # Game graphics & UI assets
```

---

## 🛠 Technologies Used
- **Flutter** (Dart)
- **Firebase Auth**
- **Firebase Firestore**
- **Firebase Storage**

---

## 📜 License
This project is open-source and free to use.
