# Contributing Guidelines

I appreciate your interest in contributing. Before you get started, please take a moment to read through these guidelines.

# Setting Up Your Environment

## Installing Flutter

If you haven't already, you'll need to install Flutter on your local machine. Follow the official installation guide for your operating system:

- [Install Flutter](https://flutter.dev/docs/get-started/install)

## Configuring VS Code

We recommend using Visual Studio Code (VS Code) as your code editor for Flutter development. To set up your VS Code environment for this project:

1. Install the Flutter and Dart extensions for VS Code.
   - [Flutter Extension](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)
   - [Dart Extension](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code)

2. Open the project folder in VS Code.

3. VS Code should automatically detect your Flutter SDK installation. If not, you can configure it manually by selecting the Flutter SDK path in the settings.

Now, you're ready to start contributing!

# Contributing Process

## Selecting an Issue

1. Browse our [Issue Tracker](https://github.com/SzilvasiPeter/grocery_shopping_template/issues) to find an issue you'd like to work on. Issues may include bug reports, feature requests, or other improvements.

2. Comment on the issue to let others know you'd like to work on it, or open a new issue if you have a new idea or find a bug.

## Forking the Repository

1. Fork this repository to your GitHub account by clicking the "Fork" button at the top-right corner of the repository page.

2. Clone your forked repository to your local machine:

```bash
git clone https://github.com/yourusername/your-repository.git
```

## Making Changes

Clean the project by running the following command in your project directory:

```bash
flutter clean
```

Before making changes, it's a good practice to clean the Flutter project to ensure a fresh start. 

Next, you need to create a new Flutter project within the existing repository, navigate to the root directory of your project and run:

```bash
flutter create .
```

This command initializes a new Flutter project in the current directory.

To run the Flutter application locally, use the following command:

```bash
flutter run
```

This command builds and runs the Flutter app on the default device or emulator.

Please follow the Flutter's coding styles while making changes to the project. The Flutter extension will help you spot bugs and coding style issues.

> Helpful commands: The `dart fix --apply` to fix source code, the `dart format` to format idiomatically, and the `flutter test` to run unit tests.

## Creating a Pull Request

1. Commit your changes with a clear and descriptive commit message:

```bash
git commit -m "Your descriptive commit message here"
```

3. Push your changes to your forked repository:

```bash
git push origin your-branch-name
```

4. Visit your forked repository on GitHub and click the "New Pull Request" button.
   
5. Select the base branch (usually "main" or "master") and your branch with changes.
   
6. Provide a clear title and description for your pull request, explaining what changes you made.
   
7.  Submit the pull request.

Thank you for contributing to the Flutter application! I'll review your pull request and provide feedback as needed. Happy coding!