# Installation
```
npm install logger
```

# Usage

```js
const Logger = require('logger');
const log = new Logger();

//error
log.error('An error has occurred!');

//warn
log.warn('This is a warning!');

//verbose
log.verbose('This is a verbose message!');

//info
log.info('This is a info message!');
```