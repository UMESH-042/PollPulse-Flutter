# GDSC-Flutter
# Flutter App Project - Installation Guide for Visual Studio Code

## Figma Design

For reference, you can view the Figma design for this project by clicking [here](https://www.figma.com/file/KAAj6qMlkKJ0HG39omnXkP/Voting-app?type=design&node-id=0%3A1&mode=design&t=w2UcQGJIplv3kSNZ-1).

## Installation

To build and run this Flutter app project in Visual Studio Code on your local machine, follow these steps:

1. Clone this repository using Visual Studio Code:

   - Open Visual Studio Code.
   - Click on the "Settings" icon in the left-bottom sidebar.
   - In the "Settings" panel, click on the Command Palette and select "Git: Clone".
   - Or you can directly open Command Palette using the keyboard shortcut `Ctrl+Shift+P`
   - Enter the repository URL: `https://github.com/UMESH-042/GDSC-Flutter`.
   - Choose a local directory where you want to clone the repository.
   - Click "Clone" to download the project.

   **OR**

   - Open Git Bash (ensure it's installed on your system).
   - Navigate to the directory where you want to clone the repository.
   - Run the following command:
     ```bash
     git clone https://github.com/UMESH-042/GDSC-Flutter
     ```

2. Open the Project:

   - After cloning, Visual Studio Code will automatically detect and open the project.

3. Configure Dependencies:

   - Ensure that you have Flutter and Dart installed on your system. You can download them from the [official Flutter website](https://flutter.dev/docs/get-started/install).
   - Open the project's directory in the terminal and run `flutter pub get` to fetch the project dependencies.

4. Build and Run the App:

   - Once the project is opened in Visual Studio Code, open a terminal inside the project directory.
   - Run `flutter run` to build and run the app.
   - Select your target device (emulator or physical device) if prompted.

5. Wait for the app to build and launch on your selected device.

That's it! You should now have the Flutter app running in Visual Studio Code on your PC. You can make changes to the code and see them reflected in real-time as you save your files.
