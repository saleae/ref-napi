
0.0.8 / 2012-05-12
==================

 - make the `void` type "set()" function be a no-op instead of throwing
 - added some more test cases

0.0.7 / 2012-05-09
==================

 - added the `reinterpret()` function

0.0.6 / 2012-05-09
==================

 - add `alignof` mappings for the types
 - add an `Object` type
 - set the `alignment` property on the built-in types

0.0.5 / 2012-05-09
==================

 - quickly add get() and set() functions
 - use the `PRId64` and `PRIu64` snprintf types

0.0.4 / 2012-05-08
==================

 - README improvements; some API documentation
 - removed some leftover debugging statements

0.0.3 / 2012-05-08
==================

 - added `readCString()` function (to `Buffer.prototype` as well)
 - added `writeCString()` function (to `Buffer.prototype` as well)
 - added an `allocCString()` function
 - removed the `Utf8String` type; moved it to node-ffi
 - made `ref.NULL` be a 'void' type

0.0.2 / 2012-05-05
==================

 - Added missing includes for Linux, etc.

0.0.1 / 2012-05-04
==================

 - Initial release