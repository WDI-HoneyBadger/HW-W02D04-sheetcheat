# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    var variableName = 'value';
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    console.log(variableName);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `It used for compare only the value of two variable`
    * How to use the `"==="` operator: 
       `It used for compare the value and the type of two variable`
    * How to use the `">"` operator: 
        `It used for compare if the first value is grater than second value return true`
   * ##### How to write an if Statements 
      ```javascript
        if ( 4 > 2 ) {
         return true; 
        } else {
         return false; 
        }
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        function nameOfTheFunction(){
        }
       ```
    * This is the other way to declare a function: 
      ```javascript
        var nameOfTheFunction = function(){
        }
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        function addFour(num){
         return num+ 4;
        }
        console.log(addFour(2)); // output: 6
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        function capitalizes(word){
         return word.toUpperCase();
        }
        console.log(capitalizes('Moroj')); // output: MOROJ
       ```
    * We use functions because:
     `To keep the code clear and DRY!`
* ### datatypes:
  * ##### Strings
    * A string is: 
        `It is series of characters`
    * You can capitalize a string by: 
        ```javascript
        var word = 'Moroj Alharbi';
        console.log(word.toUpperCase()); // output: MOROJ ALHARBI
       ```
    * Concatentation is: 
        `It is used to join two or more strings together.`
    * An example of concatenation:
         ```javascript
        var fName = 'Moroj';
        var lName = 'Alharbi';
        console.log(fName+' '+lName); // output: Moroj Alharbi
       ```
  * ##### Numbers:
    * The Modulus `%` operator is: 
       `the remainder of a quotient after division.`
    * Here is an example of the `%` operator in use:
       ```javascript
        var calculatesRemainder = 5 % 10;
        console.log(calculatesRemainder); // output: 5
       ```
  * ##### Arrays:
    * An index is: (The position of an item in an array.)
    * You can access an element in an array like this: (arr[index])
    * Map:
      * .map is an array method that: 
         `Access all items in an array and return a new array.`
      * An example of map is: 
        ```javascript
           var arr = ['HTML', 'CSS', 'javascript'];
           var newArr = arr.map(function(item){
             return item+' with WDI';
           });
           console.log(newArr); // output: ["HTML with WDI", "CSS with WDI", "javascript with WDI"]
         ```
    * Filter:
      * .filter is an array method that: 
          `Return the true value that pass the test in new array.`
      * An example of filter is: 
        ```javascript
           var arr = [10, 12, 4, 7, 9];
           var newArr = arr.filter(function(item){
            if ( item % 2 === 0 ){
             return item;
            }
           });
           console.log(newArr); // output: [10, 12, 4]
         ```
    * forEach:
      * .forEach is an array method that: 
         `Access all items in an array (similar to for loop)`
      *  An example of forEach is: 
         ```javascript
           var arr = ['HTML', 'CSS', 'javascript'];
           arr.map(function(item){
             console.log(item);
           }); // output: HTML CSS javascript
         ```

   * ##### objects
     * How to access a property `objectName.objectKey OR objectName['objectKey']` 
        ```javascript
           var info = {
            name: 'Moroj',
            hometown: 'Makkah'
            }
            console.log(`Hi my name is ${info.name}, I'm from ${info['hometown']}.`);
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           var arr = ['HTML', 'CSS', 'javascript'];
           for ( var index = 0 ; index < arr.length ; index++){
            console.log(arr[index]);
           } // output: HTML CSS javascript
          ```
* ### Querying the DOM
  ```javascript
   var container = document.querySelector('#container'); // get the element from the DOM
  ```
* ### Creating a new element in the DOM
  ```javascript
  var addNewPTag = document.createElement('p');
  var addTextToPTag = document.createTextNode('Here is the new element');
  ```
* ### Appending a new element to the DOM
  ```javascript
  addNewPTag.appendChild(addTextToPTag);
  container.appendChild(addNewPTag);
  ```
* ### Updating the style properties
  ```javascript
  container.style.color = 'cyan'; // update the color of the element.
  ```
