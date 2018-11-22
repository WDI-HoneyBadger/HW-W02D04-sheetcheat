# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    // var name = 'yahya';
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    // console.log(name);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `the double equals will compair two values without looking to its type so, 7 == '7' will return true in this case `     
    * How to use the `"==="` operator: 
       `the threequal will compair two values with respect to its types so 7 === '7' will return flase since one of them is a number and the other one is a  string `
    * How to use the `">"` operator: 
        `this is calles the "grater than operator"
        it could be use to compair between two values and return the grater one 
       ex: if num1>num2 return num1
        `
   * ##### How to write an if Statements 
      ```javascript
        var num = 100;
        if(num > 50){
        console.log('number is grater than 100');
        }
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        var func = function(){
        }
       ```
    * This is the other way to declare a function: 
      ```javascript
        function func(){
        }
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        function addFour(num){
        numPlusFour = num + 4;
        console.log(numPlusFour);
        }
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        function capitalizer(word){
        capitalWord = word.toUpperCase();
        }
       ```
    * We use functions because:
     `to meet our very firts requirement when it gets to coding "DRY" also, functions are very helpful ans it makes our code more effecient `
* ### datatypes:
  * ##### Strings
    * A string is: 
        ` a data type that accepts "Texts" to be passed in to it, in simple words strings are words `
    * You can capitalize a string by: 
        ```javascript
           anyString.toUpperCase();
       ```
    * Concatentation is: 
        ` Andding to string together `
    * An example of concatenation:
         ```javascript
       str1 = 'Yahya'; str2 = 'Aloyoni' ;
       fullName = str1 + str2;
       console.log(fullName); // YahyaAloyoni
       ```
  * ##### Numbers:
    * The `%` operator is: 
       ` "modules" this operator allows us to get the remainder of a division `
    * Here is an example of the `%` operator in use:
       ```javascript
        if(num%2 == 0){
        console.log('its an even number')
        }
       ```
  * ##### Arrays:
    * An index is: (the position of the elements within the array, a little note indecies strats from 0 so to get the first element of a certain array we would do arr[0])
    * You can access an element in an array like this: (arr[0];)
    * Map:
      * .map is an array method that: 
         `Creates a new array with the result of calling a function for each array element < W3schools `
      * An example of map is: 
        ```javascript
           var excitingBettyCakes = bettyCakes.map(function(cake) {
           var loudCake = cake.toUpperCase() + '!';
           return loudCake;
           });
         ```
    * Filter:
      * .filter is an array method that: 
          `Creates a new array with every element in an array that pass a test < W3schools `
      * An example of filter is: 
        ```javascript
           var empFullTime = employees.filter(function(emp){
           if (emp.status == 'full-time'){
                return emp;
            }
          });
         ```
    * forEach:
      * .forEach is an array method that: 
         `Calls a function for each array element < W3schools`
      *  An example of forEach is: 
         ```javascript
               bettyCakes.forEach(function(cake){
               console.log(excitedWord(cake))
               });
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           object.property;
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           for(i = 0; i < 5; i++){
           do something for 5 times
           }
          ```
* ### Querying the DOM
  ```javascript
    document.querySelector(' element,tag,id or class ')
  ```
* ### Creating a new element in the DOM
  ```javascript
     var newPTag = document.createElement('p');
  var newPTagText = document.createTextNode(capitalizedInput); 
  // ^^ from coodalongs
  ```
* ### Appending a new element to the DOM
  ```javascript
   newPTag.appendChild(newPTagText);
   resultSection.appendChild(newPTag);
  ```
* ### Updating the style properties
  ```javascript
   htmlClass = document.querySelector('class')
   htmlClass.style.color: 'rebeccapurple';
  ```
