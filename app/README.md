Overview

This project captures live camera frames, processes them using OpenCV (C++) through JNI, and displays the processed output using OpenGL ES on Android.
This repository also includes a simple TypeScript-based web viewer.

Android App Features
1. Live camera preview 
2. JNI bridge between Kotlin ↔ C++ 
3. Image processing using OpenCV C++ 
4. Grayscale, Gaussian blur, Canny edge detection 
5. OpenGL ES rendering 
6. Toggle Raw ↔ Processed 
7. FPS counter 
8. Export processed frame

Web Viewer

1. Displays a sample processed frame 
2. Shows resolution + FPS 
3. Built with TypeScript

 Repository Structure
/
├── app/
│   ├── src/main/cpp/     # C++ OpenCV + JNI
│   ├── src/main/java/    # Android Kotlin
│   └── CMakeLists.txt
│
├── web/
│   ├── index.html
│   ├── src/app.ts
│   └── tsconfig.json
│
└── README.md

 Build Instructions
Android

Install Android Studio + NDK + CMake

Clone repository

Open project

Connect device & Run

Web Viewer
npm install
npm run build
open web/index.html

📸 Screenshots



✔ Assignment Requirements Covered

OpenCV (C++)
JNI
Camera2 preview
GL rendering
Real-time image processing
Web viewer
Documentation

👤 Author
LAISIRI N M