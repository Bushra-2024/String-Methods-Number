# String-Methods-Number
An understandable explanation of string methods and numbers in JavaScript.

## Strings

<img src="https://dmitripavlutin.com/what-is-string-in-javascript/cover.png">
Strings are useful for holding data that can be represented in text form. 

## Creating strings

```js 
let string1 = "A string primitive";
let string2 = 'Also a string primitive';
let string3 = `Yet another string primitive`;
```

<img src="https://phpforever.com/wp-content/uploads/2021/03/Useful-String-Methods-In-JavaScript..png">


## String Methods in JavaScript:


Strings in JavaScript are sequences of characters. JavaScript provides many built-in methods to manipulate strings.



charAt()

Description: Returns the character at a specified index in a string.
```js
Example: let str = "Hello";
console.log(str.charAt(1)); // "e"
```

at():

Description: Returns the character at a specified index, allowing negative indices to count from the end.
```js
Example: let str = "Hello";
console.log(str.at(-1)); // "o"
```

concat():

Description: Joins two or more strings and returns a new concatenated string.
```js
Example: let str1 = "Hello"; let str2 = "World";
console.log(str1.concat(" ", str2)); // "Hello World"
```

trim():

Description: Removes whitespace from both ends of a string.
```js
Example: let str = " Hello ";
console.log(str.trim()); // "Hello"
```


includes():

Description: Checks if a string contains a specified substring, returning true or false.
```js
Example: let str = "Hello";
console.log(str.includes("e")); // true
```

indexOf():

Description: Returns the index of the first occurrence of a specified substring, or -1 if not found.
```js
Example: let str = "Hello";
console.log(str.indexOf("e")); // 1
```

lastIndexOf():

Description: Returns the index of the last occurrence of a specified substring, or -1 if not found.
```js
Example: let str = "Hello World";
console.log(str.lastIndexOf("o")); // 7
```

replace():

Description: Replaces the first occurrence of a specified substring with another string.
```js
Example: let str = "Hello World";
console.log(str.replace("World", "JavaScript")); // "Hello JavaScript"
```

replaceAll():

Description: Replaces all occurrences of a specified substring with another string.
```js
Example: let str = "Hello World World";
console.log(str.replaceAll("World", "JavaScript")); // "Hello JavaScript JavaScript"
```

substring():

Description: Extracts a part of a string between two specified indices.
```js
Example: let str = "Hello World"; console.log(str.substring(0, 5)); // "Hello"
```

slice():

Description: Similar to substring(), but it allows negative indices to start from the end of the string.
```js
Example: let str = "Hello World";
console.log(str.slice(0, 5)); // "Hello"
```

toString():

Description: Returns a string representing the specified object.
```js
Example: let num = 123;
console.log(num.toString()); // "123"
```

split():

Description: Splits a string into an array of substrings, using a specified delimiter.
```js
Example: let str = "Hello World";
console.log(str.split(" ")); // ["Hello", "World"]
```

toLowerCase():

Description: Converts all characters in a string to lowercase.
```js
Example: let str = "Hello";
console.log(str.toLowerCase()); // "hello"
```

toUpperCase():

Description: Converts all characters in a string to uppercase.
```js
Example: let str = "hello";
console.log(str.toUpperCase()); // "HELLO"
```



![Useful Number Methods in JavaScript](Download![number](https://github.com/user-attachments/assets/591eb440-2e9e-45c1-bc52-ee4a9da70bef)
s/number.jpg)



## Number Methods in JavaScript:
