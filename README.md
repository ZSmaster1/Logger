# Installation
```
npm install @zs_master1/logger
```

# Usage

```js
const Logger = require('@zs_master1/logger');
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