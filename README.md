# LVskripts 

> **JavaScript with Latvian syntax** — write, run, and transpile JavaScript using Latvian keywords.

[![npm version](https://img.shields.io/npm/v/lvskripts?color=cb3837&logo=npm)](https://www.npmjs.com/package/lvskripts)
![Syntax](https://img.shields.io/badge/syntax-Latvian-9e3039)
![VS Code Extension](https://img.shields.io/badge/VS%20Code-LVskripts-007ACC?logo=visualstudiocode)

---

##  Features

- **Latvian Syntax** — Write familiar JavaScript logic using intuitive Latvian keywords.
- **Direct Execution** — Run `.lv` files directly from the command line.
- **Two-Way Transpilation** — Compile LVskripts to standard JavaScript, or reverse-transpile existing `.js` files into LVskripts.
- **Editor Support** — Syntax highlighting and autocompletion via the VS Code extension.

---

## Installation

Install LVskripts globally via npm:

```bash
npm install lvskripts -global
```

---

##  Usage

| Action | Command | Description |
| :--- | :--- | :--- |
| **Run** | `lvskripts -run tests.lv` | Execute an LVskripts file directly |
| **Compile** | `lvskripts -compile tests.lv` | Transpile LVskripts code to JavaScript |
| **Reverse** | `lvskripts -reverse tests.js` | Transpile JavaScript code to LVskripts |

---

##  Example

Here is a side-by-side comparison printing odd numbers from an array:

### JavaScript
```js
const cipari = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

for (let i of cipari) {
    if (i % 2 === 1) {
        console.log(i);
    }
}
```

### LVskripts
```js
konstante cipari = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

priekš (mainīgais i no cipari) {
    ja (i % 2 === 1) {
        printēt(i);
    }
}
```

---

##  Syntax

See [**`sintakse.md`**](./sintakse.md) for the complete list of reserved keywords.

---

## 🧩 Visual Studio Code Extension

Install the **LVskripts** extension from the **VS Marketplace** to enable:
- 🎨 Syntax highlighting
- ⚡ Code autocompletion