This NPM [package](https://www.npmjs.com/package/json_comparision) will compare two json objects and return boolean values based on packages same are not.

__INPUT__: It will take two objects as a parameter

__OUTPUT__: boolean value 

__EXAMPLE__:

const {jsonCompare} = require('json_comparision')

const obj1 = {"a":1, "b":{"c":1, "d":1 }} 
const obj2 = { "b":{"d":1, "c":1 }, "a":1}

__jsonCompare(obj1,obj2)__ 

__true__

const {jsonCompare} = require('json_comparision')

const obj1 = {"a":1, "b":{"c":1, "d":1 }} 
const obj2 = { "b":{"d":2, "c":1 }, "a":1}

__jsonCompare(obj1,obj2)__

__false__


