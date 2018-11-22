# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    var name = 'Aisha' ;
    var age = 26;
    // write the syntax

     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    console.log(name );
    // write the syntax
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `the value is equal`
    * How to use the `"==="` operator: 
       `must be totally same and from same type`
    * How to use the `">"` operator: 
        ` less than  `
   * ##### How to write an if Statements 
      ```javascript
      if(i % 2 === 0) {
    console.log(`${i} is an even number`);
    }
        // write the syntax
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
       var firstName = function( name ){
       consol.log(name);
       }
        // write the syntax
       ```
    * This is the other way to declare a function: 
      ```javascript
        // write the syntax
        function lengthOfWord(word) {
  return word.length;
}
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        // write the syntax
        var add = function ( num1){
         return num1 +=4 ;
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        // write the syntax
        toUpperCase();
       ```
    * We use functions because:
     `value can be passed into functions and used within the function `
* ### datatypes:
  * ##### Strings
    * A string is: 
        `text value `
    * You can capitalize a string by: 
        ```javascript
        // write the syntax
        toUpperCase();
       ```
    * Concatentation is: 
        `Collect the strings to be concatenated `
    * An example of concatenation:
         ```javascript
        // write the syntax
        "Say hello " + 7 + " times fast!"
       ```
  * ##### Numbers:
    * The `%` operator is: 
       ` remaing number from dived `
    * Here is an example of the `%` operator in use:
       ```javascript
        // write the syntax
        if(i % 2 === 0) {
    console.log(`${i} is an even number`);
    }
       ```
  * ##### Arrays:
    * An index is: (definition)
    * You can access an element in an array like this: (index[0])
    * Map:
      * .map is an array method that: 
         `he map() method creates a new array with the results of calling a provided function on every element in the calling array.`
      * An example of map is: 
        ```javascript
           // write the syntax
           var array1 = [1, 4, 9, 16];

// pass a function to map
const map1 = array1.map(x => x * 2);

console.log(map1);
// expected output: Array [2, 8, 18, 32]

         ```
    * Filter:
      * .filter is an array method that: 
          `The filter() method creates a new array with all elements that pass the test implemented by the provided function `
      * An example of filter is: 
        ```javascript
           // write the syntax
           ar words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];

const result = words.filter(word => word.length > 6);

console.log(result);
// expected output: Array ["exuberant", "destruction", "present"]
         ```
    * forEach:
      * .forEach is an array method that: 
         `The forEach() method executes a provided function once for each array element `
      *  An example of forEach is: 
         ```javascript
           // write the syntax
           ar array1 = ['a', 'b', 'c'];

array1.forEach(function(element) {
  console.log(element);
});

// expected output: "a"
// expected output: "b"
// expected output: "c"
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           // write the syntax
           objectName.property
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           // write the syntax
           for (var i = 0; i <= 10; i++) {
  // console.log(i * 9);
  console.log(`${i} * 9 = ${i * 9}`);
}
          ```
* ### Querying the DOM
  ```javascript
   // write the syntax
   document.querySelector(".class");
  ```
* ### Creating a new element in the DOM
  ```javascript
   // write the syntax
   var newPTag = document.createElement('p');
  ```
* ### Appending a new element to the DOM
  ```javascript
   // write the syntax
     resultSection.appendChild(newPTag);

  ```
* ### Updating the style properties
  ```javascript
   // write the syntax
   animal.style.bottom = 6 +'px';
  ```
