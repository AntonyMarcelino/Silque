# 🎯 Silque

> **A modern and elegant iOS application for signing and managing IPA applications**

![Swift](https://img.shields.io/badge/Swift-5.0+-orange.svg)
![iOS](https://img.shields.io/badge/iOS-18.0+-blue.svg)
![Xcode](https://img.shields.io/badge/Xcode-16.0+-blue.svg)
![License](https://img.shields.io/badge/License-Private-red.svg)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow.svg)

---

## 📖 Description

**Silque** is a native iOS application developed in SwiftUI that allows you to:
- ✨ **Sign IPA applications** with your own certificates
- 📱 **Manage your applications** installed via signing
- 🎨 **Customize the interface** with themes and animations
- 🔒 **Secure access** with Touch ID/Face ID
- 🌐 **Download apps** from external sources

---

## 🚀 Key Features

### 🖊️ IPA Signing
- Import and sign IPA applications
- Developer certificate management
- Advanced application configuration
- OTA (Over-The-Air) installation
- Export signed applications

### 📱 Application Management
- Overview of all your applications
- Detailed statistics (total, weekly, OTA)
- Quick reinstallation via OTA links
- App deletion and organization

### 🎨 Modern Interface
- Glassmorphism design with visual effects
- Customizable animated mesh gradients
- Adaptive themes (light/dark)
- Multilingual interface (EN, FR, DE, TR)

### 🔐 Advanced Security
- Biometric authentication (Touch ID/Face ID)
- Configurable auto-lock
- Secure certificate management
- Optimized cache and storage

---

## 🛠️ Technologies Used

- **Language**: Swift 5.0+
- **Framework**: SwiftUI
- **iOS**: 18.0+
- **Xcode**: 16.0+
- **Architecture**: MVVM with ObservableObject
- **Storage**: UserDefaults + FileManager
- **Security**: LocalAuthentication Framework
- **Animations**: Core Animation + Metal

---

## 🎯 Features by View

### 📱 **AppsView**
- Display of all installed applications
- Advanced search and filtering
- Real-time statistics
- Downloads in progress
- Quick actions (reinstall, delete)

### 🖊️ **SigningView**
- Step-by-step signing interface
- Import IPA from device or AppsView
- Certificate selection and management
- Application configuration (name, icon, bundle ID)
- Dylib and framework management
- Export and OTA installation

### ⚙️ **SettingsView**
- Appearance customization
- Security configuration
- Cache and storage management
- Language settings
- Preferences reset

---

## 🔧 Installation and Configuration

### Prerequisites
- Xcode 16.0+
- iOS 18.0+
- Apple Developer Certificate
- iOS Device/Simulator

### Installation
Download the latest Silque.ipa and sign it with your certificate.

### Configuration
1. **Certificates**: Add your developer certificates in the app
2. **Bundle ID**: Configure your unique Bundle ID
3. **Signing**: Enable automatic signing in Xcode
4. **Build & Run**: Compile and run on your device

---

## 🎨 Screenshots

| IMG_1332 | IMG_1329 | IMG_1328 |
|----------|----------|----------|
| ![IMG_1332](IMG_1332.PNG) | ![IMG_1329](IMG_1329.PNG) | ![IMG_1328](IMG_1328.PNG) |

| IMG_1327 | IMG_1326 | IMG_1325 |
|----------|----------|----------|
| ![IMG_1327](IMG_1327.PNG) | ![IMG_1326](IMG_1326.PNG) | ![IMG_1325](IMG_1325.PNG) |

---

## 📄 License

This project is under private license. All rights reserved.

```
Copyright (c) 2025 Antony Marcelino
All rights reserved.
```

---

## 👨‍💻 Author

**Antony Marcelino** (@AntonyM1)  
- GitHub: [@AntonyMarcelino](https://github.com/AntonyMarcelino)
- Project created: June 3, 2025
- Last updated: June 15, 2025

---

## 📞 Support

For any questions or issues:
- 🐛 **Issues**: Create an issue on GitHub
- 📧 **Email**: Contact via GitHub
- 📖 **Documentation**: Check the source code

---

## 🔄 Changelog

# 📋 Changelog - Silque v1.0b6

# 📱 AllAppsView - Universal App Management for Silque

![Swift](https://img.shields.io/badge/Swift-5.0+-orange)
![iOS](https://img.shields.io/badge/iOS-14.0+-blue)
![SwiftUI](https://img.shields.io/badge/SwiftUI-2.0+-green)
![Version](https://img.shields.io/badge/Version-2.2.1-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

> **Comprehensive app management interface for Silque iOS - View, filter, search and manage all applications from all sources in one unified interface.**

## 🌟 Overview

AllAppsView is a powerful SwiftUI component that provides a centralized interface for managing applications across multiple sources in the Silque ecosystem. It combines advanced filtering, real-time search, intelligent sorting, and seamless download management into a single, intuitive view.


## ✨ Key Features

### 🔍 **Advanced Filtering System**
- **4 Smart Filters**: All, Installed, Updates Available, Not Installed
- **Real-time Counters**: Live statistics for each category
- **Instant Response**: Zero-delay filter switching with smooth animations

### 📊 **Flexible Sorting Options**
- **By Name**: Alphabetical sorting with localization support
- **By Source**: Group applications by their origin repository
- **By Version**: Latest versions first for easy discovery
- **By Recent**: Newest additions highlighted

### 🔍 **Universal Search Engine**
- **Multi-field Search**: Name, Bundle ID, Source, Description
- **Real-time Results**: Instant filtering as you type
- **Smart Matching**: Case-insensitive with partial matching

### 📝 **Rich App Descriptions**
- **Intelligent Truncation**: 150-character smart cutoff
- **Expandable Content**: "See more/See less" with smooth animations
- **Adaptive Layout**: Maintains alignment regardless of description length

### 📈 **Live Statistics Dashboard**
- **Real-time Counters**: Total, Installed, Updates, Not Installed
- **Visual StatCards**: Color-coded information cards
- **Automatic Updates**: Refreshes on data changes

### ⬇️ **Integrated Download Management**
- **Progress Tracking**: Real-time download progress visualization
- **Status Indicators**: Downloading, Completed, Failed, Waiting, Cancelled
- **Retry Functionality**: Smart error recovery with one-tap retry
- **Queue Management**: Efficient handling of multiple downloads


**Built with ❤️ in Swift & SwiftUI**

![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=xcode&logoColor=white)

</div>
