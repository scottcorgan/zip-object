# zip-object

Create an object from from arrays of keys and values. (Inspired by [lodash's _.zipObject](http://devdocs.io/lodash/index#zipObject))

## Install

```
npm install zip-object --save
```

## Usage

```js
var zipObject = require('zip-object');
var zipped = zipObject(['key1', 'key2'], ['value1', 'value2']);

console.log(zipped.key1); // outpus 'value1'
console.log(zipped.key2); // outpus 'value2'
```

## Run Tests

```
npm install
npm test
```
