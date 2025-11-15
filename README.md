# VoucherApp 🧾

A modern, cross-platform React Native mobile application that allows tutors and educational institutions to generate, manage, and share professional tuition fee vouchers effortlessly.

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-blue?style=for-the-badge)

## ✨ Features

- **⚡ Quick Voucher Generation** - Create professional vouchers in seconds
- **👥 Student Management** - Save student details for quick reuse
- **📚 Course Management** - Manage multiple courses and fee structures
- **🎨 Professional Templates** - Multiple clean, professional voucher designs
- **💾 Offline First** - Works completely offline with local data storage
- **📤 Instant Sharing** - Share vouchers as PDF via WhatsApp, Email, or any app
- **📊 Voucher History** - Track all generated vouchers with search and filter
- **🔄 Recurring Fees** - Automatic monthly/weekly voucher generation
- **🌓 Dark/Light Mode** - Comfortable viewing in any lighting

## 📸 Screenshots

<div align="center">
  
| Dashboard | Create Voucher | Voucher History |
|:---:|:---:|:---:|
| <img src="screenshots/dashboard.png" width="200"> | <img src="screenshots/create-voucher.png" width="200"> | <img src="screenshots/history.png" width="200"> |

</div>

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v18 or newer)
- **npm** or **yarn** or **pnpm**
- **Expo Go** app on your physical device

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ullahhafeez321/VoucherApp-Tuition.git
   cd VoucherApp-Tuition
Install dependencies

bash
npm install
Start the development server

bash
npx expo start
Run on your device

Scan the QR code with Expo Go app (Android) or Camera app (iOS)

Building for Production
bash
# Build for Android
npx expo run:android

# Build for iOS
npx expo run:ios

# 🛠️ Tech Stack
Framework: React Native + Expo

Language: TypeScript

Navigation: React Navigation

State Management: Zustand

UI Library: React Native Paper

Storage: AsyncStorage

PDF Generation: react-native-html-to-pdf

Sharing: expo-sharing

Icons: React Native Vector Icons

# 📁 Project Structure
text
VoucherApp/
├── app/                 # Expo Router screens
├── components/          # Reusable UI components
│   ├── ui/             # Basic UI components
│   ├── forms/          # Form components
│   └── vouchers/       # Voucher-related components
├── constants/           # App constants & themes
├── context/             # React Context providers
├── hooks/               # Custom React hooks
├── screens/             # App screens
│   ├── Dashboard/       # Main dashboard
│   ├── CreateVoucher/   # Voucher creation
│   ├── History/         # Voucher history
│   ├── Students/        # Student management
│   └── Settings/        # App settings
├── services/            # Business logic & storage
├── types/               # TypeScript definitions
├── utils/               # Helper functions
└── assets/              # Images, fonts, icons
## 💡 Usage
Add Students: Go to Students tab to add student details

Create Courses: Set up courses with respective fee structures

Generate Vouchers: Use the Create tab to generate vouchers

Manage History: View and search all generated vouchers

Share Vouchers: Export and share vouchers as PDF

## 🤝 Contributing
We welcome contributions! Please feel free to submit issues, feature requests, or pull requests.

Development Setup
Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support
If you have any questions or need help:

Open an issue

Contact: ullahhafeez321@gmail.com

## ⭐ If you find this project useful, please give it a star!

