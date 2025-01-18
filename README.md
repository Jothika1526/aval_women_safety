# AVAL - Women's Safety App

AVAL is a women’s safety application designed to provide real-time assistance, enhance security, and promote well-being through advanced technologies such as geofencing, AI-powered health chatbots, and real-time location monitoring.

## Features

1. **Danger Zone Alerts**
   - Monitors live user location.
   - Provides notifications if the user approaches high-crime areas.
   - Offers safer route suggestions.

2. **Geofence Monitoring**
   - Custom geofences for specific areas.
   - Alerts when entering or leaving defined boundaries.

3. **Emergency Response System**
   - SOS alerts activated by voice commands.
   - Sends real-time location to emergency contacts.

4. **AI-Powered Health Advisor**
   - Symptom analysis and relaxation tips.
   - Telemedicine support.

5. **AI-Powered  Safety score measure**
   - Image analysis and predict the safety score.
   - Safety measure tips and advice.

## Prerequisites

Before cloning and running the app, ensure you have the following installed:

1. **Flutter** (v3.27.1)
   - Installation: [Flutter Official Guide](https://docs.flutter.dev/get-started/install)

2. **Dart** (v3.6.0)
   - Comes bundled with Flutter.

3. **Python** (v3.8 or later)
   - Installation: [Python Official Guide](https://www.python.org/downloads/)

4. **Flask** (v3.0.3)
   - Install using pip: `pip install flask`

5. **Firebase CLI**
   - Installation: [Firebase CLI Guide](https://firebase.google.com/docs/cli)

6. Additional Packages:
   - Flutter: `geolocator`, `geofencing`, `http`
   - Python: `numpy`, `pandas`, `twilio`

## Cloning the Repository

1. Open a terminal and navigate to your desired directory.
2. Clone the GitHub repository:
   ```bash
   git clone https://github.com/Jothika1526/aval_women_safety
   ```
3. unzip the main file 
4. Navigate to the cloned directory:
   ```bash
   cd main
   ```

## Setting Up the App

### **Backend Setup**
1. Run the Flask server:
   ```bash
   python otp.py
   python terminal.py
   python safety_recom.py
   python safety_sc.py
   ```

### **Frontend Setup**
   ```
1. Install Flutter dependencies:
   ```bash
   flutter pub get
   ```
2. Run the app:
   ```bash
   flutter run
   ```

## Firebase Configuration
1. Create a Firebase project on [Firebase Console](https://console.firebase.google.com/).
2. Download the `google-services.json` file for Android and place it in the `android/app` directory.
3. For iOS, download the `GoogleService-Info.plist` file and place it in the `ios/Runner` directory.

## Usage
1. Launch the app on an emulator or a physical device.
2. Sign up with a valid twilio registered phone number to access features.
3. Set up your profile with emergency contacts.
4. Explore features like geofence monitoring, health chatbot, and real-time alerts.


