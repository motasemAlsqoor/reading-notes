# Express REST API

## Name 3 real world use cases where you’d want to change the request with custom middleware

1. when i want to log the request data before handling it  r

2. when i want to validate the request data before handling it 

3. when i want to add body to the request

## True or false: The route handler is middleware?

the middleware in general looking for incoming requests and then prepare it for processing then call the next() 
to invoke the route handler

the route handler catch the request and processing and by invoke code block (handler)

in Express the middleware always accept the next() callback and invoke it when the proccessing done 

in Express the route handler also may  accept next() function and act as exactly as the middleware (1)

as summary yes , in Express the route is middleware when it accepts and invoke the next() callback

## In what ways can a middleware function end the process and send data to the browser?

by invoking the next() function 

## At what point in the request lifecycle can you “inject” middleware?

before handling the request (preaparing to processing) 

## What can cause express to error with “Request headers sent twice, cannot start a second response”

when the next callback is not invoked in the middleware

## references 

1. https://expressjs.com/en/guide/routing.html