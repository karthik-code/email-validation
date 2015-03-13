#Reg exp

## Introduction ##

Some basics in Regular expressions used in this project are explained here.


## test() ##

The test() method searches a string for a specified value, and returns true or false, depending on the result.

For example,
```
var patt1=new RegExp("e");
document.write(patt1.test("Live to Learn"));
```
It searches for 'e' in the string "Live to Learn", and returns result in Boolean
```
true
```