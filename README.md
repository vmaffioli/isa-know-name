# isname

A simple validation to check if a string is a know first name.

At this point the main function just compares an input string with a json list loaded by the function. Currently with 7000+ know names.

The focus of this project are build and upload a simple NPM Package, for studies pruporses.

##Instalation -> 
    npm install isa-know-name 
    
##In code usage example -> 
    const name = require('is-know-name');

##To check if string/array contains a know name and returns a boolean value
    name.check('string or array here')

##To filter the string/input and returns a new array with only know names
    name.filter('string or array here');



To add names to the package edit the data.json located in root of this package.

https://www.npmjs.com/package/isa-know-name
