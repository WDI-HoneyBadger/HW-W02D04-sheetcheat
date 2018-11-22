# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```
    var height = 400px;
     ```
  * How to console.log the value of a variable: (code)
    ```
    console.log(height);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
      compares the value only
    * How to use the `"==="` operator: 
       compares the value and the type
    * How to use the `">"` operator: 
        return true if 5 grater than 3 ex( 5>3)
   * ##### How to write an if Statements 
    ```
 
    if(num1>num2){
        console.log('the ',num1,'grater than',num2);
    }else if (num2>num1){
        console.log('the ',num2,'grater than',num1);
    }else{
        console.log('the ',num1,'=',num2);
    }

       ```
 * ### functions:
    * How you declare a function: 
     ```
      function helloWorld(langCode){

    if (langCode=='English'){
        console.log('Hello world');
    }else if(langCode=='Arabic'){
        console.log('مرحبا بالعالم');}
    else {

 console.log('Bonjour le monde');
    }
    ```
      
    * This is the other way to declare a function: 
      ```
      var helloWorld = function (langCode){
      
      
    if (langCode=='English'){
        console.log('Hello world');
    }else if(langCode=='Arabic'){
        console.log('مرحبا بالعالم');}
    else {

 console.log('Bonjour le monde');
    }
      }
      
       ```
    * This is a function that adds 4 to any number:
        ```
        
        function functionAdd(a) {
   
    return a+4;
}
       ```
    * This is a function that capitalizes any word: 
        ```
        function upperCase(string) 
{
    return string.toUpperCase() ;
}
       ```
    * We use functions because:
     `The first reason is reusability. Once a function is defined, it can be used over and over and over again. You can invoke the same function many times in your program, which saves you work.`
* ### datatypes:
  * ##### Strings
    * A string is: 
        `JavaScript's String type is used to represent textual data. It is a set of "elements" of 16-bit unsigned integer values. Each element in the String occupies a position in the String. `
    * You can capitalize a string by: 
        ```javascript
        .toUpperCase() method
       ```
    * Concatentation is: 
        `In javascript the "+" operator is used to add numbers or to concatenate strings. if one of the operands is a string "+" concatenates, and if it is only numbers it adds them `
    * An example of concatenation:
         ```
var z = x + y;
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `The remainder assignment operator divides a variable by the value of the right operand and assigns the remainder to the variable. `
    * Here is an example of the `%` operator in use:
       ```  var x = 5 % 2; //result =1
       
       ```
  * ##### Arrays:
    * An index is: JavaScript arrays are zero-indexed: the first element of an array is at index 0 , and the last element is at the index equal to the value of the array's length property minus 1.
    * You can access an element in an array like this: a[0] = for the first element.
    * Map:
      * .map is an array method that: 
         `The map() method creates a new array with the results of calling a function for every array element. The map() method calls the provided function once for each element in an array, in order. `
      * An example of map is: 
        ```
          var pizzaToppings = [
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
         ```
    * Filter:
      * .filter is an array method that: 
          `write a definition `
      * An example of filter is: 
        ```var pizzaToppings = [
    'pepperoni',
    'cheese',
    'sardines',
    'mushrooms',
    'pineapples',
    'soap',
    'sausage'
  ];
 
  var sPizzaToppings = pizzaToppings.filter(function(topping) {
    return topping[0] === 's';
  });
  
         ```
    * forEach:
      * .forEach is an array method that: 
         `write a definition `
      *  An example of forEach is: 
         ```var pizzaToppings = [
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
        ```var  aquarium = {
    filledWithWater: true,
    capacityInGallons: 12,
    numberOfRocks: 5,
    fish: [
            {
                type: 'goldfish' ,
                size: '3.5 inches',
                color: 'golden'
            },
            {
                type: 'puffer',
                size: '4 inches',
                color: 'tan'
            },
            {
                type: 'clown',
                size: '3 inches',
                color: 'orange'
            }
        ]
}
aquarium.capacityInGallons;
        ```
* ### loops
     *   how to make for loop 
         ```
         for(var i=0 ; i< a.length ; i++){
         return a[i];
         }
         
          ```
* ### Querying the DOM
  ```javascript
 document.querySelector(".example");

  ```
* ### Creating a new element in the DOM
  ```var para = document.createElement("p");
var node = document.createTextNode("This is new.");
para.appendChild(node);
  ```
* ### Appending a new element to the DOM
  ```
  para.appendChild(node);
  ```
* ### Updating the style properties
  ```
   animal.style.color ='black';
  ```
