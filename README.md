# LVskripts 😀
LVskripts is JavaScript with Latvian syntax
# Installation
    npm install lvskripts -global
# Usage
Running LVskripts code:
       
    lvskripts -run tests.lv
Transpiling LVskripts to JavaScript:
       
    lvskripts -compile tests.lv
Transpiling JavaScript to LVskripts:
    
    lvskripts -reverse tests.js
# Syntax
See *sintakse.md* for all reserved keywords
# Example
JavaScript
```
const cipari = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

for (let i of cipari) {
    if (i % 2 === 1) {
        console.log(i);
    }
}
```
LVskripts
```
konstante cipari = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

priekš (mainīgais i no cipari) {
    ja (i % 2 === 1) {
      printēt(i);
    }
}
```
# Visual Studio Extension
Install the 'LVskripts' extension from the VS Marketplace for syntax highlighting and code autocompletion.