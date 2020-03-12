This package will compare two json objects and return boolean values based on packages same are not.

Input: It will take two objects as a parameter



OutPut: boolean value 

example:

obj1 = {"a":1, "b":{"c":1, "d":1 }}
obj2 = { "b":{"d":1, "c":1 }, "a":1}

jsonCompare(obj1,obj2) will return true

obj1 = {"a":1, "b":{"c":1, "d":1 }}
obj2 = { "b":{"d":2, "c":1 }, "a":1}

jsonCompare(obj1,obj2) will return false
