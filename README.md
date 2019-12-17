# log-filejs

A logger for just about everything.

[![NPM](https://img.shields.io/npm/v/log-filejs.svg?style=flat-square)](https://nodei.co/npm/log-filejs/)[![NPM](https://img.shields.io/npm/dm/winston.svg?style=flat-square)](https://nodei.co/npm/log-filejs/)[![NPM](https://img.shields.io/travis/winstonjs/winston/master.svg?style=flat-square)](https://nodei.co/npm/log-filejs/)[![NPM](https://img.shields.io/david/winstonjs/winston.svg?style=flat-square)](https://nodei.co/npm/log-filejs/)

[![NPM](https://nodei.co/npm/log-filejs.png)](https://nodei.co/npm/log-filejs/)

# Install

```console
$ npm i log-filejs --save
```

# Usage

```js
const logFile = require('log-filejs')

logFile.info('Hello again distributed logs')
// - Write to all logs with level `info` and below to `combined.log` 

logFile.error('error 404 not found')
// - Write all logs error (and below) to `error.log`
```