# Flixtube-Movies-Tv-Shows-App

flutter android and windows movie app that scrap movies links from egybest and akwam web sites using dio package and get movie image and description from tmdb api

# Download App For Android

<a  href="https://github.com/mano1997max/Flixtube-movies-tv-shows-app/raw/main/Pharaohs%20Tube%20-%20android%20apk/app-release_v1.1.0%2B1.apk" >
v1.1.0+1 Download Now
</a>

# Download App For Windows
<a  href="https://www.mediafire.com/folder/e4ty0pl0xx8wf/flixtube" >
v1.1.0+1 Download Now
</a>

# installation

in cmd run
`flutter pub get`
to install packages

## iOS

If you're unable to view media loaded from an external source, you should also add the following:

```
<key>NSAppTransportSecurity</key>
<dict>
  <key>NSAllowsArbitraryLoads</key>
  <true/>
</dict>
```

## android

To load media/subitle from an internet source, your app will need the INTERNET permission.
This is done by ensuring your <project root>/android/app/src/main/AndroidManifest.xml file contains a uses-permission declaration for android.permission.INTERNET:

```
<uses-permission android:name="android.permission.INTERNET" />
```

## design pattern

DDD design pattern
with get_it dependancy injection with injectable_generator

## packages

```
dependencies:
  window_size:
    git:
      url: git://github.com/google/flutter-desktop-embedding.git
      path: plugins/window_size
   bloc: ^7.0.0
   carousel_slider: ^4.0.0
   cookie_jar: ^3.0.1
   cupertino_icons: ^1.0.2
   dartx: ^0.7.1
   dartz: ^0.9.2
   desktop_window: ^0.4.0
   dio: ^4.0.0
   dio_cookie_manager: ^2.0.0
   flutter_bloc: ^7.0.1
   flutter_custom_tabs: ^1.0.2
   freezed: ^0.14.2
   get_it: null
   google_fonts: ^2.1.0
   html: ^0.15.0
   cached_network_image: ^3.0.0
   http: ^0.13.3
   injectable: ^1.4.1
   inview_notifier_list: ^2.0.0
   path_provider: ^2.0.2
   provider: ^5.0.0
   url_launcher: ^6.0.6
   uuid: ^3.0.4
   flutter_widget_from_html: ^0.6.1
   build_runner: ^2.0.4
   freezed_annotation: ^0.14.2
   injectable_generator: ^1.4.1
```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
