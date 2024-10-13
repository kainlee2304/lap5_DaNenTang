REPORT  
LAB: Mobile App Development - Xylophone Music App


### Introduction  
This lab report documents the process of developing a simple mobile music application using Flutter. The primary purpose of the report is to demonstrate the usage of open-source Flutter packages, Dart programming concepts, and how to develop a cross-platform mobile app that can play Xylophone sounds. This project is part of a larger course from The App Brewery focused on Flutter development.

### Objectives  
The objectives of this lab are:
1. To learn how to incorporate open-source Flutter libraries into a project.
2. To create a music app that plays Xylophone sounds.
3. To understand how to generate and use repeated widgets in Flutter.
4. To explore Dart programming concepts, including functions with input/output and one-line syntax.

### Methodology  
The development process began with setting up the Flutter environment, including integrating the `audioplayers` package to handle sound playback. The app is designed using a `Column` widget with multiple buttons that each play a distinct sound when pressed. The buttons are styled using Flutter’s `TextButton` widget, and colors were assigned to differentiate the keys. Dart functions were used to manage the logic of sound playback, with each function taking the sound number as an input.

Steps:
1. Install Flutter and set up the development environment.
2. Create a new Flutter project and structure the app.
3. Import the `audioplayers` package for sound playback.
4. Use `Expanded` and `TextButton` widgets to generate the Xylophone keys.
5. Develop a function that plays sound files when a button is pressed.
6. Test the app on both iOS and Android platforms to ensure cross-platform functionality.

### Results  
The result is a fully functional Xylophone app that plays seven different notes when the user interacts with the colored buttons. Below are screenshots of the app running on both Android and iOS devices.



### Discussion  
The Xylophone app successfully meets the objectives by demonstrating how to integrate external Flutter packages, manage sounds, and create repeated user interface elements. One of the major strengths of this project is its simplicity and cross-platform functionality, allowing the app to run on both Android and iOS without changes in the code. However, a limitation is the limited sound file formats that could be supported across platforms. Furthermore, adding more advanced features such as recording functionality or different musical instruments could enhance the app.

Cross-platform mobile development using Flutter offers several strengths, such as reduced development time and consistency across platforms. However, challenges include dealing with platform-specific issues, particularly with hardware interactions.

### Conclusion  
In conclusion, the lab successfully demonstrated how to build a cross-platform Xylophone app using Flutter. The app was built using Dart functions and integrated the `audioplayers` package to handle sound playback. Future work could involve adding more complex functionality, such as multiple instruments or recording features, to enhance user interaction and experience.
