# Homework #4

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.
		
	* Callback Functions
	  * A function that is an argument to another function. e.g. array.forEach(function(num) { //stuff }); *** Usually when defining your own callback functions, the calling function's argument is abbreviated and referenced as 'cb'.
	* Closure
	  * A function that is returned from a function. This allows you to create functions dynamically that may need to be customized for certain situations. This function remembers the scope from where it was defined.
	* arguments array
	  * This is a sort of built-in array that allows you to access a function's arguments when the amount of arguments are not known. i.e. the array is literally called "arguments" and can be accessed like a normal array but its limited on the methods that can be used on it. Does have .length() method so it can be iterated through (i.e. for loop).
	* recursion
	  * A form of iteration by having a function call itself. See Fibonacci example...
	* prototype
	  * This allows you to later modify a class/constructor even the built-in ones in javascript. e.g. class.prototype.newproperty
	* constructors
	  * Constructors in javascript are like a pseudo-class in stronger typed langauges (java, c#, etc). These are created as a function and built like an object within it (its argument is usually an object). e.g. function User(options) { this.username = options.username; this.password = encryptPass(options.password); } *** This allows you to create new objects when you need to do another processes (i.e. validation, other functions) behind the scenes without having to explicitly call them when making a new object manually.


2. Fork and clone this repo.  When you need to commit use the following commands.
		
	* git status
	* git add --all
	* git status
	* git commit -m "your commit message"
	* git push origin master

3. Install dependencies using `npm install`.  Run tests using `npm test`.

4. Make the tests pass!



#### Congratulations on finishing Homework #4!
Apply to our full-time or part-time immersive program to learn cutting edge technologies that are used by top technology companies around the world.

Our part-time and full-time courses are 13 intense weeks of focused study on the most relevant technologies.  

Class sizes are small to ensure that each student gets individual attention from our world class instructors to help them succeed.  We also provide career support both during and after the course to help you succeed.  We are committed to your success.

For more information visit: https://www.lambdaschool.com
