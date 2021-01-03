#Day 3...ProxyObjects and You!

##What are the two common operations that we will set in the handler?
Two common operations in a handler will be the 'get' and 'set' functions. These are used to report or manipulate the values of called methods.

##What do you have to make sure you are doing with every Get to insure the value does not become undefined?
Maker your custom getter be able to take in two values, the object itself, and the value of the property trying to be accessed. This way, you can read the values on the object, and not override the automatic return value of the get method. 

##What are some of the benefits of the proxy object that we are using in our structure for applications?
The ability to customize get and set methods to the specific needs of your application. It also helps with access restriction to private properties of objects. 
