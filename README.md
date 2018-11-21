# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    // write the syntax
    var variableName = value;
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    // write the syntax
    console.log(variableName);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `write a definition `:
       
       ```=> '"=="' This operator called '"equality"' which check the values of two variable.```
    * How to use the `"==="` operator: 
       `write a definition `:
       
       ```=> '"==="' This operator called '"trequality"' which check the values of two variable and their types which need to be the same.```
    * How to use the `">"` operator: 
        `write a definition `:
        
       ``` => This operator is carrot or '"Larger than"' which checks between two values to see which is the bigger value.```
   * ##### How to write an if Statements 
      ```javascript
        // write the syntax
        if (condition) {
        code block;
        }
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        // write the syntax
        function functionName (parameter) {
        code block;
        } 
       ```
    * This is the other way to declare a function: 
      ```javascript
        // write the syntax
            var functionName = function (parameter) {
        code block;
        }
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        // write the syntax
        function functionName (parameter) {
        return parameter + 4;
        }
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        // write the syntax
          function functionName (parameter) {
        return parameter.toUpperCase();
        }
       ```
    * We use functions because:
     `write a definition `:
     
     ```To performs a task or calculates a value.```
* ### datatypes:
  * ##### Strings
    * A string is: 
        `write a definition `:
        
        ``` String is a data type used in programming, and used to represent text rather than numbers. ```
    * You can capitalize a string by: 
        ```javascript
        // write the syntax
        a method called '"toUpperCase();"'
       ```
    * Concatentation is: 
        `write a definition `:
        
        ``` Concatentation is an operation to join two strings or more into one string variable. ```
    * An example of concatenation:
         ```javascript
        // write the syntax
        variableName = '"stringValue1"' + '"stringValue2"'
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `write a definition `:
       
       ``` modulo is an arithimetic operator which calculates the remainder of a quotient after division. ```
    * Here is an example of the `%` operator in use:
       ```javascript
        // write the syntax
        if (variableName % 2 === 0){
        code here;
        }
       ```
  * ##### Arrays:
    * An index is:
    ``` the location number of the element inside the array.```
    * You can access an element in an array like this:
    ``` arrayName[index] = etc...```
    * Map:
      * .map is an array method that: 
         `write a definition `:
         
        ``` 'The Map object holds key-value pairs and remembers the original insertion order of the keys. Any value (both objects and primitive values) may be used as either a key or a value.' ```
         
      * An example of map is: 
        ```javascript
           // write the syntax
           var variableName = arrayName.map(function(parameter){
           code here;
           })
         ```
    * Filter:
      * .filter is an array method that: 
          `write a definition :'
          
       ```   'The filter() method creates a new array with all elements that pass the test implemented by the provided function.' ```
      * An example of filter is: 
        ```javascript
           // write the syntax
           var variableName = arrayName.filter(function(parameter){
           code here;
           })
         ```
    * forEach:
      * .forEach is an array method that: 
         `write a definition `
        ``` 'forEach is an Array method that we can use to execute a function on each element in an array.' ```
         
      *  An example of forEach is: 
         ```javascript
           // write the syntax
           arrayName.forEach(function(parameter){
           code here;
           })
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           // write the syntax
           objectName.propertyName = value;
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           // write the syntax
           for (var i =0; i < variable(or Array).length; i++) {
           code here;
           }
          ```
* ### Querying the DOM
  ```javascript
   // write the syntax
   var objectName = document.querySelector('elementName');
  ```
* ### Creating a new element in the DOM
  ```javascript
   // write the syntax
    var objectName = document.createElement('elementName');
  ```
* ### Appending a new element to the DOM
  ```javascript
   // write the syntax
  objectName.appendChild(variableName that stores element);
  ```
* ### Updating the style properties
  ```javascript
   // write the syntax
   ObjectName.style.property = value
  ```
