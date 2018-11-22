# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    // write the syntax
    var variableName = 'the value';
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    // write the syntax
    console.log('some sext (Optional)' , variableName);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `Compare the value of variables and check if they are equal to each other. Returns true if so. (note: does'nt care about the type)  `
    * How to use the `"==="` operator: 
       `Compare variables and check if they are equal to each other in value and type at the same time. `
    * How to use the `">"` operator: 
        `Compare between variables and check if one is greater then another. If true, some condition will be excuted.  `
   * ##### How to write an if Statements 
      ```javascript
        // write the syntax
        if (condition1) { 
          // Code to be executed if condition1 is true
        } else if (condition2) { 
          // Code to be executed if condition1 is false and condition2 is true
        } else { 
          // Code to be executed if no conditions above are met
           } 
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        // write the syntax
        var functionName = function(parameter){
        //body of function
        }
        
        functionName(value);  // to call the function
       ```
    * This is the other way to declare a function: 
      ```javascript
        // write the syntax
         function functionName(parameter){
        //body of function
        }
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        // write the syntax
        function addsFour(num){
        return num + 4;
        }
        
        console.log(addFour(2)); //output 6
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        // write the syntax
        
        function capitalize(word){
        return word.toUpperCase();
        }
        
        console.log(capitalize('Web Development immersive is fun')); // output WEB DEVELOPMENT IMMERSIVE IS FUN
        
       ```
    * We use functions because:
     `write a definition `
* ### datatypes:
  * ##### Strings
    * A string is: 
        `Collection of charecters, in other words, it's a text. (Note: should be surrounded by quotes: "Noorah") `
    * You can capitalize a string by: 
        ```javascript
        // write the syntax
        using toUpperCase(); method
        example: 
        var ga = 'General Assembly';
        console.log(ga.toUpperCase());  // output GENERAL ASSEMBLY.
       ```
    * Concatentation is: 
        `Concatenate and join two strings or more into a single string. `
    * An example of concatenation:
         ```javascript
        // write the syntax
        var name = 'Noorah';
        var familyName = 'Alghamdi';
       
       var fullName = name + familyName;
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `Called modulus operator which returns the division remainder. `
    * Here is an example of the `%` operator in use:
       ```javascript
        // write the syntax
        var reminder = 5 % 2;
        console.log(reminder); // output 1
       ```
  * ##### Arrays:
    * An index is: (definition) ` is the position element inside the array.`
    * You can access an element in an array like this: (code)
    ```array[index]```
    * Map:
      * .map is an array method that: 
         `Creates a new array (does'nt change the original) with the results of calling a function for every array element.`
      * An example of map is: 
        ```javascript
           // write the syntax
           
           var names = ['Noorah', 'Shahad' , 'Marwah' , 'Hannan'];
           var capitalNames = names.map(function(name) {
           var capitalizedNames = name.toUpperCase() + '!';
           return capitalizedNames;
            });
            
            // this will return a new array of names with capital letters.
         ```
    * Filter:
      * .filter is an array method that: 
          `Creates an array filled with all array elements that pass the function condition. `
      * An example of filter is: 
        ```javascript
           // write the syntax
            
           var fullTimeEmployees = employees.filter(function(fullTime) {
          return fullTime.status === 'full-time';
          });
         ```
    * forEach:
      * .forEach is an array method that: 
         `Enable us to excute a function for each emelemnt in the array`
      *  An example of forEach is: 
         ```javascript
           // write the syntax
           
            array.forEach(function(arr) {
            console.log(`${arr}`);
             })
          
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           // write the syntax
           object.propertyName ;
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           // write the syntax
           
           for (initialization; condition; finalExpression) { 
           // A block of code.
           } 
           
           //example
           
           for( i = 1 ; i <= 10 ; i++){
            console.log(i);
             }
          ```
* ### Querying the DOM
  ```javascript
   // write the syntax
   var section = document.querySelector('.section');
  ```
* ### Creating a new element in the DOM
  ```javascript
   // write the syntax
    var newPTag = document.createElement('p');
    var newPTagText = document.createTextNode(' new paragraph ');
  ```
* ### Appending a new element to the DOM
  ```javascript
   // write the syntax
    newPTag.appendChild(newPTagText);
    section.appendChild(newPTag);
  ```
* ### Updating the style properties
  ```javascript
   // write the syntax
   
  section .style.backgroundColor = '#a6c4f4';
  ```
