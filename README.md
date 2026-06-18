
# Little Lemon Restaurant App

## Overview

Little Lemon is a React Native mobile application developed as part of the Meta React Native Specialization Capstone Project on Coursera. The application allows users to browse the restaurant menu, view featured dishes, and manage their profile information through a clean and responsive mobile interface.

## Features

* User onboarding and profile setup
* Browse restaurant menu items
* Search and filter menu categories
* Persistent local storage using AsyncStorage
* Responsive user interface
* Navigation between screens using React Navigation
* Data fetching from a remote API
* Form validation and user input handling

## Technologies Used

* React Native
* Expo
* JavaScript (ES6+)
* React Navigation
* AsyncStorage
* Context API / React Hooks
* FlatList and SectionList

## Project Structure

```text
LittleLemon/
│
├── assets/
│   ├── images/
│   └── icons/
│
├── screens/
│   ├── Onboarding.js
│   ├── Home.js
│   ├── Profile.js
│
├── components/
│   ├── Header.js
│   ├── Hero.js
│   ├── MenuItem.js
│
├── utils/
│   └── storage.js
│
├── App.js
├── package.json
└── README.md
```

## Installation

### Prerequisites

* Node.js
* npm or yarn
* Expo CLI

### Clone the Repository

```bash
git clone https://github.com/your-username/little-lemon-capstone.git
cd little-lemon-capstone
```

### Install Dependencies

```bash
npm install
```

### Start the Application

```bash
npx expo start
```

Scan the QR code using the Expo Go application on your mobile device or run the app on an emulator.

## Application Screens

### Onboarding Screen

* Collects user information.
* Stores user data locally.

### Home Screen

* Displays featured menu items.
* Supports searching and filtering menu categories.

### Profile Screen

* Shows user profile information.
* Allows updating and saving profile details.

## Learning Outcomes

This project demonstrates:

* React Native fundamentals
* Component-based architecture
* State management with Hooks
* Navigation in mobile applications
* Local data persistence
* API integration
* Responsive mobile UI design

## Future Improvements

* Online ordering functionality
* Authentication system
* Push notifications
* Dark mode support
* Backend integration for real-time updates

## Author

Developed as part of the Meta React Native Capstone Project on Coursera.

## License

This project is created for educational purposes and is not intended for commercial use.
