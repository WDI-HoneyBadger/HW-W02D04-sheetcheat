# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    Var variableName;
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    // console.log(value);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `The more commonly-used abstract comparison (e.g. ==) converts the operands to the same type before making the comparison.
    * How to use the `"==="` operator: 
       A strict comparison (e.g., ===) is only true if the operands are of the same type and the contents match.
    * How to use the `">"` operator: 
        Greater than 30>20
   * ##### How to write an if Statements 
      if(condition1){
      //code to be executed if condition1 is true
      }else if (condition2){
      //code to be executed if condition1 is false and condition2 is true.
      }else{
      //code to be executed if condition1 is false and condition2 is false.
      }
      }
 * ### functions:
    * How you declare a function: 
      ```javascript
        // Function is a term that comes out of mathematics. You may remember hearing it in your high school algebra class.
       ```
    * This is the other way to declare a function: 
      ```javascript
        // Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.
       ```
    * This is a function that adds 4 to any number:
        var quad = function(num) {
    return num + 4;
}
console.log(quad(2));
    * This is a function that capitalizes any word: 
        function func() { 
    // Original string 
    var str = 'HoneyBadger'; 
    // String converted to Upper Case 
    var string = str.toUpperCase(); 
    console.log(string); 
} 
    * We use functions because:
      Don't repet yourself.
* ### datatypes:
  * ##### Strings
    * A string is: 
     Strings are collections of letters and symbols known as characters, and we use them to deal with words and text in JavaScript. They come in two varieties, 'single-quote' and "double-quote."
    * You can capitalize a string by: 
        ```javascript
        //  toUpperCase() 
       ```
    * Concatentation is: 
        `write a definition `
    * An example of concatenation:
         ```javascript
        function myFunction() {
    var str1 = "Hello ";
    var str2 = "world!";
    var res = str1.concat(str2);
  console.log(res);
}
myFunction();
       ```
  * ##### Numbers:
    * The `%` operator is: Binary operator. 
       Returns the integer remainder of dividing the two operands.
    `
    * Here is an example of the `%` operator in use:
       ```javascript
       12 % 5 returns 2.
       ```
  * ##### Arrays:
    * An index is: (definition) An array is a special variable, which can hold more than one value at a time.
      You access an array element by referring to the index number.
    * You can access an element in an array like this: (code)
    * Map:
      * .map is an array method that: 
         The map() method creates a new array with the results of calling a provided function on every element in the calling array.
      * An example of map is: 
        var array1 = [1, 4, 9, 16];
     // pass a function to map
      const map1 = array1.map(x => x * 2);
      console.log(map1);
    // expected output: Array [2, 8, 18, 32]
         ```
    * Filter:
      * .filter is an array method that: 
          filter() creates a new array with elements that fall under a given criteria from an existing array
      * An example of filter is: 
       var numbers = [1, 3, 6, 8, 11];
       var lucky = numbers.filter(function(number) {
       return number > 7;
       });
      // [ 8, 11 ]
    * forEach:
      * .forEach is an array method that: 
         forEach() is designed to run a function on each indexed element in an array.
      *  An example of forEach is: 
         const arr = ['cat', 'dog', 'fish'];
         arr.forEach(element => {
        console.log(element);
        });

   * ##### objects
     * How to access a property  
        ```javascript
           objectName["propertyName"]
        ```
* ### loops
     *   how to make for loop 
         var text = "";
          var i;
       for (i = 0; i < 5; i++) {
        text += "The number is " + i + "<br>";
}
console.log(text);

* ### Querying the DOM
  var special = document.querySelectorAll( "p.warning, p.note" );
  
* ### Creating a new element in the DOM
   var para = document.createElement("p");
   
* ### Appending a new element to the DOM
  var para = document.createElement("P");                       // Create a <p> node
var t = document.createTextNode("This is a paragraph.");      // Create a text node
para.appendChild(t);                                          // Append the text to <p>
document.getElementById("myDIV").appendChild(para);           // Append <p> to <div> with id="myDIV"
* ### Updating the style properties
  document.getElementById(id).style.property = new style
