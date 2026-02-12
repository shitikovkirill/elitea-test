# Quiz CLI

An interactive command-line quiz game for learning JavaScript and Node.js fundamentals.

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Node Version](https://img.shields.io/badge/Node-%3E=18.0.0-brightgreen)

---

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact/Maintainers](#contactmaintainers)

---

## Features
- Interactive CLI quiz game.
- Covers JavaScript basics, Node.js fundamentals, and general programming questions.
- Questions categorized into topics for focused learning.
- Provides explanations for correct answers.

---

## Prerequisites
- Node.js version 18 or higher must be installed. [Download Node.js here](https://nodejs.org/).

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shitikovkirill/elitea-test.git
   cd elitea-test
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

---

## Usage
Start the quiz game:
```bash
npm start
```

### Example Quiz Session
```
Welcome to the Quiz CLI!
Choose a category:
1) JavaScript Basics
2) Node.js Fundamentals
3) General Programming
Enter your choice: 1

Question 1: What keyword is used to declare a constant in JavaScript?
1) var
2) let
3) const
4) define
Enter your answer (1-4): 3
Correct! The 'const' keyword declares a block-scoped constant that cannot be reassigned.
```

To run tests:
```bash
npm test
```

---

## Project Structure
- `index.js`: Entry point of the application.
- `package.json`: Project metadata and scripts.
- `data/questions.json`: Stores categorized quiz questions.
- `src/colors.js`: Utility for CLI color formatting.
- `src/input.js`: Handles user input.
- `src/quiz.js`: Core quiz logic and game flow.

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact/Maintainers
- Maintainer: [Kirill Shitikov](https://github.com/shitikovkirill)
- Feel free to open an issue or contact us for any questions!
