# JSON to HTTP Query string
> This package allows you to convert JSON to Http query string
[![npm](https://img.shields.io/npm/v/github-buttons)](https://www.npmjs.com/package/json-to-http-query-string)

## Getting Started
To install the module, run the following in the command line:
```bash
npm i json-to-http-query-string --save
```
Use within your application with the following line of JavaScript:
```js
const jsonToQuery = require('json-to-http-query-string');
//or 
//import jsonToQuery from 'json-to-http-query-string'

jsonToQuery({
  foo: "hi",
  bar: {
    blah: [1, 2, 3],
    blah2: 123
  }
}) 
//foo=hi&bar%5Bblah%5D%5B0%5D=1&bar%5Bblah%5D%5B1%5D=2&bar%5Bblah%5D%5B2%5D=3&bar%5Bblah2%5D=123
```
