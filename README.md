# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    // write the syntax 
    var jay = "Jumanah";
  * How to console.log the value of a variable: (code)
    ```javascript
    // write the syntax console.log(jay);
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
      In short, '==' compares only value
      ex jumanah == 'jumanah'
      value return true
    * How to use the `"==="` operator: 
      while '===' checks value as well as type.
      ex jumanah === "jumanah"
       value return false
    * How to use the `">"` operator: 
        it's an operater that means "greater than"
        ex: 7 > 2 
        7 is greater than 2 
   * ##### How to write an if Statements 
      ```javascript
        // write the syntax
     if (hour < 15) { 
     greeting = "Have a wonderful day!!" 
     } else { 
     greeting = "See you soon!!"; 
     }
 * ### functions:
    * How you declare a function: 
      ```javascript
        function myFunction(a, b) {
        return a * b;
        }
    * This is the other way to declare a function: 
      ```javascript
       var x = function (a, b) {return a * b};
     
    * This is a function that adds 4 to any number:
        ```javascript
        var divideAnum = function(num) {
        return num * 4 
        }
       ```
    * This is a function that capitalizes any word: 
        ```javascript
       function capWord(word){ 
       return word.toUpperCase();}
       console.log(capWord(“Jumanah”)) ;
       ```
    * We use functions because:
    Functions always return a value. In JavaScript, if no return value is specified, the function will return undefined.
* ### datatypes:
  * ##### Strings
    * A string is: 
       A string can be any text inside double or single quotes
       ex "Jumanah" or 'Jumanah'
    * You can capitalize a string by: 
        ```javascript
        .toUpperCase();
       ```
    * Concatentation is: 
       The term"concatenation" literally means to merge two things together.
    * An example of concatenation:
         ```javascript
        example  > "Say Salam Alaikum " + 11 + " times extremly fast!"
        the result shows this >>’Say Salam Alaikum 11 times extremly fast!’
       ```
  * ##### Numbers:
    * The `%` operator is: 
       The % is a modulus (Division Remainder).The remainder operator returns the remainder left over when one operand is divided by a second operand. It always takes the sign of the dividend.
    * Here is an example of the `%` operator in use:
       ```javascript
        12 % 5 // 2
       ```
  * ##### Arrays:
    * An index is: The index is a method returns the first index at which a given element can be found in the array, or -1 if it is not present
    * You can access an element in an array like this: []
    * Map:
      * .map is an array method that: 
         `The map() method creates a new array with the results of calling a provided function on every element in the calling array. `
      * An example of map is: 
        ```
           var array1 = [1, 3, 9, 10];
           // pass a function to map
           const map1 = array1.map(x => x * 2);
           console.log(map1);
           // expected output: Array [2, 6, 18, 20]
         ```
    * Filter:
      * .filter is an array method that: 
          `The filter() method creates a new array with all elements that pass the test implemented by the provided function.
      * An example of filter is: 
        ```
        var words = ['red', 'blue', 'pink', 'watermelon', 'lemonade', 'sandcastle'];
        const result = words.filter(word => word.length > 6);
        console.log(result);
        // expected output: Array ["watermelon", "lemonade", "sandcastle"]
         ```
    * forEach:
      * .forEach is an array method that: 
         `The forEach() method executes a provided function once for each array element.
      *  An example of forEach is: 
         ```var array1 = ['apple', 'orange', 'banana'];
         array1.forEach(function(element) {
         console.log(element);
         });
         // expected output: "apple"
         // expected output: "orange"
         // expected output: "banana"
           
         ```

   * ##### objects
     * How to access a property  
        `A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same   as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:
        example > (objectName.propertyName)
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           var i;
           for (i = 0; i < cars.length; i++) { 
           text += cars[i] + "<br>";
           }
          ```
* ### Querying the DOM
  ```javascript
   document.querySelectorAll > to select many values.
   ex var special = document.querySelectorAll("p.warning, p.note" );
   or document.querySelector > if we want to select one tag or one value.
   var el = document.querySelector( "#main, #basic, #exclamation" );
  ```
* ### Creating a new element in the DOM
  ```javascript
   This code creates a new <p> element:
   example var para = document.createElement("p");
   To add text to the <p> element, you must create a text node first. This code creates a text node:
   var node = document.createTextNode("Whooo you passed the exam!!");
  ```
* ### Appending a new element to the DOM
  ```javascript
   example para.appendChild(node);
  ```
* ### Updating the style properties
  ```javascript
   we can updating the style properties by using (.getElementsByTagName + setAttribute)
   Also we can change the color we can use (document.body.style.backgroundColor = "red";)
   one example to update the link in a document: document.getElementsByTagName("INPUT")[0].setAttribute("type", "button");
   Another example : var anchor = document.getElementById("myAnchor");  // Get the <a> element with id="myAnchor"
   var att = document.createAttribute("href");        // Create a "href" attribute 
   att.value = "https://www.w3schools.com";            // Set the value of the href attribute
   anchor.setAttributeNode(att);                      // Add the href attribute to <a>
  ```
