A closure is a fusion of a function enclosed together with referencing to it's surrounding state.
A closure is made when an inner function is made accessible from outer function that created it.
This happens when an outer function returns an inner function. 
We can say that a closure gives an oppertunity to access an outer function's scope from an inner function.
The way to use a closure is  simply define a function inside any function and expose it.
To expose a function, return it or pass it to any other function.
The inner function have access to the variables in the outer function scope, even after the outer function has returned.
closures are very helpful to give objects data privacy.
Data privacy is an important function that helps us program to an interface, not an implementation. 
Links from where i studied:
1.http://www.w3schools.com/js/js_function_closures.asp
2.https://lostechies.com/derekgreer/2012/02/17/javascript-closures-explained/
3.https://www.sitepoint.com/javascript-closures-demystified/