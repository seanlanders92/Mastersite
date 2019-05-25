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
 >This javascript as an example will display a greeting on a webpage that changes based on the time of day. Basically javascript is the code that drives the functionality of the webpage. It allows you to create interactivity on a website such as buttons or user prompts.
 [Home](./README.md)