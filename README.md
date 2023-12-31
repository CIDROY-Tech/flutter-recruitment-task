# Flutter Recruitment Task

This task is designed to assess your skills in Flutter application development and testing. You are required to build a Flutter application that fetches and displays a list of Pokémon. Users should be able to tap on a list item to navigate to a detailed view of the selected Pokémon, complete with images on both screens.

To fetch pokemon details you can use `StubbedPokemonApi` class which can be found in `packages/data/lib/src/data_base.dart`. You can import this package to your main application to use the given class.

```yaml
...

dependencies:
  data_layer:
    path: packages/data_layer

...
```

## Task Description

### Application Features:

- **Listing Screen:** Display a scrollable list of Pokémon. Each list item should present at least the name of the Pokémon.
- **Detail Page:** Upon tapping a list item, the app should navigate to a detailed information page for that Pokémon, showing more data, including images.
- **State Management:** Use the BLoC pattern for managing application state.
- **Localization:** Prepare the app for localization with the Flutter Intl package.
- **Networking:** Fetch Pokémon data from an API.
- **Testing:** Write unit and widget tests to ensure the application's reliability.

### Technical Requirements:

- Utilize the following recommended packages to achieve the functionality:
  1. `freezed` for immutability and exhaustive pattern matching.
  2. `flutter_bloc` for implementing the BLoC pattern.
  3. `flutter_intl` for internationalization.

### Evaluation Criteria:

- Code quality and readability.
- Application architecture.
- Implementation of state management.
- Functionality according to the task description.
- Test coverage for critical parts of your application.

## Setup Instructions

To get started with the development, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `flutter pub get` to install all the necessary dependencies.
4. Run `flutter pub get` inside the directory `packages/data/`
5. Open your preferred IDE and start building the application.

Make sure you have Flutter installed and set up on your development machine. For detailed instructions on setting up Flutter, visit the official [Flutter installation guide](https://flutter.dev/docs/get-started/install).

## Submission Guidelines

Please ensure your final submission includes:

- The source code of the application.
- A `README.md` file with setup and run instructions.
- Any necessary documentation to understand your design decisions and architecture.
- A list of completed features and any known issues or unimplemented parts of the application.

Good luck with your task! We are excited to see your innovative and efficient solutions.
