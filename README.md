# micro-settimeout-promise

A super-little (57 byte) wrapper for setTimeout as an ES6 Promise.

```
const wait = require('micro-settimeout-promise')

wait(2500).then(() => 'The world is your slightly delayed oyster')
```
