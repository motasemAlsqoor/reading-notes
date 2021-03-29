# Express

HTTP is the foundation of data communication for the World Wide Web. It is a *request-response* protocol which helps users communicate with the server to perform CRUD operations. HTTP supports a number of request methods such as PUT, POST and PATCH to create or update resources.[1]


## The difference between PUT and PATCH?

The PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource (1).

PATCH applies a partial update to the resource.


put :

```app.put(path, callback [, callback ...])```

Routes HTTP PUT requests to the specified path with the specified callback functions.

## tools that allow you to “mock” an API for development like json-server

1. [Postman Mock Server](https://learning.getpostman.com/docs/postman/mock-servers/setting-up-mock/)

2. [Mockserver](https://www.npmjs.com/package/mockserver)

3. [Wiremock](http://wiremock.org/)

## HTTP Status Codes

1. 1xx: Informational

It means the request has been received and the process is continuing.

2.	2xx: Success

It means the action was successfully received, understood, and accepted.

3.	3xx: Redirection

It means further action must be taken in order to complete the request.

4.	4xx: Client Error

It means the request contains incorrect syntax or cannot be fulfilled.

5.	5xx: Server Error

It means the server failed to fulfill an apparently valid request.


## SOAP & REST

SOAP and REST are two API styles .

An API stands for Application Programming Interface. It makes it possible to transfer data from an app to onther
An API receives requests and sends back responses through internet protocols such as HTTP, SMTP, and others.

REST was created to address the problems of SOAP.

SOAP is a standardized protocol that sends messages using other protocols such as HTTP and SMTP .

REST is not a protocol but an architectural style. The REST architecture lays down a set of guidelines you need to follow if you want to provide a RESTful web service, for example, stateless existence and the use of HTTP status codes.

As SOAP is an official protocol, it comes with strict rules and advanced security features such as built-in ACID compliance and authorization. Higher complexity, it requires more bandwidth and resources which can lead to slower page load times.







# References

1. https://en.wikipedia.org/wiki/Patch_verb



