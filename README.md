# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    // var name = 'Sam';
       var age = 25;
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    // console.log(name);
       console.log(age);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `use it in an if statement. it will return 1 if the statement is true
       if( x == y){console.log("true")} else{console.log("false");
    * How to use the `"==="` operator: 
       `write a definition `
    * How to use the `">"` operator: 
        `when the value of side 1 is larger than the value from the other side`
   * ##### How to write an if Statements 
      ```javascript
        // if(number > arr.length){console.log('you win');}
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        // function eBook(){
        }
       ```
    * This is the other way to declare a function: 
      ```javascript
        // var getGrades = function(variable){
        return variable;}
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        // function calculate(){
        return value + 4;
        }
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        // getName.toUpperCase;
       ```
    * We use functions because:
     `when we need to capitalize letters `
* ### datatypes:
  * ##### Strings
    * A string is: 
        `is traditionally a sequence of characters, either as a literal constant or as some kind of variable. `
    * You can capitalize a string by: 
        ```javascript
        // var cap = name.toUpperCase;
       ```
    * Concatentation is: 
        `function is used to join two or more strings together `
    * An example of concatenation:
         ```javascript
        // str.concat
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `write a definition `
    * whaen you want to devide
       ```javascript
        // if(number %2){
        }return number.
       ```
  * ##### Arrays:
    * An index is: The index is the position of an item inside an array, a list,
    * You can access an element in an array like this: (code)
    * Map:
      * .map is an array method that: 
         `is used to apply a function on every element in an array. A new array is then returned. }); newArr — the new array that is returned `
      * An example of map is: 
        ```javascript
           //var officersIds = officers.map(function (officer) { return officer.id });
         ```
    * Filter:
      * .filter is an array method that: 
          `creates a new array with all elements that pass the test implemented by the provided function `
      * An example of filter is: 
        ```javascript
           // The syntax. var newArray = array.filter(function(item) { return condition; });
         ```
    * forEach:
      * .forEach is an array method that: 
         `is an Array method that we can use to execute a function on each element in an array `
      *  An example of forEach is: 
         ```javascript
           // array.forEach(function(currentValue, index, arr), thisValue)
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           // var person[{ name :'Anoud', age:23}]
           function info (){ return person.name}
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           // for(i =0; i<x.length;i++)
          ```
* ### Querying the DOM
  ```javascript
   // Document.querySelector()
  ```
* ### Creating a new element in the DOM
  ```javascript
   //Document.createElement()
  ```
* ### Appending a new element to the DOM
  ```javascript
   // Create a text node node.appendChild(textnode);
  ```
* ### Updating the style properties
  ```javascript
   // document.getElementById("xyz").style.padding-top = "10px";
  ```
