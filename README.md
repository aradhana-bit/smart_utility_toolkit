 <h1 align="center">Smart Utility Toolkit</h1>

<p align="center">
  A collection of practical JavaScript utilities built with Node.js to explore core programming concepts, file handling, command-line applications, and HTTP server development.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-Runtime-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
</p>

---

## Overview

Smart Utility Toolkit is a beginner-friendly Node.js project that brings together multiple standalone utilities demonstrating essential JavaScript and backend development concepts.

The project focuses on practical implementation of modules, conditional logic, mathematical operations, random number generation, file system operations, and HTTP server creation.

## Key Features

- **Even Number Checker:** Determines whether a given number is even.
- **CLI Calculator:** Performs addition, subtraction, multiplication, and division.
- **Dice Roller:** Generates random dice values using Node.js crypto.
- **File Manager:** Creates, reads, updates, and deletes files.
- **HTTP Server:** Handles basic routes using Node.js HTTP module.
- **Modular Architecture:** Organizes functionality into separate JavaScript files.

## Technology Stack

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-Runtime-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/HTTP-Server-00599C?style=for-the-badge&logo=serverfault&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-Version_Control-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</p>

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

Make sure you have the following installed:

- Node.js
- Visual Studio Code (or any code editor)
- Basic knowledge of JavaScript

### Installation

1. Clone the repository:

```bash
git clone https://github.com/aradhana-bit/smart_utility_toolkit.git
```

2. Navigate to the project directory:

```bash
cd smart_utility_toolkit
```

## Running the Project

Run each utility independently using Node.js.

**Even Number Checker**
```bash
node app.js
```

**CLI Calculator**
```bash
node calculator.js
```

**Dice Roller**
```bash
node dice.js
```

**File Manager**
```bash
node fileManager.js
```

**HTTP Server**
```bash
node server.js
```

After starting the HTTP server, open:

```text
http://localhost:3000
```

## HTTP Server Routes

| Route | Description |
|---|---|
| `/` | Displays the home page |
| `/about` | Displays the about page |
| `/contact` | Displays the contact page |
| Other routes | Returns a 404 response |

## Concepts Implemented

- JavaScript fundamentals
- Functions and conditional statements
- CommonJS modules (`require` and `module.exports`)
- Node.js built-in modules
- Command-line execution
- Mathematical operations
- Random number generation using `crypto`
- File System operations
- HTTP server and routing
- Error handling and input validation

## Project Objectives

- Strengthen JavaScript programming fundamentals.
- Understand the Node.js runtime environment.
- Practice working with built-in Node.js modules.
- Learn basic backend server development.
- Build practical utilities through hands-on implementation.

## Purpose

This project is developed as a practical learning exercise to strengthen programming fundamentals and gain hands-on experience with JavaScript and Node.js.

---

<p align="center">
  <b>Built with JavaScript and Node.js</b>
</p>

<p align="center">
  Developed by <b>Aradhana</b>
</p>
