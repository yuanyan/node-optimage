node-optimage
===

Image optimizer, PNG and JPEG image compress on OS X, Linux, FreeBSD and Windows.

## Install

Install with [npm](https://npmjs.org/package/optimage): `npm install --save optimage`

## Example usage

```js
var optimage = require('optimage');

optimage({
    inputFile: "test.png",
    outputFile: "test.min.png"
  }, function(err, res){

    // res.inputFile
    // res.outputFile
    // res.saved
});
```

## License

MIT.
