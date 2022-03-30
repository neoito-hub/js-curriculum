# Strings

## **Challenges (5)**
### Challenge 1

```
Store the name of a President in a variable 'name'
```
<details>
  <summary>Hint</summary>
Text data in JS is stored as strings. There is no separate type for single character

## **How to initialize string**

Strings can be enclosed within either single quotes, double quotes or backticks:

  ```js
    let first = 'single-quoted';
    let second = "double-quoted";
    let third = `backticks`;
  ```

</details>

### Challenge 2

```
Store the number of characters of 'name' in a variable 'numberOfCharactersInName' 
```
<details>
  <summary>Hint</summary>

## **Properties of string**

String has property `.length` which returns the number of characters. Note that length is a property and not a [method or function](#).

  ```js
    let third = 'Properties of strings';
    let numberOfCharacters = third.length; // 9
  ```

</details>


### Challenge 3

```
Store the third and fourth characters of name in variables 'thirdCharacter' and 'fourthCharacter' 
```
<details>
  <summary>Hint</summary>

## **Accessing characters**
To get the character at position use square brackets [pos] or call the method str.charAt(pos). The first character starts from the zero position.

  ```js
    let text = 'Characters';
    let firstCharacter = text[0]; // C

    // last character
    let lastCharacter = text[text.length - 1]; // s
  ```

</details>

### Challenge 4

```
Print the name in all uppercase.
Print the name in all lowercase.
```
<details>
  <summary>Hint</summary>

## **Methods of strings**

To change the case strings have `.toLowerCase()` and `.toUpperCase()` methods

  ```js
    let text = 'Characters';
    text.toLowerCase();

    text.toUpperCase();
  ```

</details>


### Challenge 5

```
Print the last four characters from name in all uppercase.
```
<details>
  <summary>Hint</summary>

## **Methods of strings**

To access parts of strings there are three methods `.slice(start [, end])`, `.substring(start [, end])`, `.substr(start [, length])`

Note: slice returns the part of the string from `start` to (but not including) `end`.
  ```js
    let text = 'Characters';
    text.slice(2,4); // ar
  ```
  

</details>





## **References**

[What is a string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

