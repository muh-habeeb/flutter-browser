# mbrowser

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## strructure

```
    voyage/
    ├── lib/
    │ ├── main.dart # Main entry point of the application
    │
    │ ├── providers/ # State management for themes, bookmarks, etc.
    │ │ ├── theme_provider.dart # Theme management provider
    │ │ └── history_provider.dart # Manages browser history
    │
    │ ├── models/ # Data models for bookmarks and history
    │ │ ├── bookmark.dart # Bookmark model
    │ │ └── history_entry.dart # History entry model
    │
    │ ├── screens/ # Screens/pages for the app
    │ │ ├── home_screen.dart # Main browser screen
    │ │ ├── history_screen.dart # Displays browsing history
    │ │ ├── settings_screen.dart # Settings and theme switching
    │ │ └── bookmarks_screen.dart # Manage bookmarks
    │
    │ ├── services/ # Browser-related utilities and logic
    │ │ ├── url_validator.dart # Utility for validating and normalizing URLs
    │ │ └── local_storage.dart # Handles shared preferences or local storage
    │
    │ ├── widgets/ # Custom reusable widgets
    │ │ ├── url_input_field.dart # A styled text field for entering URLs
    │ │ └── navigation_bar.dart # Bottom navigation for tabs
    │
    │ └── utils/ # General helper functions or constants
    │ └── app_constants.dart # Constants like default URLs and themes
    │
    ├── pubspec.yaml # Dependencies and project configuration
    └── assets/ # Images, icons, fonts, etc.
    ├── icons/
    └── themes/

```
