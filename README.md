# firstpacketmodule


## Installation 
```sh
npm install firstpacketmodule --save

```

## Usage

### JavaScript

```javascript
var firstmodule = require('firstpacketmodule');
var output = firstmodule.helloWorldFunction();
console.log(output);

```
```sh
Output should be 'Hello World - ALL'

```



### AMD
```javascript
exports.helloWorldFunction= function()
{
	console.log("Hello World - ALL");
};
```

## Test 
```sh
npm run test
```
