# Relationships are still hard...

## In simple terms, what is a sub-document?
A document nested in another document. More specifically to mongoose, a schema nested within another schema.
## When might you use a sub document?
When there is a direct, but complex one to one relationship between two schemas. That way, all of the data relevant to the parent schema are nested within the parent data object.

## How do you add to a collection of sub-documents? What about editing them?
The first step is to find the element in the parent schema you wish to change. Next, you can drill into the collection of sub-documents using dot notation. Finally you can edit or add the information you wish to change/add, and remake the sub-document array.

https://github.com/RyanDavis-bcw/da-planets