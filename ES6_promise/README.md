# ES_PROMISE

This project explores the concept of Promises in ECMAScript 6 (ES6) and how to handle asynchronous operations effectively in JavaScript. Promises are a fundamental part of ES6 and provide a cleaner, more readable way to work with asynchronous code compared to traditional callbacks.

## Resources

To complete this project, you can refer to these resources:

- [JavaScript Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)
- [Understanding JavaScript Promises](https://developers.google.com/web/fundamentals/primers/promises)
- [Promise API Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

## Learning Objectives

By the end of this project, you should be able to:

- Understand what Promises are and how they handle asynchronous operations
- Describe the states of a Promise (pending, fulfilled, rejected)
- Explain how to create and use Promises in ES6
- Chain Promises using `.then()` and `.catch()`
- Handle errors in asynchronous operations with `.catch()`
- Work with `Promise.all()` and `Promise.race()` for handling multiple promises

## Requirements

- Platform: Ubuntu 18.04 LTS
- Node.js Version: 12.11.x
- Editor Options: `vi`, `vim`, `emacs`, `Visual Studio Code`
- File Requirements: All files should end with a new line and use the `.js` extension
- Testing: Jest Testing Framework
- Linting: ESLint with specific rules provided
- Dependencies: Install project dependencies with `npm`

## Setup

### 1. Install Node.js 12.11.x

Run the following commands in your home directory:

```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
nodejs -v  
npm -v       
