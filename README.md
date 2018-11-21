# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    //   var a ; // variable Declaration 
    a = 10; // variable Initialization

  
     ```
  * How to console.log the value of a variable: (code)
    ``` javascript
    console.log(a);  // expected output: 2  ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `Checks if the values of two operands are equal or not, if yes then condition becomes true.  `
    * How to use the `"==="` operator: 
       `it verifies that the objects being compared are of the same type and avoids implicit conversions.`
    * How to use the `">"` operator: 
        `	Checks if the value of left operand is greater than the value of right operand, if yes then condition becomes true. `
        
   * ##### How to write an if Statements 
      ```javascript
       var a = 1;
      if (a === 1) {
       var a = 2;
     
   
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
      function a() {
      };
      ```
    * This is the other way to declare a function: 
      ``` javascript
      var a = (function(){
       }); 
       or
       var a = function(){
       };
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        function a(number){
        console.log(4+number); 
        };
        a(3); // 7 
       ```
    * This is a function that capitalizes any word: 
        ```javascript
         function myFunction() {
         var str = "Hello World!";
          var res = str.toUpperCase();
          console.log(res);
           };
          myFunction();
       ```
    * We use functions because:
     ` Once a function is defined, it can be used over and over and over again. You can invoke the same function many times in your program, which saves you work.`
     
* ### datatypes:
  * ##### Strings
    * A string is:  
        `
      /A string is any data. Strings are surrounded by speech marks or quote marks. Either single quotes(') or double quotes(") can be used to enclose characters sometimes numbers are used inside a string speech marks or quote marks so they are treated as strings
        
        `
    * You can capitalize a string by: 
        ```javascript
        // console.log('alphabet'.toUpperCase());
       ```
    * Concatentation is: 
        ` is the operation of joining two strings together. The term"concatenation" literally means to merge two things together. `
    * An example of concatenation:
    
         ```javascript
        // var number =5; 
        console.log("3"+number); //35
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `Divides left-hand operand by right-hand operand and returns remainder. `
    * Here is an example of the `%` operator in use:
       ```javascript
         var y = 5;
       var x = y % 2;
        console.log(y); 
       ```
  * ##### Arrays:
    * An index is:The location of an item in an array. Aggregate child (... is a part of or used in me.) Note: In most programming languages, the first array index is 0 or 1, and indexes continue through the natural numbers. The upper bound of an array is generally language and possibly system specific.
    * You can access an element in an array like this: (code)
        ```javascript
       var cars = ["Saab", "Volvo", "BMW"];
         console.log(cars[0]);
             ```
    * Map:
      * .map is an array method that: 
         `The map() method creates a new array with the results of calling a provided function on every element in the calling array. `
      * An example of map is: 
        ```javascript
         //var pizzaToppings = [
          'pepperoni',
           'cheese',
         'sardines',
         'mushrooms',
          'pineapples',
        'soap',
        'sausage'
           ];

        var pizzaToppingsCaps = pizzaToppings.map(function(topping){
        return topping.toUpperCase();
        })

        console.log(pizzaToppingsCaps);
         ```
    * Filter:
      * .filter is an array method that: 
          `The filter() method creates a new array with all elements that pass the test implemented by the provided function. `
      * An example of filter is: 
```javascript

        
        var words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];

const result = words.filter(word => word.length > 6);
console.log(result)
```
* forEach:
      * .forEach is an array method that: 
         `The forEach() method executes a provided function once for each array element. `
      *  An example of forEach is: 
         ```javascript
          var array1 = ['a', 'b', 'c'];
array1.forEach(function(element) {
  console.log(element);
});   ```
* ##### objects
     * How to access a property  
        ```javascript
           // person = {'firstname': 'John', 'lastname': 'Doe'}

       console.log(person['lastname']);
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           // var step;
           for (step = 0; step < 5; step++) {
           // Runs 5 times, with values of step 0 through 4.
         console.log('Walking east one step');
                  }
          ```
* ### Querying the DOM
  ```javascript
   // document.querySelector(".example")
    document.querySelector("#example")
  ```
* ### Creating a new element in the DOM
  ```javascript
   //var para = document.createElement("P");

  ```
* ### Appending a new element to the DOM
  ```javascript
   // write the syntax
  ```
* ### Updating the style properties
  ```javascript
   //  body.style.backgroundColor = 'red';
   document.getElementById("p2").style.color = "blue";
    document.getElementById("p2").style.fontFamily = "Arial";
   document.getElementById("p2").style.fontSize = "larger";
   

  ```
