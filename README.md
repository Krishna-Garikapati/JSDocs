# 📘 JSDoc Documentation Practice

## 📌 Overview

This project demonstrates how to use **JSDoc** to document JavaScript code and generate structured HTML documentation. It includes examples of documenting functions, parameters, return types, and generating documentation using the JSDoc CLI.

---

## 🧠 What I Learned

* Writing structured comments using JSDoc (`/** ... */`)
* Documenting functions with `@param` and `@returns`
* Improving code readability and maintainability
* Generating HTML documentation from code comments
* Using JSDoc for better IntelliSense and type hints in VS Code

---

## 🔧 Technologies Used

* JavaScript
* JSDoc
* pnpm

---

## 📁 Project Structure

```
JSDocs/
├── src/
│   ├── login.js
├── out/                 # Generated JSDoc documentation
└── README.md
```

---

## ⚙️ Setup & Installation

### 1. Install Dependencies

```
pnpm install
```

### 2. Install JSDoc (if not installed)

```
pnpm add -D jsdoc
```

---

## 🚀 Generate Documentation

### Run JSDoc

```
pnpm dlx jsdoc src --recurse
```

### Output

Documentation will be generated in:

```
out/index.html
```

Open this file in a browser to view the documentation.

---

## ✍️ Example JSDoc Usage

```js
/**
 * Logs in a user using email and password
 * @param {string} email - User email address
 * @param {string} password - User password
 * @returns {Promise<boolean>} Returns true if login is successful
 */
async function loginUser(email, password) {
  // logic
}
```

---

## 💡 Key Benefits of JSDoc

* Improves code readability
* Provides better IntelliSense in VS Code
* Helps in debugging and maintenance
* Enables automatic documentation generation
* Supports team collaboration
---

## 📌 Conclusion

JSDoc is a powerful tool for documenting JavaScript code. It helps developers write clean, maintainable, and self-explanatory code while also enabling automatic documentation generation.

---

