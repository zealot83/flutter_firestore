# flutter_firestore

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

It is important to add the following two statements in flutter_firestore/android/app/build.gradle

아래 두 문장을 꼭 flutter_firestore/android/app/build.gradle에 추가해 주어야 합니다.
    
    implementation 'com.google.android.gms:play-services-location:18.0.0'
    
    implementation "io.grpc:grpc-okhttp:1.32.2"
