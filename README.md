# Quiz-CLI

An interactive command-line quiz game for learning JavaScript. This project is designed to help users improve their JavaScript knowledge through engaging and fun quizzes directly from the terminal.

![License](https://img.shields.io/badge/license-MIT-green) ![Node Version](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen)

---

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features
- Interactive CLI-based quiz game
- Multiple quiz categories and customizable question count
- Questions sourced from a JSON file for easy customization
- Styled console output for an enhanced user experience

---

## Prerequisites
- Node.js version 18.0.0 or higher

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shitikovkirill/elitea-test.git
   ```
2. Navigate to the project directory:
   ```bash
   cd elitea-test
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

---

## Usage
Run the quiz game using the following command:
```bash
npm start
```

### Example Quiz Session
```bash
Welcome to the JavaScript Quiz!

Select a category:
1. Basics
2. Advanced
3. Async/Await

Your choice: 1

How many questions would you like to answer? 2

Question 1: What is the output of `console.log(typeof null)`?
1. "null"
2. "object"
3. "undefined"

Your answer: 2
Correct!

Question 2: What is the keyword to declare a variable in JavaScript?
1. "var"
2. "let"
3. "const"

Your answer: 2
Correct!

Congratulations! You completed the quiz.
```

---

## Project Structure
- **index.js**: Main entry point for the CLI quiz game.
- **package.json**: Project metadata and scripts.
- **data/questions.json**: JSON file containing the quiz questions.
- **src/**: Contains source code files:
  - **colors.js**: Utility functions for styling console output.
  - **input.js**: Handles user input and interactions.
  - **quiz.js**: Implements quiz logic and flow.

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and open a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
Maintained by [Kirill Shitikov](https://github.com/shitikovkirill). For questions or feedback, please open an issue in the repository.