 <h1 align="center">Smart Utility Toolkit</h1>

<p align="center">
  A modular JavaScript and Node.js project featuring practical utilities and core Node.js functionality.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Node.js-Runtime-green?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Project Status" />
</p>

---

## Overview

Smart Utility Toolkit is a JavaScript-based project developed using Node.js. It combines multiple command-line utilities and demonstrates the practical implementation of JavaScript fundamentals and built-in Node.js modules.

The project includes mathematical operations, random dice generation, file management, number checking, and a basic HTTP server.

## Key Features

- **Even Number Checker:** Determines whether a number is even using a reusable JavaScript module.
- **Calculator:** Performs addition, subtraction, multiplication, and division.
- **Dice Roller:** Generates random dice outcomes using the Node.js Crypto module.
- **File Manager:** Creates, reads, updates, and deletes files using the File System module.
- **HTTP Server:** Handles basic routes such as Home, About, and Contact.
- **Modular Architecture:** Organizes functionality into separate JavaScript files for better code management.

## Technology Stack

| Technology | Description |
| --- | --- |
| JavaScript | Core programming language |
| Node.js | JavaScript runtime environment |
| HTTP Module | Handles server requests and responses |
| File System Module | Performs file operations |
| Crypto Module | Generates random dice values |

## Project Structure

```text
smart_utility_toolkit/
│
├── modules/
│   └── isEven.js
│
├── app.js
├── calculator.js
├── dice.js
├── fileManager.js
├── server.js
└── README.md
```

## Getting Started

### Prerequisites

- Node.js installed on your system.
- Visual Studio Code or any code editor.
- Basic knowledge of JavaScript.

### Installation

Clone the repository:

```bash
git clone https://github.com/aradhana-bit/smart_utility_toolkit.git
```

Navigate to the project directory:

```bash
cd smart_utility_toolkit
```

No external dependencies are required.

## Running the Project

| Utility | Command |
| --- | --- |
| Even Number Checker | `node app.js` |
| Calculator | `node calculator.js add 10 5` |
| Dice Roller | `node dice.js` |
| File Manager | `node fileManager.js` |
| HTTP Server | `node server.js` |

### HTTP Server Routes

After starting the server, visit `http://localhost:3000`.

| Route | Functionality |
| --- | --- |
| `/` | Welcome Page |
| `/about` | About Page |
| `/contact` | Contact Page |
| Other Routes | 404 Error Response |

## Concepts Implemented

- JavaScript Functions and Arrow Functions
- CommonJS Modules
- Module Import and Export
- Command-Line Arguments
- Conditional Statements and Switch Cases
- Node.js File System Operations
- HTTP Server Creation
- Asynchronous Programming and Callbacks
- Random Number Generation

## Project Objectives

- Strengthen JavaScript programming fundamentals.
- Understand the Node.js runtime environment.
- Explore built-in Node.js modules.
- Implement practical command-line utilities.
- Develop modular and reusable code.

## Purpose

This project was developed as a practical learning exercise to explore JavaScript and Node.js concepts through real-world utility programs.

---

<p align="center">
  <strong>Developed by S. Aradhana</strong>
  <br />
  <a href="https://github.com/aradhana-bit">GitHub Profile</a>
  <br />
  <sub>Building, Learning and Creating with Code.</sub>
</p>
