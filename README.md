# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
     var name = "muneera";
  * How to console.log the value of a variable: (code)
    ```javascript
    console.log(name);
     ``` 
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator:
    
       `compares only the value for example 
       '5' == 5 
        5 == 5 
       both return true ;`
       
    * How to use the `"==="` operator: 
    
       `is only true if the operands are of the same type and the contents match. 
       '5' === 5 ;
       false
       5 === 5 ;
       true
       `
    * How to use the `">"` operator: 
    
        `5 > 10 return false 
        10 > 5 return true`
   * ##### How to write an if Statements 
      ```javascript
     var name = "muneera";
        if ( name == "muneera"){
        return true ;
        } else { return false; }
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript 
        function nameOfFunction(value){
        }
       ```
    * This is the other way to declare a function: 
      ```javascript
        function sum(a, b) {  
        return a + b; }
        sum(5, 6);           // => 11  
        ([3, 7]).reduce(sum)
        
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        function add(number){
        return number+4  } 
        console.log(add(5)) ;
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        function capWord(word){ 
        return word.toUpperCase(); 
        }  console.log(capWord("muneera")) ;
       ```
    * We use functions because:
     `A function is a subprogram designed to perform a particular task. `
* ### datatypes:
  * ##### Strings
    * A string is: 
        `store a series of characters:`
        
    * You can capitalize a string by: 
        ```javascript
        toUpperCase()
       ```
    * Concatentation is: 
        `` Joining an array of strings OR the sum of numbers
    * An example of concatenation:
         ```javascript
        console.log( firstName + lastName );
        console.log( 3 + 4 );
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `Modulus (division remainder) which is a way to know if the number is odd or even `
    * Here is an example of the `%` operator in use:
       ```javascript
        4 %2 = 0 (even)
        5 %2 = 1 (odd)
        6 % 3 = 2 
        
       ```
  * ##### Arrays:
    * An index is: returns the place of a given element can be found in the array
    * You can access an element in an array like this: arrName[indexNumber];
    * Map:
      * .map is an array method that: 
         `The map() method creates a new array with the results of calling a function for every array element. 
      * An example of map is: 
        ```javascript 
        var names = ["Sara" , "muneera" , "Hana" , "Mohammed"]; 
        var upperNames = names.map(function(arrName){
        return arrName.toUpperCase(); 
        }) 
        console.log(upperNames);
           var finalsupmit = names.map(function(supply) { 
           return supply.toUpperCase(); 
           })
         ```
    * Filter:
      * .filter is an array method that: 
          `method creates a new array with all elements that pass the test implemented by the provided function. `
      * An example of filter is: 
        ```javascript
            var names = ["Sara" , "Muneera" , "Hana" , "Mohammed"];
            var filterNames = names.filter(function(arrName){
            return (arrName[0] == 'M')
            })
            console.log(filterNames);

         ```
    * forEach:
      * .forEach is an array method that: 
         `method executes a provided function once for each array element.`
      *  An example of forEach is: 
         ```javascript
           var names = ["Sara" , "Muneera" , "Hana" , "Mohammed"];
           var eachName = names.filter(function(arrName){
           return (arrName[0] == 'M')
           }) 
           console.log(eachName);
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           objectName.property
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           for (let i = 0; i < array.length; i++) {.......}
          ```
* ### Querying the DOM
  ```javascript
   document.querySelector(".example");
  ```
* ### Creating a new element in the DOM
  ```javascript
   var example = document.createElement("p");
  ```
* ### Appending a new element to the DOM
  ```javascript
   var node = document.createTextNode("This is a new paragraph.");
  ```
* ### Updating the style properties
  ```javascript
   element.style.backgroundColor = "red";
  ```
