# Library_TorkUtils
A quick library that aids in interfacing with BlocklandJS. Very WIP.

## Installation
Download/clone the repo (and make sure that it isn't in a zip), then, move it to your Add-Ons/ directory. To use it, call
```js
import('Library_TorkUtils').then((mod) => {TorkUtils = mod;});
```

All functions exported by this module (byteLength, ToUint8, FromUint8, isObject, filePath, fileBase, getFieldCount, getField, getFields) will now be available for use on the TorkUtils object.
