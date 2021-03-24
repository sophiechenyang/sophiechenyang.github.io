# Javascript 

## String methods

**Template strings** are created with the backtick character. It can span multiple lines and supports interpolation
```
`Hi there! 
My name is ${name} and
I am learning ${language}`; 
```

[string.startsWith(searchString)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/startsWith) returns true when a strinng starts with the substring\
[string.endsWith(searchString)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith) returns true when a string ends with the substring\
[strinng.trim()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trim) removes additional spaces from the beginning and the end of a string

```javascript
const phoneNumber = "+103123456";
phoneNumber.startsWith("+"); //true
phoneNumber.startsWith("10"); //false
```

## Numbers
Convert from a number to string: [value.toString()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toString)
Convert from string to number: [Number.parseInt()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/parseInt)

```javascript
answer.toString(); // "42"
Number.parseInt("42", 10); //42 The second argument is radix. 
//Radix of 10 means we're using the decimal system)
```
