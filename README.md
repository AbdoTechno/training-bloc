# training_bloc

A Flutter training project for state management using `flutter_bloc`.

## Overview

`training_bloc` is a starter Flutter application that demonstrates the structure and dependencies for working with BLoC and Cubit state management patterns.

The app currently includes:
- `lib/main.dart` — main application entry point with a default counter UI
- `lib/controllers/bloc/` — BLoC controller structure for counter state
- `lib/controllers/cubit/` — Cubit controller structure for counter state

## Features

- Basic Flutter counter app UI
- Example state management setup using `flutter_bloc`
- Ready for expansion to Bloc and Cubit implementations

## Dependencies

- Flutter SDK `^3.12.0`
- `flutter_bloc: ^9.1.1`
- `cupertino_icons: ^1.0.8`

## Getting Started

1. Install Flutter and ensure it is available on your PATH.
2. In the project root, fetch packages:

   ```bash
   flutter pub get
   ```

3. Run the app on a connected device or emulator:

   ```bash
   flutter run
   ```

## Project Structure

- `lib/main.dart`
  - Main app entry with `MaterialApp` and default counter UI.
- `lib/controllers/bloc/`
  - `counter_bloc.dart`
  - `counter_event.dart`
  - `counter_state.dart`
- `lib/controllers/cubit/`
  - `counter_cubit.dart`
  - `counter_state.dart`

## Notes

- The current `CounterBloc` implementation is scaffolded and needs event-to-state logic.
- The current `CounterCubit` includes the initial state and can be extended with counter update methods.
- This project is configured for mobile and desktop platforms through the standard Flutter project structure.

## Useful Commands

- `flutter analyze` — analyze code for issues
- `flutter test` — run unit and widget tests
- `flutter build apk` — build Android APK
- `flutter build ios` — build iOS app

## License

This project is private and not configured for `pub.dev` publishing.
