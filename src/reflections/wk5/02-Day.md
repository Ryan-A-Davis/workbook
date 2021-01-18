# Relationships are hard...

## What are the three kinds of relationships?
The three types of relationships are one to one, onte to many, and many to many. In OOP the many to many relationship requires a "buffer" object, to relate the many elements to each other.

## What are the benefits of linking relationships, rather than the traditional embedding method?

Linking keeps the data block itself less complicated. When you embed, you are making a more complex piece of data, that is more difficult to work with on the front end of an application, rather than just pointing to another simple block of data. 
## What are some of the challenges faced when creating a many to many relationship, and making decisions on how to manage it?

Deciding how to manage the relationship in the first place may be the hardest decision to make when creating m=>m relationships. Considerations for data structure, and query design, and how to access what data by what parameters, all need to be taken in to account.

https://github.com/RyanDavis-bcw/gregslistserver