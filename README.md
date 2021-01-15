# countChars

Подсчёт количества символов в строке

## Install

```sh
npm install @stanislavkarol/count-chars -S
```

## API

```js
countChars('Тестовая строка') => Function
countChars(varString) => String
```

## Example

```js
const countChars = require("@stanislavkarol/count-chars");

const varString = "Тестовая строка";

const result = countChars(varString);

console.log(result); // {'Т': 1,'е': 1,'с': 2,'т': 2,'о': 2,'в': 1,'а': 2,'я': 1,' ': 1,'р': 1,'к': 1}
```
