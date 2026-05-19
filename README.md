# Namma Vastra (Self-Employment)

Namma Vastra is a dedicated Android application designed to empower local weavers by providing them with a digital marketplace and tools to manage their craft effectively. The app aims to bridge the gap between traditional craftsmanship and modern commerce.

## 🚀 Features

- **Loom Gallery (Marketplace):** A digital showcase where weavers can list their sarees and buyers can view them. Includes direct contact integration via WhatsApp.
- **Upload Saree:** A simple interface for weavers to photograph and list their products, including descriptions and pricing.
- **Fair Price Calculator:** A tool to help weavers calculate recommended market prices based on material costs, labor, and a fair profit margin.
- **Trend Board:** Keeps weavers updated with current market trends and popular designs.
- **Weaver Stories:** A section dedicated to the rich heritage and stories behind the craft.
- **Local-First Fallback:** The app is designed to work seamlessly even without immediate Firebase configuration by utilizing local session storage.

## 🛠 Tech Stack

- **UI:** [Jetpack Compose](https://developer.android.com/jetpack/compose) (Modern Android Toolkit)
- **Language:** [Kotlin](https://kotlinlang.org/)
- **Navigation:** Compose Navigation
- **Asynchronous Work:** Kotlin Coroutines & Flow
- **Image Loading:** [Coil](https://coil-kt.github.io/coil/)
- **Backend (Optional):** Firebase Firestore & Firebase Storage
- **Architecture:** MVVM (Model-View-ViewModel)

## 📦 Getting Started

### Prerequisites
- Android Studio Ladybug (or newer)
- JDK 11+
- Android SDK Level 35 (Compile SDK)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/NammaVastra.git
   ```
2. Open the project in Android Studio.
3. Sync Project with Gradle Files.
4. (Optional) To enable cloud features, add your `google-services.json` to the `app/` directory and uncomment the Firebase plugin in `app/build.gradle.kts`.

### Building the APK
To build the debug APK, run the following command in the terminal:
```bash
./gradlew assembleDebug
```
The APK will be generated at `app/build/outputs/apk/debug/app-debug.apk`.

## 📂 Project Structure

- `app/src/main/java/.../ui/screens/`: Contains all Compose screen implementations.
- `app/src/main/java/.../viewmodel/`: Contains `LoomViewModel` for state management.
- `app/src/main/java/.../model/`: Data classes for Saree and Trend items.
- `app/src/main/res/`: Resources including strings and themes.

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
