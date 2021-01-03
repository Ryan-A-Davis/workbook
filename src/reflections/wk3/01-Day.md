#Week Three...Attack of the MVC

##What problem does using exports solve?
It makes it so the use of multiple script tags unneccesary at run time, which improves app performance and efficiency. It also eliminates the need tp run things as 'strict', since things in their own module are run as strict by default, and used components are expsed using exports.

##How does export differ from export default?
An export default assumes that you will only be exporting one block of code from the file. The export statement on it's own lets you export multiple blocks to multiple different files. 

##What is the benefit of using the module system?
It helps keep code organized in blocks of unctionality, which makes it easier to read and debug. 