# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    var variable 
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
      console.log(var);
     ```
     
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
     ` == operator returns a true values are equal and false if they are not. useulay used with if statements.`
    * How to use the `"==="` operator: 
     `=== operattor retunes true if both values are equal and type- match, false if otherwise`
    * How to use the `">"` operator: 
        `greater than sign returns true is value of the left is large than the value on the right` 
   * ##### How to write an if Statements 
      ```javascript
       if (condition){
       function;
       }
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
       var name = function(){
       logic;
        };
       ```
    * This is the other way to declare a function: 
      ```javascript
       function name(argument){
       logic;
       }
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        function(num){
           num = num + 4;
            return num
           }
        ```
    * This is a function that capitalizes any word: 
        ```javascript
       function(word){
       word.toUpperCase();
       return word;
       }
       ```
    * We use functions because:
     the aim is DRY code, take away repetitvie tasks. 
* ### datatypes:
  * ##### Strings
    * A string is: 
        way to organice any combinatios of words
    * You can capitalize a string by: 
        ```javascript
       var string;
       string.toUppercase();
       ```
    * Concatentation is: 
        `puting one or more string togother`
    * An example of concatenation: 
         ```javascript
        `'this' + " " + is + 'concatanated' + " " + 'string'`
       ```
  * ##### Numbers:
    * The `%` operator is: retuens the remaindr of a division 
    * Here is an example of the `%` operator in use: the remaindr of 5 /2  is 1 
       ```javascript
       remainder = 5 % 2
       ```
  * ##### Arrays:
    * An index is: the postion of a spesific element in an array.
    * You can access an element in an array like this: Arr[i];
    * Map:
      * .map is an array method that: 
         runs a specific function over the entire arrey.
      * An example of map is: 
        ```javascript
          Arrey.map(arreymethod(input))
         ```
    * Filter:
      * .filter is an array method that: 
          ` creates a new arrey with elmements that pass the passed condition `
      * An example of filter is: 
        ```javascript
           var array 
           var newarray = array.filter(condition);
         ```
    * forEach:
      * .forEach is an array method that: 
         ` performs a specific opration on each element of the array `
      *  An example of forEach is: 
         ```javascript
           array.forEach(function(index){
            });
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           objeect.property
        ```
* ### loops
     *   how to make for loop 
         ```javascript
          for(i=0; (condition logic); iterator){
          logic;
          }
          ```
* ### Querying the DOM
  ```javascript
   document.queryselect() or document.queryslectall();
  ```
* ### Creating a new element in the DOM
  ```javascript
     var = new;
     document.createElemnt(new);
  ```
* ### Appending a new element to the DOM
  ```javascript
      var = new;
     document.createElemnt(new);
     document.appendElemnt(new);
  ```
* ### Updating the style properties
  ```javascript
   document.style.property = new property,
  ```
