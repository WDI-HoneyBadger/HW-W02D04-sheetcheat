# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    // write the syntax
    var name = 'value';
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    // write the syntax
    console.log(variable);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `write a definition `
       compairson value only
    * How to use the `"==="` operator: 
       `write a definition `
       compre data type and value
    * How to use the `">"` operator: 
        `write a definition `
        Returns true if the left operand is greater than the right operand.
        
   * ##### How to write an if Statements 
      ```javascript
        // write the syntax
        if (condition){
       block of code to be executed if the condition is true
       } else{
       block of code to be executed if the condition is false
       }
       ```
      
 * ### functions:
    * How you declare a function: 
      ```javascript
        // write the syntax
        var name = 'value';
       ```
       
    * This is the other way to declare a function: 
      ```javascript
        // write the syntax
        var name = function(parameters){
        statements
        };
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        // write the syntax
        var number = function(num){
        console.log(num + 4)
        };
        
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        // write the syntax
        var word = function(words){
        return words.toUpperCase()
        };
        
       ```
    * We use functions because:
     `write a definition `
     They can be assigned to a value, and they can be passed as arguments and used as a return value.
     
* ### datatypes:
  * ##### Strings
    * A string is: 
        `write a definition `
        is a data type denoted by double or single quotes
    * You can capitalize a string by: 
        ```javascript
        // write the syntax
        
       ```
    * Concatentation is: 
        `write a definition `
        
    * An example of concatenation:
         ```javascript
        // write the syntax
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `write a definition `
       one operand is divided by a second operand
    * Here is an example of the `%` operator in use:
       ```javascript
        // write the syntax
        var areBothEven = function (num1, num2) {
           if (num1 % 2 === 0 && num2 % 2 === 0) {
               return true;
           } else {
               return false;
           }
         };
         areBothEven(2, 4);
       ```
  * ##### Arrays:
    * An index is: (definition)
    is an ordered list of values; these values can be strings, booleans, numbers.
    * You can access an element in an array like this: (code)
    var favoritePlace = ['Riyadh', 'NewYork', 'china'];
    favoritePlace[1]; // => NewYork
    * Map:
      * .map is an array method that: 
         `write a definition `
      * An example of map is: 
        ```javascript
           // write the syntax
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
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           // write the syntax
           var myBicycle = {
          color: "brown",
          model: "DL165",
          make: "Raleigh Competition",
          year: 1976,
          accelerate: function () {
              console.log("Zoom zoom!");
} }
var bicyclemMake = myBicycle.make;
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           // write the syntax
           for (initialization; condition; finalExpression){
           // A block of code.
           }
          ```
* ### Querying the DOM
  ```javascript
   // write the syntax
   document.querySelector('varabie');
  ```
* ### Creating a new element in the DOM
  ```javascript
   // write the syntax
   we will need to use three step process;
   1. we will use the createElement() method.
   2. add content to the element using the innerHTML or textcontent properites.
   3.add the content by useing appendChil() method.
   var newlistItem = document.creatElement('li');
   newListItem.textContent = 'Jalapenos';
  ```
* ### Appending a new element to the DOM
  ```javascript
   // write the syntax
   document.querySelector('ul').appendChild(newListItem);
  ```
* ### Updating the style properties
  ```javascript
   // write the syntax
  
  ```
