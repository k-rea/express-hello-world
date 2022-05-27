# Express demo: Display "Hello World"
## Environment

```bash
node --version # v16.13.1
http --version # 3.2.1
```

## Expressサーバーの立ち上げ

### In the shell

```bash
mkdir express-tutorial
cd express-tutorial
npm init -y
npm install express # "express": "^4.18.1"
```

### ./index.js

```jsx
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send("Hello World!")
})

app.listen(port, () => {
  console.log(`Example app listening on port ${port}`)
})
```

### Create server

```bash
nodo index.js
```

### Check server

```bash
http localhost:3000
```

