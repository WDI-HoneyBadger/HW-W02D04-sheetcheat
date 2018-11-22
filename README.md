# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    
    var home;
     
  * How to console.log the value of a variable: (code)
     var home = 'house';
     console.log(home);
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
    
      It used in to compare values. For example: 5 == 1 the result will be false.
    * How to use the `"==="` operator: 
       
       It used to compare same value and same type. For example: 'word' === 'word' the result is true. Both of them are Strings and their values are equal.
    * How to use the `">"` operator: 
        `
        It used to checks if the value of the left operand is greater than the value of the right operand, if yes, then the condition becomes true.For example, (4 > 2) the result will true.


   * ##### How to write an if Statements 
      if (condition) {
    
} else {
    
}


---
       
 * ### functions:
    * How you declare a function: 
     function home() {
   
}
    * This is the other way to declare a function: 
      function car() {
    var carName = "Jeep";
  
}
    * This is a function that adds 4 to any number:
       
       
       
      
    * This is a function that capitalizes any word: 
      function myFunction() {
    var text= 'hellow'
      console.log(text.toUpperCase());
      
      
}
----
console.log('Codecademy'.toUpperCase());
    * We use functions because:
     `write a definition `
* ### datatypes:
  * ##### Strings
    * A string is: 
        `write a definition `
       a set of letters, single letter and word that is in double or single quotes.
    * You can capitalize a string by: 
        ```javascript
        
        var stre = 'hello world.';
        
        console.log(stre.toUpperCase());
     
 
       ```
    * Concatentation is: 
       joining two strings together.
    * An example of concatenation:
        console.log( " start" + 123 + " hello world!");
 
     
  * ##### Numbers:
    * The `%` operator is: 
       finds the remainder after division two numbers
    * Here is an example of the `%` operator in use:
       7%2=1
     
       
  * ##### Arrays:
    * An index is: (index of an array element is the number can be accessed the brackets [])
    * You can access an element in an array like this: (var number = [1, 2, 3, 4]);
    number[0];  
    1
    
    * Map:
      * .map is an array method that: 
 creates an array filled with all array elements that does not execute the function for array elements without values and does not change the original array.
 * An example of map is: 
    var foods = [“rice ”, “spagity”];

var fastFood = foods.map(function(food) {
	return ‘burger ’ + pizza';
});
    * Filter:
      * .filter is an array method that: 
         creates a new array with elements filter some items out of an existing array.
          
      * An example of filter is: 
  var numbers = [1, 3, 6, 8, 11];

var guess = numbers.filter(function(number) {
  return number > 7;
});

    
    * forEach:
      * .forEach is an array method that: 
        forEach executes a provided function once for each array element.
      *  An example of forEach is: 
  var greeting = ['hi', 'hello', 'bye'];

greeting.forEach(function(element) {
  console.log(element);
});
output:hi
      hello 
      bye

   * ##### objects
     * How to access a property  
    var person = {
    firstName:"nawaf",
    lastName:"Alhathni",
    eyeColor:"black"
};
person.eyeColor();
* ### loops
     *   how to make for loop 
     for (initialization; test condition; iteration statement){
   Statement(s) to be executed if test condition is true
}
* ### Querying the DOM
 document.querySelector(".example");
 
 
 
* ### Creating a new element in the DOM
 var hello = document.createElement('');
 
 
* ### Appending a new element to the DOM


.appendChild();



* ### Updating the style properties
 document.getElementById().style.property = new style
