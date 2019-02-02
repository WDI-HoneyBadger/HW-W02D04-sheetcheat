# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    //Variables are declared with the var keyword as follows:
    var name;
    //multiple variables with the same var keyword as follows:
    var name , age;
  * How to console.log the value of a variable: (code)
  
   console.log(name)
   
   
   
   
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
    equal to as 
    var x=2
    if(x==2){
    console.log(x)
    }else
    console.log("false")
    
    * How to use the `"==="` operator:
    equal value and equal type 
    var x="2"
    if(x==="2")
    console.log("true")
    else
    console.log("false")
 
    * How to use the `">"` operator: 
    var x=4
        greater than as if  (x > 2){
        console.log(x);
        }
   * ##### How to write an if Statements 
   
     if (condition) {
    block of code to be executed if the condition is true
}
 * ### functions:
    * How you declare a function: 
    
      function functionname(parameter)
      {
         statements
      }
    * This is the other way to declare a function: 
     
     var mohrah =function(){
     console.log(mohrah)
     }
    * This is a function that adds 4 to any number:
   var number;
   function add(num){
   return num + 2;
   }
    * This is a function that capitalizes any word: 
   function capitalizeEachWord(str) {
    return str.replace(/\w\S*/g, function(txt) {
        return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
    });
    
    * We use functions because:
     The most common way to define a function in JavaScript is by using the function keyword, followed by a unique function   name, a list of parameters (that might be empty), and a statement block surrounded by curly braces.
     
* ### datatypes:
  * ##### Strings
    * A string is: 
    string or a text string is a series of characters  
    * You can capitalize a string by: 
    function capitalizeEachWord(str) {
    return str.replace(/\w\S*/g, function(txt) {
        return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
    });
    * Concatentation is: 
    -is sticking different things together to make a unit
    -is usually used to stick strings and variables together
    * An example of concatenation:
   var x = "2";
   the 2 is not a number but a string, and if then you had the line:
   var y = 3 + x;
   the variable y would contain this string: "32"
  * ##### Numbers:
    * The `%` operator is: 
    Outputs the remainder of an integer division
    * Here is an example of the `%` operator in use:
    var x=5
    var y=2
    var result= x % Y
    console.log(result)
  * ##### Arrays:
    * An index is:
    Javascript array indexOf() method returns the first index at which a given element can be found in the array, or -1 if it is not present.
    * You can access an element in an array like this: 
 array.indexOf(searchElement[,fromIndex]);
    * Map:
      * .map is an array method that: 
       method creates a new array with the results of calling a provided function on every element in this array.
      * An example of map is: 
     array.map(callback[, thisObject]);

   * Filter:
      * .filter is an array method that: 
      method creates a new array with all elements that pass the test implemented by the provided function.
      * An example of filter is: 
    
      array.filter(callback[,thisobject]);
      
   * forEach:
      * .forEach is an array method that: 
    method calls a function for each element in the array
      *  An example of forEach is: 
        
   array.forEach(callback[, thisObject]);
        

   * ##### objects
     * How to access a property  
   
      var book = new Object();   // Create the object
      book.subject = "tt"; // Assign properties to the object
      book.author  = "yyy";
      
* ### loops
     *   how to make for loop 
    
     for (i = 0; i < 5; i++) {
    text += "The number is " + i ;}
         
          
 * ### Querying the DOM

  document.querySelector(".example");
 
* ### Creating a new element in the DOM
  
 document.craetElement('div')
 
 * ### Appending a new element to the DOM

  node.appendChild(node)

  * ### Updating the style properties

document.getElementById(id).style.property = new style;
