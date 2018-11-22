# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    var name = 'nada';
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    console.log(code);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `We use it when we want to compare variables value and don't care of type `
    * How to use the `"==="` operator: 
       `We use it when we want to compare if the variables have same value and type `
    * How to use the `">"` operator: 
        `To compare if one variable is greater then anothar varable example:`
        ` var1 > var2 `
   * ##### How to write an if Statements 
      ```javascript
        var i = 0;
        if (var < 5){
           console.log(var);
        }
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        function nameOfFunction() {
            // code of the function operation
        };
       ```
    * This is the other way to declare a function: 
      ```javascript
        var nameOfFunction = function() {
            // code of the function operation
        };
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        var num = 2;
        function addFour() {
            num = num + 4;
        }
        ```
    * This is a function that capitalizes any word: 
        ```javascript
       function capitalize(word) {
            word.toUpperCase();
       }
       capitalize('hello');
       ```
    * We use functions because:
     `We use the function when we what to do spcific operation/s only when the function call. `
* ### datatypes:
  * ##### Strings
    * A string is: 
        `Sequence of charecters. `
    * You can capitalize a string by: 
        ```javascript
        var name = 'nada';
        name.toUpperCase();
       ```
    * Concatentation is: 
        `adding two strings togather. `
    * An example of concatenation:
         ```javascript
         var myName = 'Nada';
         console.log('My name is: ' + myName);
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `we call it remainder give us the remainder from the division operation`
    * Here is an example of the `%` operator in use:
       ```javascript
       // This will give us 1
        console.log(15 % 2);
       ```
  * ##### Arrays:
    * An index is: the position of array element
    * You can access an element in an array like this: (arrayName[i])
    * Map:
      * .map is an array method that: 
         `access an objects and alwayes return array`
      * An example of map is: 
        ```javascript
           var pizzaToppings = [ 
           'pepperoni',
           'cheese',
           'sardines'
           ];
           var pizzaToppingsCaps = pizzaToppings.map(function(topping){
           return topping.toUpperCase();
           })
         ```
    * Filter:
      * .filter is an array method that: 
          `Get some of array element with spcific properties `
      * An example of filter is: 
        ```javascript
           var newArray = arrayname.filter(function(parameter){
           .
           .
           })
         ```
    * forEach:
      * .forEach is an array method that: 
         `Access all array elements and output all or some of array elements with, forEach can’t be used with object `
      *  An example of forEach is: 
         ```javascript
           var newArray = arrayname.foreach(function(parameter) {
           .
           .
           })
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           var car = { 
           name: 'lumbergeni',
           year: 2016,
           speed: 349
           }
           
           // Access a property
           car.year = 2017;
        ```
* ### loops
     *   how to make for loop 
         ```javascript
         // This wi iterate 10 times
           for (var i = 0; i < 10; i++){
               console.log('i = ',i);
           }
          ```
* ### Querying the DOM
  ```javascript
   document.querySelector('.className');
   document.querySelector('#idName');
   document.querySelector('tagName');
   document.querySelectorAll('.className');
   document.querySelectorAll('#idName');
  ```
* ### Creating a new element in the DOM
  ```javascript
   var pTag = document.createElement('p');
  ```
* ### Appending a new element to the DOM
  ```javascript
   document.appendChild(pTag);
  ```
* ### Updating the style properties
  ```javascript
   span.style.color = 'red';
   span.style.fontSize = '25px';
  ```
