# Expense Tracker App

This is a simple expense tracker app developed using Flutter. The app allows users to track their expenses, categorize them, view charts representing expenses, and search through transactions.

## Features

- **Home Screen**: Displays a list of categories and total expenses.
- **Category Screen**: Shows expenses categorized by different categories.
- **Expense Screen**: Displays detailed expenses for a selected category, including charts for visual representation.
- **All Expenses Screen**: Allows users to view all transactions and search through them.
- **Data Persistence**: Expenses are stored locally using SQLite, ensuring data persistence.

## Getting Started

To run the app locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `flutter pub get` to install dependencies.
4. Run the app on a connected device or simulator using `flutter run`.

## Screenshots

[Include screenshots here]

## Usage

1. **Home Screen**: Upon launching the app, you'll see a list of categories and their respective total expenses.

2. **Category Screen**: Tap on a category to view expenses related to that category.

3. **Expense Screen**: In the category screen, tap on a specific expense category to view detailed expenses and charts representing expenses for the last week.

4. **All Expenses Screen**: Accessible through the navigation drawer or any action button, this screen allows you to view all transactions. You can also search through transactions using the search functionality provided.

## Technologies Used

- Flutter: Frontend UI development framework.
- SQLite: Local database for storing expenses data.
- Provider: State management library for managing data flow.
- intl: Package for internationalizing and localizing date and currency formats.
- fl_chart: Library for creating interactive and customizable charts.

## Known Issues

1. Upon initial app launch, the pie chart on the home screen may display 'NaN' values until expenses data is fetched.
2. Deleting an entry doesn't prompt for confirmation, which might lead to accidental deletions.

## Future Improvements

1. Improve error handling and edge case scenarios.
2. Enhance UI/UX for a more intuitive user experience.
3. Implement cloud syncing for data backup and synchronization across devices.
4. Allow users to customize categories and set budgets.

## Contributors

- [Your Name](https://github.com/yourusername)
- [Contributor Name](https://github.com/contributorusername)

Feel free to contribute by submitting bug fixes, feature enhancements, or suggestions via pull requests or by opening issues. We welcome your feedback!
