# NDimens

Create an n-dimensional array easily!

## Example

```spwn
ndimens = import ndimens

myArray = ndimens([2,3,4,5], "hello guys") // "hello guys" is the default value

$.print(myArray) // [[[['hello guys','hello guys','hello guys','hello guys',...
$.print(myArray[0][0][0][0]) // "hello guys"
```
