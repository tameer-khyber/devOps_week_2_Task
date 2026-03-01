# devOps_week_2_Task: Data Management and Persistent Storage

A Flutter application demonstrating basic state management using `setState` and persistent data storage using the `shared_preferences` package.

## Features

This application contains two built-in demonstration screens accessible via a bottom navigation bar:

### 1. Counter App (State Management Basics)

- A simple counter that increments and decrements a value when the respective buttons are pushed.
- Demonstrates the use of `setState` to immediately reflect widget updates onto the UI.
- The counter value is stored persistently using `SharedPreferences`, meaning it will retain its value even if the app undergoes a restart.

### 2. To-Do List App (Persistent Data Storage & Lists)

- A task list that allows the user to add new tasks.
- Displays added tasks dynamically in a `ListView`.
- Users can delete specific tasks using the trailing delete icon.
- Utilizes `SharedPreferences` to save the list items persistently, meaning they will not be lost upon app restart.

## Getting Started

To run this application, make sure you have the Flutter SDK installed on your system.

1. **Clone or Open the Repository**
2. **Fetch Dependencies**:
   Open a terminal in the project directory and run:

   ```bash
   flutter pub get
   ```

3. **Run the App**:
   You can run the application on any connected emulator or desktop target:

   ```bash
   flutter run
   ```

## Packages Used

- [shared_preferences](https://pub.dev/packages/shared_preferences): Used for saving simple data (like integers and lists of strings) locally on the device.

## Author

Developed as part of an internship task (Task 2) on Data Management and Persistent Storage.
