
# DieRoll App

A simple React Native application that simulates rolling a dice and displays the result.

## Overview

The Dice Roller App is a React Native application that allows users to roll a dice with a single tap. The result of the dice roll is displayed as a number between 1 and 6.

## Features

- Roll a dice with a button press
- Display the result of the dice roll
- Simple and intuitive user interface

## Installation

1. Ensure you have Node.js and npm installed on your machine.
2. Install React Native CLI if you haven't already:
   ```sh
   npm install -g react-native-cli
   ```
3. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/dice-roller-app.git
   ```
4. Navigate to the project directory:
   ```sh
   cd dice-roller-app
   ```
5. Install the dependencies:
   ```sh
   npm install
   ```

## Usage

To run the app on an iOS simulator or Android emulator:

1. For iOS:
   ```sh
   npx react-native run-ios
   ```

2. For Android:
   ```sh
   npx react-native run-android
   ```

Make sure you have an emulator running or a physical device connected.

## Dependencies

- React: `^17.0.2`
- React Native: `^0.64.0`

## Technical Information

### Components

#### App Component

The main component that renders the dice and the roll button. It manages the state for the dice result and handles the logic for rolling the dice.

### State Management

The app uses React's `useState` hook to manage the dice result state. The state is updated whenever the user taps the roll button.

### Styling

The app uses `StyleSheet` from React Native to handle styling. It ensures a consistent look across different platforms.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new features to add.

