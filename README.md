# isname

A simple validation to check if a string is a know first name.

At this point the main function just compares an input string with a json list loaded by the function. Currently with 7000+ know names.

The focus of this project are build and upload a simple NPM Package, for studies pruporses.

    ##Instalation -> 
    npm install is-know-name 
    
    ##In code usage -> 
    const name = require('is-know-name');
    name('Put-a-name-here')

    ##Input ->
    String = Returns True or False;
    Array = Returns an array with names that have passed validation; if nobody passes the validation, it returns false;
