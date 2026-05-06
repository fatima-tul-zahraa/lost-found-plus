# 🔍 Lost Found Plus

A cross-platform Flutter application for reporting and discovering lost and found items. Users can post lost items with photos, browse found items, and help reconnect people with their belongings.

## ✨ Features

- 📸 Upload photos of lost/found items using the device camera or gallery
- 🆔 Unique item tracking with UUID-based identifiers
- 🎨 Clean, modern UI powered by Google Fonts
- 📅 Date/time formatting for item reports
- 📱 Supports Android & iOS

## 🛠️ Tech Stack

| Package | Version | Purpose |
|---|---|---|
| Flutter | SDK | UI framework |
| google_fonts | ^6.1.0 | Typography |
| image_picker | ^1.0.4 | Camera & gallery access |
| intl | ^0.18.1 | Date/time formatting |
| uuid | ^4.2.1 | Unique item IDs |

## 🚀 Getting Started

### Prerequisites

- Flutter SDK `>=3.38.4`
- Dart SDK `>=3.11.0 <4.0.0`
- Android Studio / Xcode (for device/emulator)

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/lost-found-plus.git

cd lost-found-plus

# Install dependencies
flutter pub get

# Run the app
flutter run
```

## 📂 Project Structure
lib/
├── main.dart          # App entry point
├── screens/           # UI screens
├── widgets/           # Reusable components
└── models/            # Data models