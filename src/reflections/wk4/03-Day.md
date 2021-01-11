## Javascript Promises

# What are the three states of a promise?
The three states of a promise are pending, resolved, and rejected. Pending is the initial state of a promise, resolved is the completed stage of a promise, rejected is the failed state of a promise.
# How does a promise seek to resolve the issues of "callback hell"?
It allows the developer to attach callbacks to the promises instead of passing them as parameters. This makes the code much easier to read.


# What is the difference between .then() and .catch()?
The .then() method is only used for resolved promises. The catch method allows the developer to 'trap' an error from a bad request, which makes debugging much easier. 

https://github.com/RyanDavis-bcw/trivia