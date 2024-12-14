# Angel's C++ Program

## Overview
This is a simple C++ application that displays an image and plays a sound. The application uses the Windows API, GDI+ for image rendering, and the Windows Multimedia API for sound playback.

## Files
- `main.cpp`: The main source code file for the application.
- `main.c`: An alternative main source code file for the application.
- `app.exe`: The compiled executable of the application.
- `s.iss`: Inno Setup script for creating an installer for the application.
- `Output/hawktuah.exe`: The output installer executable generated by Inno Setup.
- `readme.md`: This readme file.

## Dependencies
- Windows API
- GDI+ library
- Windows Multimedia API

## Building the Project
To build the project, you need a C++ compiler that supports Windows API and GDI+. You can use Visual Studio to compile the project.

1. Open the project in Visual Studio.
2. Build the solution to generate `app.exe`.

## Running the Application
After building the project, you can run the application by executing `app.exe`. The application will display an image and play a sound.

## Creating an Installer
To create an installer for the application, use the Inno Setup script `s.iss`.

1. Open Inno Setup.
2. Load the `s.iss` script.
3. Compile the script to generate the installer `hawktuah.exe` in the `Output` directory.

## License
This project is licensed under the MIT License.