# Run-sh

## Install
`npm install run-sh`

## Use
```
const sh = require('run-sh');

sh("times").then(function(res) {
  console.log("Current server time:", res.stdout);
});
```