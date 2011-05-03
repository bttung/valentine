    \  / _. |  _  ._ _|_ o ._   _
     \/ (_| | (/_ | | |_ | | | (/_

JavaScript's Sister, and protector. At 1.5k Valentine provides you with type checking, functional iterators, and basic utility helpers.

NPM users, install it:

    $ npm install valentine

Use it:

    var v = require('valentine');

    v.map(['a', 'b', 'c'], function (letter) {
      return letter.toUpperCase();
    }).join(' '); // => 'A B C'

API
---

<h3>iterators</h3>

  * v.each()
  * v.map()
  * v.every()
  * v.some()
  * v.filter()
  * v.indexOf()
  * v.lastIndexOf()
  * v.reduce()
  * v.reduceRight()

<h3>utility</h3>

  * v.pluck()
  * v.toArray()
  * v.size()
  * v.reject()
  * v.find()
  * v.compact()
  * v.flatten()
  * v.uniq()
  * v.first()
  * v.last()
  * v.keys()
  * v.trim()

<h3>type checking</h3>

  * v.is.fun()
  * v.is.str()
  * v.is.ele()
  * v.is.arr()
  * v.is.num()
  * v.is.bool()
  * v.is.args()
  * v.is.emp()
  * v.is.dat()
  * v.is.nan()
  * v.is.nil()
  * v.is.und()

Ender Support
-------------
Don't have [Ender](http://ender.no.de)? Install it, and don't ever look back.

    $ npm install ender -g

Then build valentine into your package

    $ ender build valentine

Have an existing Ender package? Include it:

    $ ender add valentine

Happy iterating!