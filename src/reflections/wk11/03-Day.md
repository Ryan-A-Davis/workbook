# Injection

## What is SQL injection?
An a Injection is an attempt by a malicious actor to manipulate server data. Usually the intention is to steal the data.

## What are 3 methods SQL injection can be done by?

Entering SQL commands into a web form. Appending sql queuries onto a URL. or inserting commands in a brower cookie.

## How can we detect and sanitize SQL injection attacks?

You can limit scope of sql commands in your program by using an orm like Dapper. Dapper handles the sanitization for you.