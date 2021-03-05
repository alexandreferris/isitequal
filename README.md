# isitequal

[![Project Size](https://img.shields.io/github/repo-size/alexandreferris/isitequal)](https://www.npmjs.com/package/isitequal) [![Project Downloads](https://img.shields.io/npm/dt/isitequal)](https://www.npmjs.com/package/isitequal) [![Project License](https://img.shields.io/npm/l/isitequal)](https://www.npmjs.com/package/isitequal)




### Description
Started with the idea to create an extension function for Any* objects to verify the equality of two Any* objects, such as:

```
var string = "dummyString"
var resultTrue = string.isItEqual("dummyString") // true
var resultFalse = string.isItEqual("anotherDummyString") // False
```

But due to the lack of knowledge of the developer (in this case, it is me) to create an extension function, another approach was done, such as just having a function that compares both Any* objects with `===` ([You can read about Equality comparisons and sameness here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness))

So, the end result is basically:
```
npm install isitequal
----
var iie = require('isitequal')

var dummy = "dummy"
var dummyToBeCompared = "dummy"

var result = iie.isItEqual(dummy, dummyToBeCompared)
``` 
