# NerdyNotes - Markdown Notes for Developers, by

A dedicated note-taking app designed specifically for developers, featuring markdown support, code syntax highlighting, and GitHub integration.

## Features

### Core Features

- **Clean, Minimalist Design**: Focused on readability and usability with a modern UI
- **Markdown Support**: Write and format notes using markdown syntax
- **Code Syntax Highlighting**: Add code snippets with automatic syntax highlighting
- **Tags Organization**: Organize notes with custom tags and colors
- **Full-Text Search**: Quickly find notes with powerful search functionality
- **Light & Dark Themes**: Switch between light and dark mode for comfortable reading
- **Pin Important Notes**: Keep critical notes at the top of your list
- **Archive Notes**: Move less important notes to archive

### Premium Features

- **GitHub Integration**: Sync notes with GitHub repositories
- **Unlimited Code Highlighting**: Support for all programming languages
- **Custom Themes**: Personalize the app appearance
- **Note Collaboration**: Share and collaborate on notes with others
- **No Ads**: Ad-free experience

## Architecture

NerdyNotes is built with a clean architecture approach:

- **Presentation Layer**: UI components, screens, and widgets
- **Domain Layer**: Business logic, entities, and use cases
- **Data Layer**: Data sources, repositories, and models

## Technical Stack

- **Flutter**: Cross-platform UI framework
- **Riverpod**: State management solution
- **SQLite**: Local database for notes storage
- **GitHub API**: Integration for note syncing
- **flutter_markdown**: Markdown rendering
- **flutter_highlight**: Code syntax highlighting

## Project Structure

```
lib/
├── core/
│   ├── constants/
│   ├── errors/
│   ├── themes/
│   └── utils/
├── data/
│   ├── datasources/
│   ├── models/
│   └── repositories/
├── domain/
│   ├── entities/
│   ├── repositories/
│   └── usecases/
├── presentation/
│   ├── common_widgets/
│   ├── pages/
│   └── providers/
└── main.dart
```

## Getting Started

### Prerequisites

- Flutter SDK (version 3.10.0 or higher)
- Dart SDK (version 3.0.0 or higher)
- Android Studio or VS Code with Flutter extensions

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/nerdy_notes.git
```

2. Navigate to the project directory:
```bash
cd nerdy_notes
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Flutter](https://flutter.dev/) - UI framework
- [Riverpod](https://riverpod.dev/) - State management
- [GitHub API](https://docs.github.com/en/rest) - GitHub integration
- [flutter_markdown](https://pub.dev/packages/flutter_markdown) - Markdown rendering
- [flutter_highlight](https://pub.dev/packages/flutter_highlight) - Code highlighting