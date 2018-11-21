# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    var cat = "Astrid";
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    console.log(cat);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `conditional operator that evaluates to true if the two compared values are equal to each other(type does not matter)`
    * How to use the `"==="` operator: 
       `conditional operator that evaluates to true if the two compared values are equal to each other(type has to be the same) `
    * How to use the `">"` operator: 
        `conditional operator that evaluates to true if the first operand's value is larger than the second's `
   * ##### How to write an if Statements 
      ```javascript
        if (firstOne === secondOne){
        }
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        var play = function(optionalParameter){
        }
       ```
    * This is the other way to declare a function: 
      ```javascript
        function play(){
        }
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        function addsFour(num){
            return (num+4);
        }
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        function capitalize(word){
            return word.toUpperCase();
        }
       ```
    * We use functions because:
      we want to have a contained piece of code that does a specific task and may take in one or multiple values and also may return a value upon completion. Also, it ideally does not depend on other parts of the code base.
* ### datatypes:
  * ##### Strings
    * A string is: 
        Basically text between double or single quotes that can be manipulated by a multitude of convenient methods.
    * You can capitalize a string by: 
        ```javascript
        string.toUpperCase();
       ```
    * Concatentation is: 
        Joining two or more strings together to generate one string.
    * An example of concatenation:
         ```javascript
        "The cat's " + "name is " + `${astrid}`; //overuse just to demonstrate
        //Can also just use backticks instead like:-
        `The cat's name is ${cat}`;
       ```
  * ##### Numbers:
    * The `%` operator is: 
       The modulus operator which does a division and gives the remainder of that operation.
    * Here is an example of the `%` operator in use:
       ```javascript
        5 % 2; //evaluates to 1
       ```
  * ##### Arrays:
    * An index is: the position of elements in the array starting with 0.
    * You can access an element in an array like this:
    ```javascript
    var arr = [1, 2, 3];
    arr[0]; //we get the value 1
    ```
    * Map:
      * .map is an array method that: 
          Creates a new array with the results of calling a provided function on every element in the calling array.
      * An example of map is: 
        ```javascript
           var array1 = [1, 4, 9, 16];

           // pass a function to map
           const map1 = array1.map(x => x * 2);

           console.log(map1);
           // expected output: Array [2, 8, 18, 32]

         ```
    * Filter:
      * .filter is an array method that: 
          Creates a new array with all elements that pass the test implemented by the provided function.
      * An example of filter is: 
        ```javascript
           var words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];

           const result = words.filter(word => word.length > 6);

           console.log(result);
           // expected output: Array ["exuberant", "destruction", "present"]
         ```
    * forEach:
      * .forEach is an array method that: 
         Executes a provided function once for each array element.
      *  An example of forEach is: 
         ```javascript
           var array1 = ['a', 'b', 'c'];

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
           obj.name;
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           var sum = 0;
           for(i = 1; i <= 5; i++){
           sum += i;
           console.log(sum);
           }
          ```
* ### Querying the DOM
  ```javascript
   var firstP = document.querySelector("p");
  ```
* ### Creating a new element in the DOM
  ```javascript
   var newP = document.createElement("p");
  ```
* ### Appending a new element to the DOM
  ```javascript
   existingDiv = document.querySelector("div");
   existingDiv.appendChild(newP);
  ```
* ### Updating the style properties
  ```javascript
   firstP.style.color = "firebrick";
  ```
