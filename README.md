## Overview
This React Native application fetches and displays user data from a public API. Users can navigate between records using **Previous** and **Next** buttons or manually enter an index to jump to a specific user. The app supports smooth UI transitions, error handling, and an optimized layout for different screen sizes.

## Features
- Fetches and displays **80 users** from Random Data API
- Shows **user details** (Avatar, Name, Username, Email, ID, UID, Password)
- **Navigation options**:
  - **Previous/Next** buttons to switch users sequentially
  - **Custom index input** to directly jump to a user
- **Error handling** for API failures or invalid inputs
- **Smooth UI design** with scrollable content and keyboard handling
- **Loading animation** while fetching data

## How to Run the Application Locally

### Prerequisites
Make sure you have the following installed:
- Node.js
- React Native CLI
- Android Studio (for Android emulator) or Xcode (for iOS)
- A physical or virtual device for testing

### Installation Steps
1. Clone the repository:
   ```sh
   git clone <your-repo-link>
   cd <your-project-folder>
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start Metro bundler:
   ```sh
   npx react-native start
   ```
4. Run the app:
   - For Android:
     ```sh
     npx react-native run-android
     ```
   - For iOS (requires macOS & Xcode):
     ```sh
     npx react-native run-ios
     ```

## Additional Notes
- The API fetches **80 random users**; each app launch may show different users.
- If the **API fails**, an alert will notify the user.
- Ensure an **internet connection** when running the app for API requests.
- The **custom index field** only accepts numbers **between 1 and 80**.
- If running on a **physical device**, enable **developer mode** and connect via USB or WiFi.

