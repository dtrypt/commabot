# Commabot [![Build Status](https://travis-ci.org/trustinruss/commabot.svg?branch=master)](https://travis-ci.org/trustinruss/commabot) [![Coverage Status](https://coveralls.io/repos/github/trustinruss/commabot/badge.svg?branch=master)](https://coveralls.io/github/trustinruss/commabot?branch=master)

A small library that adds commas to every 3 number places

## Installation
```js
npm install commabot
```

## Usage
```js
var numFormatter = require('commabot');
var formattedNum = numFormatter(123456789); // Output is `123,456,789`
```

## Tests
```
npm test
```

# Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.
