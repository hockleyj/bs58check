# bs58smartcheck

[![NPM Package](https://img.shields.io/npm/v/bs58smartcheck.svg?style=flat-square)](https://www.npmjs.org/package/bs58smartcheck)


A straight forward implementation of base58check extending upon bs58 for smartcash


## Example

```javascript
var bs58smartcheck = require('bs58smartcheck')

var decoded = bs58smartcheck.decode('VMcAbMfj44MqqL1rL4cwxTe8NfgcbAGJUhaXb4rNVqKWpNhf4Za6')

console.log(decoded)
// => <Buffer bf ae c5 39 7b 66 d8 86 31 10 bf 6a 84 22 91 43 19 79 96 b2 46 cc 50 24 1d 70 5b 3b b9 5d 97 4e 41 01>

console.log(bs58smartcheck.encode(decoded))
// => VMcAbMfj44MqqL1rL4cwxTe8NfgcbAGJUhaXb4rNVqKWpNhf4Za6
```


## LICSENSE [MIT](LICENSE)
