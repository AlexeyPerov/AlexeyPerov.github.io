[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Example Apps

## Flutter Examples

* [LogKeeper](https://github.com/AlexeyPerov/Flutter-Log-Keeper-Tool) is a tool for storing logs that generates links to them after saving. 
Our applications automatically upload logs to it when errors are detected, and the resulting links are easier to share and attach to tasks than when using log files. 
[LogKeeper](https://github.com/AlexeyPerov/Flutter-Log-Keeper-Tool) is made for iOS/Android/Web/Server with Flutter/Dart using Bloc pattern and Firebase Firestore. 
It also demonstrates the usage of Dart on the backend and sharing code within a server and a client.

* [Notes](https://github.com/AlexeyPerov/Flutter-Notes) is a simple notes management app built with Flutter (iOS/Android/Web). 
It is based on [Async Redux](https://pub.dev/packages/async_redux) and Firebase Firestore.

## Android JetPack Compose Examples

* [LogKeeper](https://github.com/AlexeyPerov/Flutter-Log-Keeper-Tool) client for an Android built with JetPack Compose and Firestore.
See [LogKeeperCompose here](https://github.com/AlexeyPerov/LogKeeper-JetPackCompose)

* WIP [Notes](https://github.com/AlexeyPerov/Flutter-Notes) built using JetPack Compose
See [NoteCompose here](https://github.com/AlexeyPerov/NotesCompose)

## iOS SwiftUI Examples

* [LogKeeper](https://github.com/AlexeyPerov/Flutter-Log-Keeper-Tool) client for an iOS built with SwiftUI, Redux, Swinject, SPM and Firestore.
See [LogKeeperSwiftUI here](https://github.com/AlexeyPerov/LogKeeperSwift)

# Tools

## Unity Tool to Find Assets Dependencies

Unfortunately, Unity Editor allows you to find usages of an asset in Scene only.
In order to find all assets references you need custom scripts which scan .meta files.

This tool is one of them.
See [Unity Dependencies Hunter](https://github.com/AlexeyPerov/Unity-Dependencies-Hunter)

## Pulse Auto ID Generator WebHook for monday.com task manager

monday.com lacks a feature of custom pulse id generation. See [feature request](https://community.monday.com/t/custom-numbering-of-pulses/855/35)

Until the functionality is implemented, we use [this WebHook tool](https://github.com/AlexeyPerov/Monday.com-Auto-ID-generator) based on Firebase, AWS Lambda and Node.js
