# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    var hi = "hi";
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    console.log(hi);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       These double equal signs used to check the euqality between two things.
    * How to use the `"==="` operator: 
       These triple equal signs are used to compare between variable types.
    * How to use the `">"` operator: 
        `To compare which side is bigger the other.
   * ##### How to write an if Statements 
      ```javascript
        if(1 < 2){
        console.log('hi');
        
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        function hello(){
        
        }
       ```
    * This is the other way to declare a function: 
     ```
     var hello = function(){
     
     }
     
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        function addFour(num){
        
        return num + 4;
        
        }
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        function capitalize(string){
        
        return string.toUpperCase();
        
        }
       ```
    * We use functions because:
     To avoid repeating our selves and to keep the code structure clean and neat. 
* ### datatypes:
  * ##### Strings
    * A string is: 
        A combination of letters.
    * You can capitalize a string by: 
        ```javascript
        string.ToUpperCase();
       ```
    * Concatentation is: 
        Placing strings beside each other.
    * An example of concatenation:
         ```javascript
        console.log("Hello" + "General" + "Assembly");
       ```
  * ##### Numbers:
    * The `%` operator is: 
       To get the reminder of the numbers, mostly used in finding odd or even numbers.
    * Here is an example of the `%` operator in use:
       ```javascript
        if(4 % 2 === 0){
         console.log('GA');       
        
        }
       ```
  * ##### Arrays:
    * An index is: the place of an element in the array.
    * You can access an element in an array like this: (code)
    * Map:
      * .map is an array method that: 
         Creating a new array after going through provided function with specific task.
      * An example of map is: 
        ```javascript
        
        // var pizzaToppings = [
//   'pepperoni',
//   'cheese',
//   'sardines',
//   'mushrooms',
//   'pineapples',
//   'soap',
//   'sausage'
// ];

/* FOREACH LOOPS */
/* pizzaToppings.forEach(function(topping){
  if(topping[0] == 's') {
    console.log(topping);
  }
})
         ```
    * Filter:
      * .filter is an array method that: 
          Has a function built in which is responsible in comparing between variables or objects. It's very similar to if statement but in professional and wise way.
      * An example of filter is: 
        ```javascript
        
        var strikeEmployees = employees.filter(function(employ){
    return ((employ.status == 'part-time') && (employ.weeklyPay < 500));
})

console.log(strikeEmployees);
          
         ```
    * forEach:
      * .forEach is an array method that: 
         It's the function that loops through an array and has built in function for further actions.
      *  An example of forEach is: 
         ```javascript
           var pizzaToppings = [
  'pepperoni',
  'cheese',
  'sardines',
  'mushrooms',
  'pineapples',
  'soap',
  'sausage'
];

pizzaToppings.forEach(function(topping){
  if(topping[0] == 's') {
    console.log(topping);
  }
})
         ```

   * ##### objects
     * How to access a property  
        ```javascript
         var ob = {
        name: 'Khalid'; 
         }
         
         ob.name;
        ```
* ### loops
     *   how to make for loop 
         ```javascript
          for(var i = 0; i<20; i++){
          
          consloe.log(i);
          
          
          }
          ```
* ### Querying the DOM
  ```javascript
   document.querySelector();
  ```
* ### Creating a new element in the DOM
  ```javascript
   document.ceateElement();
  ```
* ### Appending a new element to the DOM
  ```javascript
  object.appendChild(ob2);
  ```
* ### Updating the style properties
  ```javascript
   ob.style.color = 'red';
  ```
