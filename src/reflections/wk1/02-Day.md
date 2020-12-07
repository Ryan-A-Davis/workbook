# CSS Basics

## What is a psuedo-class, and what are some of the most commonly used ones?
A psusedo class is a selector that selects elements that are in a certain state, such as after, or before. Some of the most commonly used ones are the aforementioned before and after, as well as hover, first, last and only child and invalid.

## What is specificity and how might you use it to your benefit?
Specificity is the level of discretion the computer uses to apply selectors. For example calling out a tag name in an external style sheet gives an element a specificity of 1, while calling out an id gives that selector a specificity of 10, which will apply styles with more priority over the simple tag name selector. You can use specificity to more easily control the overall style of elements on your page. 

## What problems do you think you will encounter if you over-utilize the !important feature?
The bigger a project gets, the more people will be involved, and it's not a good idea to use the important tag, because it will make it harder for anyone to change any of the elements without going into the code, and searching for the elements that are tagged as important.  