# Async Code

## What are some of the signs and causes of callback hell?
One of the signs of callback hell is the pyramid like structure of some developers code. It is caused by the need to write code that runs from the top down, visually, from the DOM.

## What does asynchronus mean, and how are callbacks involved?
Async code essentially is code that needs to run either concurrently, or directly in sequence. Callbacks are one way developers can ensure that a function is called right when it needs to be ran.

## Summarize the 3 ways to avoid callback hell.
Number one would be to keep your code shallow. Limit funtions to performing only one thing at a time. Modualize your code. In other words, create liraries of useful code that can be used over and over again. Finally, you can handle every error. You can set traps, or even use callbacks to help you comb thorugh any errors you encounter in your code.

https://github.com/RyanDavis-bcw/pokemonapi