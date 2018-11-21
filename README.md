# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    // write the syntax
   
-numbers, eg. 123, 120.50 etc.
-Strings of text e.g. "This text string" etc.
-Boolean e.g. true or false.
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    // write the syntax
     -console.log();
     
    
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       ` abstract comparisoر، converts the operands to the same type before making the comparison.`
    * How to use the `"==="` operator: 
       `a strict comparison operator, the objects being compared must have the same type.
       Two Boolean operands are strictly equal if both are true or both are false.`
    * How to use the `">"` operator: 
        `write a definition `
   * ##### How to write an if Statements 
      ```javascript
        // write the syntax
        
       - if (condition) {
    block of code to be executed if the condition is true
}
example: if (hour < 18) {
    greeting = "Good day";
}

       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        // write the syntax
        -A function is a group of statements that together perform a task. In other words, it's a block of reusable JSstatment.
     
    * This is the other way to declare a function: 
      ```javascript
        // write the syntax
         -var product="   ";
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        // write the syntax
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        // write the syntax
        -your string'.replace(/\b\w/g, function(l){ return l.toUpperCase() })
// => 'Your String'.

       ```
    * We use functions because:
     `write a definition `
* ### datatypes:
  * ##### Strings
    * A string is: 
        `write a definition `
        -strings of characters can be for example letters and symbols.
    * You can capitalize a string by: 
        ```javascript
        // write the syntax
        - .toUpperCase()
       ```
    * Concatentation is: adding two strings together 
       
    * An example of concatenation:
    "Say hello " + 7 + " times fast!"
    ’Say hello 7 times fast!’`
         ```javascript
        // write the syntax
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `write a definition `
    * Here is an example of the `%` operator in use: Divides left-hand operand by right-hand operand and returns remainder.
    
       ```javascript
        // write the syntax
       ```
  * ##### Arrays:
    * An index is: - An array in JavaScript is a type of global object that is used to store data. Arrays consist of an ordered collection or list containing zero or more datatypes, and use numbered indices starting from 0 to access specific items
    * You can access an element in an array like this: (code)
    * Map:
      * .map is an array method that: 
         `write a definition `
      * An example of map is: 
      -var numbers = [1, 4, 9];
var roots = numbers.map(Math.sqrt);
// roots is now [1, 2, 3]
// numbers is still [1, 4, 9]
        ```javascript
           // write the syntax
           -array.map(function(currentValue, index, arr), thisValue)
         ```
    * Filter:
      * .filter is an array method that: 
          `write a definition `
      * An example of filter is: 
        ```javascript
           // write the syntax
         ```
    * forEach:
      * .forEach is an array method that: 
         `write a definition `
      *  An example of forEach is: 
         ```javascript
           // write the syntax
           -var newArry=array.filter(function(iteam));
         ```

   * ##### objects
     * How to access a property  
     -var waterBottle ={
     color:'seafom',
     capcity:1,
     straw: true,
     owner: 'trevor'
     }
     console.log(waterbottle.owner) <<<< to acces 
     
        ```javascript
           // write the syntax
           ^
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           // write the syntax
              -for (var i=0; i<...,...; i++)
          ```
* ### Querying the DOM
  ```javascript
   // write the syntax
   -element = document.querySelector(selectors);
  ```
* ### Creating a new element in the DOM
  ```javascript
   // write the syntax
   -var para = document.createElement("p"); 
   ^ creates a new <p> element
  ```
* ### Appending a new element to the DOM
  ```javascript
   // write the syntax
   -var node = document.createTextNode("This is a new paragraph.");
   ^must create a text node first.
  ```
* ### Updating the style properties
  ```javascript
   // write the syntax
   -document.getElementById(id).style.property = new style
  ```
