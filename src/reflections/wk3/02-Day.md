#Day Two...Encapsule Corp

##What is the purpose of encapsulation?
Encapsulation is mainly used to maintain secure, clean and readable code. It promotes the separation of truly private functions from public scope. 

##What were some of the problems with closures and the underscore prefix?
By using the underscore prefix, some developers were unintentionally giving access to functions that were meant to be private. This could lead to unintentional bugs and breaking changes by users not meant to have access to these functions.  

##How do we make private variables in a E6 Class? Why would you do this?
You can use closures to create priveleged methods that only have scope within the boundaries of it's lexical environment. You can also use a private field such as a class, with self contained functions that also only have scope within the boundaries of the field.  
