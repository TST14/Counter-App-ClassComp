# Counter-App-ClassComp
A simple counter application built using React class components. This app allows users to increment and decrement a counter value.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)

## Features

- Increment the counter value
- Decrement the counter value
- Display the current counter value

## Demo

You can try the live demo [here](https://counter-app-class-comp-wine.vercel.app/).

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/TST14/Counter-App-ClassComp.git
    cd counter-app-classcomp
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Usage

- Click the **Increment** button to increase the counter value by 1.
- Click the **Decrement** button to decrease the counter value by 1.

## Code Overview

### CounterApp.js

This is the main component of the application. It uses a class component to manage the state of the counter and handle increment and decrement actions.

- **State Variables**:
  - `count`: Stores the current counter value.

- **Functions**:
  - `increment`: Increments the counter value by 1.
  - `decrement`: Decrements the counter value by 1.

- **Render Method**:
  - Displays the current counter value and buttons to increment and decrement the counter.

### index.js

This is the entry point of the application. It renders the `CounterApp` component inside a `StrictMode` wrapper.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
