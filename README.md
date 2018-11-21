# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    var name = 'Abdulrab';
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    console.log(name);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `write a definition `
    * How to use the `"==="` operator: 
       `write a definition `
    * How to use the `">"` operator: 
        `write a definition `
   * ##### How to write an if Statements 
      ```javascript
        if ( name == 'Abdulrab' ){
           console.log('correct');
           };
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        function home(){
        
        };
       ```
    * This is the other way to declare a function: 
      ```javascript
        var home = function(){
        
        };
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        function numberAdd(num){
           return num+4
        };
        numberAdd(8);
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        function capitalizes(str){
        var word = str.toUpperCase();
        };
        capitalizes('abdulrab');
       ```
    * We use functions because:
     `Once a function is written, it can be called multiple times from within the program. `
* ### datatypes:
  * ##### Strings
    * A string is: 
        `sequence of symbols from character and number. `
    * You can capitalize a string by: 
        ```javascript
        var word = str.toUpperCase();
       ```
    * Concatentation is: 
        `joining two strings together. `
    * An example of concatenation:
         ```javascript
        console.log('Abdulrab ' + 'Bin Talib');
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `Finds the remainder after division of one number by another `
    * Here is an example of the `%` operator in use:
       ```javascript
        if ( 4 % 2 == 0 ){
        console.log('even');
        } else {
        console.log('odd');
        };
       ```
  * ##### Arrays:
    * An index is: The location of an item in an array.
    * You can access an element in an array like this: var arr = ['Abdulrab', 'Bin Talib']; arr[0]; // Abdulrab
    * Map:
      * .map is an array method that: 
         `Method creates a new array with the results of calling a provided function on every element in the calling array. `
      * An example of map is: 
        ```javascript
           var bettyCakes = [
                             'strawberry',
                             'banana',
                             'sparkle berry',
                             'chocolate',
                             'confetti',
                             'angel cake',
                             'vanilla'];
          var neopolitan = bettyCakes.map(function(flavor){
            if (flavor == 'strawberry') {
              return 'strawberry'; });


         ```
    * Filter:
      * .filter is an array method that: 
          `Method creates a new array with all elements that pass the test implemented by the provided function. `
      * An example of filter is: 
        ```javascript
           bettyCakes.forEach(function(flavor){
             if (flavor == 'strawberry') {
               neopolitan2.push(flavor);});
         ```
    * forEach:
      * .forEach is an array method that: 
         `Method executes a provided function once for each array element. `
      *  An example of forEach is: 
         ```javascript
           var array1 = ['a', 'b', 'c'];
            array1.forEach(function(element) {
              console.log(element);
            });

         ```

   * ##### objects
     * How to access a property  
        ```javascript
           var person = { Fname: 'Abdulrab', Lname: 'Bin Taleb', location: 'Riyadh' }
           console.log(person.Fname);
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           while(true){
             console.log('Abdulrab');
           };
          ```
* ### Querying the DOM
  ```javascript
   document.querySelector('.class');
   document.querySelector('#id');
  ```
* ### Creating a new element in the DOM
  ```javascript
   var newElement = document.createElement('p');
  ```
* ### Appending a new element to the DOM
  ```javascript
    document.appendChild(newElement);
  ```
* ### Updating the style properties
  ```javascript
   body.style.backgroundColor = 'Blu';
   body.style.width = '80px';
   body.style.height = '80px';
  ```
