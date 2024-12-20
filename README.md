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


## Number Methods in JavaScript:

1. Math.floor()
Rounds a number down to the nearest integer.
```js
console.log(Math.floor(4.7)); // Output: 4
console.log(Math.floor(-4.7)); // Output: -5
```

2. Math.ceil()
Rounds a number up to the nearest integer.
```js
console.log(Math.ceil(4.1)); // Output: 5
console.log(Math.ceil(-4.1)); // Output: -4
```


3. Math.round()
Rounds a number to the nearest integer.

Values .5 or higher are rounded up, otherwise down.
```js
console.log(Math.round(4.5)); // Output: 5
console.log(Math.round(4.4)); // Output: 4
```

4. Math.abs()
Returns the absolute (positive) value of a number.
```js
console.log(Math.abs(-7)); // Output: 7
console.log(Math.abs(7));  // Output: 7
```

5. Math.max()
Returns the largest value from a list of numbers.
```js
console.log(Math.max(10, 20, 30)); // Output: 30
console.log(Math.max(-10, -20, -30)); // Output: -10
```

6. Math.min()
Returns the smallest value from a list of numbers.
```js
console.log(Math.min(10, 20, 30)); // Output: 10
console.log(Math.min(-10, -20, -30)); // Output: -30
```

7. Math.pow()
Calculates the power of a number: 
base exponent.
```js
console.log(Math.pow(2, 3)); // Output: 8 (2³)
console.log(Math.pow(5, 2)); // Output: 25 (5²)
```

8. Math.sqrt()
Returns the square root of a number.
```js
console.log(Math.sqrt(16)); // Output: 4
console.log(Math.sqrt(2));  // Output: 1.414...
```

9. Math.random()
Generates a random number between 0 (inclusive) and 1 (exclusive).
```js
console.log(Math.random()); // Output: e.g., 0.456 (varies each time)
console.log(Math.random() * 10); // Random between 0 and 10
```

10. Math.NaN (Not a Function, just a value)
Represents a value that is not a valid number. It's not a function, but an indication of an invalid computation.
```js
console.log(0 / 0); // Output: NaN
console.log(Math.sqrt(-1)); // Output: NaN
```
