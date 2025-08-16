# MediTrack - Medication Reminder Application

A cross-platform medication management solution built with React Native and Expo for iOS and Android devices.

## Key Features

- **Custom Medication Scheduling**: Personalized reminders for each medication
- **Refill Management**: Track medication supply with low stock alerts
- **Biometric Security**: Face ID/Touch ID authentication
- **Progress Tracking**: Medication adherence history and visualization
- **Calendar Integration**: Sync doses with device calendar
- **Cross-Platform Compatibility**: iOS and Android support
- **Offline-First Architecture**: Secure local data storage

## Technology Stack

- **Frontend Framework**: React Native with TypeScript
- **Development Platform**: Expo SDK
- **Navigation**: React Navigation
- **Notification System**: Expo Notifications
- **Animation Library**: React Native Reanimated
- **Authentication**: Expo Local Authentication
- **Data Storage**: AsyncStorage

## Installation
npm install

## Launch development server:

bash
npx expo start

### Prerequisites
- Node.js (version 16 or higher recommended)
- npm or yarn package manager
- Expo CLI (install via `npm install -g expo-cli`)
- iOS Simulator or Android Emulator (optional)
- Expo Go mobile application (for physical device testing)

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/meditrack.git
   cd meditrack
Install project dependencies:

bash
npm install
Launch development server:

bash
npx expo start
Development Guide
Running the Application
iOS Simulator: Press i in terminal after starting development server

Android Emulator: Press a in terminal after starting

Physical Device: Scan displayed QR code with Expo Go app

## Project Structure
text
meditrack/
├── app/                  # Primary application directory
│   ├── components/       # Shared UI components
│   ├── constants/        # Application constants
│   ├── hooks/            # Custom React hooks
│   ├── navigation/       # Navigation configuration
│   ├── screens/          # Application screens
│   ├── services/         # Business logic services
│   ├── styles/           # Global styling
│   ├── types/            # TypeScript definitions
│   └── utils/            # Utility functions
├── assets/               # Static resources
├── .expo/                # Expo configuration
└── .gitignore            # Version control ignore rules

## Educational Value

Key learning areas include:
- React Native development patterns
- Expo platform integration 
- Push notification implementation
- Biometric authentication workflows
- Client-side data management
- Calendar system integration  
- Mobile interface design principles



