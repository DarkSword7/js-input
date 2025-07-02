# js-input-prompt

A simple, Promise-based async input function for Node.js — inspired by Python's `input()` function.

> Ideal for use in CLI applications and interactive scripts using `async/await`.

---

## 📦 Installation

```bash
npm install js-input-prompt
🚀 Usage
js
Copy
Edit
const input = require("js-input-prompt");

(async () => {
  const name = await input("Enter your name: ");
  console.log(`Hello, ${name}!`);
})();
```
### 🔍 Features
Easy to use with async/await

Works like Python’s input() function

Built on Node.js readline module

Lightweight, zero dependencies

### 🧠 Example: Inside a Loop
```
const input = require("js-input-prompt");

(async () => {
  while (true) {
    const answer = await input("Type something (or 'exit' to quit): ");
    if (answer.toLowerCase() === 'exit') break;
    console.log(`You said: ${answer}`);
  }
})();
```

### 📄 License
MIT License

### ✨ Author

Ashutosh Tiwari
[GitHub](https://github.com/darksword7/js-input) • [NPM](https://www.npmjs.com/package/js-input)
