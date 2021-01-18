# More relationship drama...

## What is a virtual property?
A virtual property is one that is not actually stored in the database on that data -object. It is appended on to the body of a return from a front end request, for ease of use.

## When might you use a virtual property? 
When there is relationship between two data objects, one might append virtuals on one or both of the objects that tie it to the other. 

## How do you search by a virtual properties value?

You cannot. The only way to access virtual properties, is to know the address of the parent schema/model and find them that way.