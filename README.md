# 💸 Loan Calculator
A responsive React-based loan calculator that computes monthly EMI, total payment, and interest using user input, with real-time updates and data persistence via local storage.

# Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Available Scripts](#available-scripts)
- [Deployment](#deployment)
- [Future Enhancements](#future-enhancements)
- [notes](#notes)
- [Acknowledgements](#acknowledgements)
- [License](#license)

# Introduction
The Loan Calculator is a web-based application built using React that enables users to easily calculate their monthly loan payments (EMI), total repayment amount, and interest payable. Designed with a clean and responsive interface, this tool helps users make informed financial decisions by providing real-time results based on loan amount, interest rate, and loan tenure inputs. Leveraging React Hooks for state management and SCSS for styling, the app ensures smooth interactivity and modern design. It also utilizes local storage to retain user inputs for convenience. Ideal for personal or educational use, this project showcases core React concepts in a practical scenario.

# Features

- 🔢 Real-time loan and EMI calculation
- 🎨 Clean, responsive UI styled using SCSS
- 💾 Saves previous user inputs using LocalStorage
- ⚛️ React functional components with hooks
- 🧠 Input validation for reliable calculations

# Technologies Used

- React (via Create React App)
- React Hooks (`useState`, `useEffect`)
- SCSS (`node-sass`)
- LocalStorage API
- HTML5 / CSS3

# Setup Instructions

1. **Clone or Download** this repository:
    ```bash
    git clone https://github.com/your-username/loan-calculator-react.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd loan-calculator-react
    ```

3. **Install dependencies**:
    ```bash
    npm install
    ```

4. **Start the development server**:
    ```bash
    npm start
    ```

5. Open your browser at `http://localhost:3000`.

# Available Scripts

| Command         | Description                    |
| --------------- | ------------------------------ |
| `npm start`     | Starts the development server  |
| `npm run build` | Builds the app for production  |
| `npm test`      | Runs unit tests (if available) |

# Deployment

To build the project for production:

```bash
npm run build
```

The optimized static files will be output to the `build` directory, ready to be deployed.

# Future Enhancements

* Add graphs for EMI breakdown
* Support currency conversion
* Add user authentication for saved calculations

# Notes

- Make sure Node.js and npm are installed before running this project.
- This app was bootstrapped using Create React App.
- Documentation is also included as a `.docx` file in the root directory.

# Acknowledgements

- React documentation – [https://reactjs.org](https://reactjs.org)
- Create React App – [https://create-react-app.dev](https://create-react-app.dev)
- Icons and design inspiration from open-source communities

# License

This project is open-source and available under the [MIT License](LICENSE).
