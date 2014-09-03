# github-linker-registries 
[![Supported npm package][count-npm-image]][count-npm-url] [![Supported bower package][count-bower-image]][count-bower-url] [![NPM version][npm-image]][npm-url]


## Install

```bash
$ npm install --save github-linker-registries
```


## Usage

```javascript
var registries = require('github-linker-registries');
console.log(registries.npm) 
// => {"jquery":"https://github.com/jquery/jquery", "bootstrap":"https://github.com/twbs/bootstrap" ...}

console.log(registries.bower)
// => {"lodash":"https://github.com/lodash/lodash", "async":"https://github.com/caolan/async" ...}
```


## Total supported repositories

npm: 75151

bower: 16982


## License

Copyright (c) 2014 Stefan Buck. Licensed under the MIT license.



[npmjs-url]: https://npmjs.org/package/github-linker-registries
[npmjs-image]: https://badge.fury.io/js/github-linker-registries.svg
[count-npm-url]: https://npmjs.org/
[count-npm-image]: http://img.shields.io/badge/npm-75151-green.svg
[count-bower-url]: https://bower.io/
[count-bower-image]: http://img.shields.io/badge/bower-16982-green.svg
