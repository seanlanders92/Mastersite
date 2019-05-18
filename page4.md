# Intro to javascript
>Below is an example of some java script code.
<script src="javatest.js"></script>
>This is the code used to achieve the previous affect. 
'var today = new Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) {
    greeting = 'Good evening!';
} else if (hourNow > 12) {
    greeting = 'Good afternoon!';
} else if (hourNow > 0) {
    greeting = 'Good morning!';
} else {
    greeting = 'Welcome!';
}

console.log(greeting);

document.write('<h3>' + greeting + '</h3>');'