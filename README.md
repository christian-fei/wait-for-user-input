# wait-for-user-input

[![NPM](https://nodei.co/npm/wait-for-user-input.png)](https://npmjs.org/package/wait-for-user-input)

minimal way to wait for user input on the terminal.

handles single character user input. (y/n)

```
async main () {
  const input = await waitForUserInput('do you agree?')
  ...
}
```

## installation

```
npm i wait-for-user-input
```


## usage

### async / await

```
const waitForUserInput = require('wait-for-user-input')

main()

async function main () {
  const response = await waitForUserInput('')
}
```

### promises

```
const waitForUserInput = require('wait-for-user-input')
waitForUserInput('')
.then(userInput => {
  // handle user input
})
```