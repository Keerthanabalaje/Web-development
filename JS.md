# general
- link for object string access https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String
## Steps to write JS in windows
-  Download visual studio
-  open the folder "Javascript"
-  open new file in our folder name "index.html"
   - put "!"
   - press "Tab"
   - will build a basic code
-  Download live server in the extension
   - right click the file
   - open with live server
   - will take you to the chrome page
## Language JS is a Dynamic
## VARIABLES
-  To reassign a variable use "let", if not use "const"
## Types
- Primitive/Values
  - String
  - Number(All are numbers no floating, integer, etc and all)
  - Boolean
  - Undefined
  - Null(object)
- Reference type
  - Object
    1. Dot notation (object.property)
    2. Bracket notation(object['property'])
  - Array[ ]
  - Function() { }
***
#  oops
Just a Styling not a programme
- used by c#, java, Ruby,Python, javascript
- Angular frme work
## 4 pillar
- encapsulation(groups),
- Abstraction,
- Inheritance and
- Polymorphism(reduce switch case)
***
## Arrays
```
let sow = ['sowmiya',21, 'bsc']
```
***
## Functions
         1. Normal - Camalcase [myName]
         2. Constructor function - [MyName]
         3. Higher order functions => A functions that takes input of other functions.
```
function square(number){
  return number * number;
}
square(2); 
```
#### => Anonymous function 
An anonymous function is a function without a name. An anonymous function is often not accessible after its initial creation.
```
let show = function () {
    console.log('Anonymous function');
};

show();
```
***
## String
- Prmitive string
```
cont kee = 'keerthna';
```
-  Object string
```
const kee =new string('keerthana');
```
***

# ES6 - ANGELA
- Concatenation
- lenght and retriving number => to get number of characters
- Slicing and extracting =>
- case changing
- Basic arithmetic and modulo expression Numbers (BODMAS)
- Increment and decrement
## Math.random [Love calculator]
```
prompt('Enter your name:');
prompt('Enter your spouse name:');
var keerthu= Math.random();
var ana = (keerthu*100) + 1;
alert('Your love calculator is '+ ana)
```
## Arrays
   - arrayName.includes();
   - arrayName.push();
   - arrayName.pop();
### Fizz Buzz
```
var output = [];
var count = 1;
function fizzBuzz () {
    if(count%3 ===0 && count%5 ===0){
       output.push('FIZZBUZZ');
    }
    else if(count%3 ===0) {
         output.push('FIZZ');
    }
    else if(count%5 ===0) {
         output.push('Buzz');
    }
    else {
         output.push(count);
    }
    count=count+1;
    console.log(output);
}
```
# Document Object Model
## Selector
1. document.getElementsByTagName('') => (array)
   - It will not allow to change property/text of the content.
   - So, we should mention square bracket [0] for the only elements
2. document.getElementsByClassName('') => (array)
   - It will not allow to change property/text of the content.
   - So, we should mention square bracket [0] for the only elements
3. document.getElementById('') => (will give single output)
   - It does not need any mentioning in square brackets
4. document.querySelector('') => ( Unlike tagName and className)
   - By changing the property/text it apply it on the first element only.
   - To apply in all of them the go for querySelectorAll.
5. document.querySelectorAll('')
   - By changing the property/text it apply it on all the elements available.
***
## CSS Styles usig DOM
- Eg. document.querySelector('h1').style.color ='red or else'.
***
## Class list
- Eg. document.querySelector('h1').classList.add('Invisibile')
- the class name added with that old one.
- We can use it by giving propertis ties to the class in css files. Can apply this by,
     1. classList.add('')
     2. classList.remove('')
     3. classList.toggle('')
***
## Text
- querySelector('h1').innerHTML; => Will give the the text with HTML tag like <em>Heloo</em> [emp to strong ]
- querySelector('h1').text content; => can only change the text content
***
## Attribute
- Getting = Eg, getAttribute('href)
- Setting = Eg, setAttribute('href','change to some other link')
***
## addEventlistner
1. Anonymous function =>
```
document.querySelectorAll('button')[i].addEventListener('click', function click() {
        alert('Cliked!');
    });
```
2. Named function
```
document.querySelectorAll('button')[i].addEventListener('click', click);
function click() {
        alert('Cliked!');
}
```



