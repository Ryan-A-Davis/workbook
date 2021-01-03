#Day 4...Observe and Reflect

##What problems does the observer pattern seek to solve?
The issue of keeping disparate elements synched with the same data. 

##What are three mechanisms of the observer pattern?
The three mechanisms are the subscribe, unsubscribe and broadcast methods. 

##Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your underestanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

The proxystate extends the listeners from the eventemitter file. This file puts a listener or observer, on every piece of data entered into the app state. This allows the controller to observe changes made in the dom by accessing these listeners. The listeners signal the controller that change has been made to the DOM, and it passes those changes to the Service, which manipulates the ProxyState of the application.The AppState itself is never directly manipulated, since it exports the ProxyState as an instance of the AppState. This maintains basic security measure to ensure that your data can only be manipulated within your files.