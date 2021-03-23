# Javascript 

## String methods

**template strings** supports interpolation
```
I am learning ${language}`; //"I am learning Javascript"; 
```

[string.startsWith(searchString)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/startsWith) returns true when a strinng starts with the substring\
[string.endsWith(searchString)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith) returns true when a string ends with the substring\
[strinng.trim()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trim) removes additional spaces from the beginning and the end of a string

```javascript
const phoneNumber = "+103123456";
phoneNumber.startsWith("+"); //true
phoneNumber.startsWith("10"); //false
```
