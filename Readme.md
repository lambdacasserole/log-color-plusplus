# Log.js (with added vitamins for pep and vigor)

This package is based on [log-color-optionaldate.js](https://github.com/lambdacasserole/log-color-optionaldate.js) which is a fork of [log-color.js](https://github.com/futoase/log-color.js) which it itself a fork of [Log.js](https://github.com/tj/log.js).

## Installation

Install using [npm](https://www.npmjs.com/):

```
$ npm install log-color-plusplus
```

## Example

Can be used in a similar fashion to [Log.js](https://github.com/tj/log.js).

Code snippet:

```
var Log = require('log');
var log = new Log('info');
log.info('Sent a message to the user@example.com');
```

### Enabling Color

Enable color like this:

```
var Log = require('log-color-plusplus');
var log = new Log({ level: 'debug', color: true, date: false, wrap: 50 });
log.warning('Failed to send a message to the user@example.com');
```

## Log Levels

The same log levels are available as in [Log.js](https://github.com/tj/log.js):

```
log.alert('alert');
log.critical('critical');
log.error('error');
log.warning('warning');
log.notice('notice');
log.info('info');
log.debug('debug'); 
```
