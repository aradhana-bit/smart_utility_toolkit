# Smart Utility Toolkit

A modular command-line utility project built with JavaScript and Node.js. It brings together practical programming utilities and examples of core Node.js modules in one organized toolkit.

## Overview

Smart Utility Toolkit demonstrates how small, focused JavaScript programs can solve everyday tasks while introducing important Node.js concepts. The project includes number checking, arithmetic operations, random dice rolls, file-system operations, and a basic HTTP server.

## Key Features

- **Even Number Checker:** Checks whether a given number is even using a reusable module.
- **Calculator:** Performs addition, subtraction, multiplication, and division through command-line arguments.
- **Dice Roller:** Generates three random dice outcomes using Node.js's crypto module.
- **File Manager:** Demonstrates file creation, reading, appending, and deletion with the file-system module.
- **HTTP Server:** Runs a basic server with home, about, and contact routes, along with a 404 response.
- **Modular Structure:** Keeps the number-checking utility in a separate module for reuse.

## Technology Stack

| Technology | Purpose |
| --- | --- |
| JavaScript | Application logic and utilities |
| Node.js | JavaScript runtime |
| Node.js built-in modules | HTTP, file-system, and cryptographic operations |

## Project Structure

```text
smart_utility_toolkit/
├── modules/
│   └── isEven.js
├── app.js
├── calculator.js
├── dice.js
├── fileManager.js
├── server.js
└── README.md
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your system.
- A terminal or command prompt.

### Clone the Repository

```bash
git clone https://github.com/aradhana-bit/smart_utility_toolkit.git
cd smart_utility_toolkit
```

No external npm packages are required. The project uses Node.js built-in modules.

## Usage

Run each utility from the project root.

### Even Number Checker

```bash
node app.js
```

The example checks whether the number `8` is even.

### Calculator

Syntax:

```bash
node calculator.js <operation> <number1> <number2>
```

Examples:

```bash
node calculator.js add 10 5
node calculator.js subtract 10 5
node calculator.js multiply 10 5
node calculator.js divide 10 5
```

Supported operations: `add`, `subtract`, `multiply`, and `divide`.

### Dice Roller

```bash
node dice.js
```

Generates three random dice results.

### File Manager

```bash
node fileManager.js
```

Creates `test.txt`, reads its contents, appends additional text, reads the updated file, and deletes it.

### HTTP Server

Start the server:

```bash
node server.js
```

Open `http://localhost:3000` in your browser.

| Route | Response |
| --- | --- |
| `/` | Welcome message |
| `/about` | About page |
| `/contact` | Contact page |
| Any other route | 404 response |

Stop the server with `Ctrl + C`.

## Concepts Implemented

- JavaScript functions, arrow functions, and modules
- CommonJS `require()` and `module.exports`
- Command-line arguments with `process.argv`
- Conditional statements and switch-case
- Node.js `crypto`, `fs`, and `http` modules
- File handling and asynchronous callbacks
- Creating and handling HTTP requests and responses

## Project Objectives

This project is intended to strengthen foundational JavaScript and Node.js skills through small, practical programs. It also provides a simple structure that can be extended with additional utilities.

---

<p align="center">
  <strong>Built to practice JavaScript. Designed to grow with every utility.</strong>
  <br />
  <sub>Developed by <a href="https://github.com/aradhana-bit">S. Aradhana</a></sub>
</p>
