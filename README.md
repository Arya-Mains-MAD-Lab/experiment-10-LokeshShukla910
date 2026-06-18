## Name : Lokesh Shukla

## Roll Number : 23EACCA033

## Experiment Title : Image & Video Handling

## Aim : To handle images and videos according to device size.

## Procedure

- Install Flutter SDK
  - Download and install the Flutter SDK from the official website and set up environment variables.
  - Verify installation using:
    ```bash
    flutter doctor
    ```

- Install Android Studio
  - Install Android Studio and configure it with Flutter and Dart plugins.

- Create a New Flutter Project
  - Open Android Studio
  - Click on New Flutter Project
  - Select Flutter Application
  - Enter project name and location
  - Click Finish

- Write the Source Code
  - Open the `main.dart` file and replace the existing code with the given program.
  - The program demonstrates:
    - Loading image from network using Image.network
    - Responsive UI using MediaQuery
    - Dynamic image sizing based on screen dimensions

- Connect Device/Emulator
  - Start an Android emulator or connect a physical device with internet access.

- Run the Application
  - Click Run button or use:
    ```bash
    flutter run
    ```

- Observe the Output
  - The app displays:
    - A network image loaded from https://picsum.photos
    - Responsive resizing based on screen width and height
    - A caption below the image

## Output: A Flutter application displaying a responsive network image with proper scaling using MediaQuery.

- <img width="1919" height="1029" alt="Screenshot 2026-04-14 210735" src="https://github.com/user-attachments/assets/4431bc5b-aaa4-47a9-b2b8-5ad4747a08b2" />

## Conclusion : The experiment was successfully completed by implementing image handling in Flutter using network images and responsive layout techniques with MediaQuery.
