# micro-settimeout-promise

A super-little (**50 byte**) wrapper for setTimeout as an ES6 Promise, with no dependencies.

```
const wait = require('micro-settimeout-promise')

wait(2500).then(() => 'The world is your slightly delayed oyster')
```
