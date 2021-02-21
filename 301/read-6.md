# NodeJS

NodeJS is an open source and cross-platform runtime environment for executing JavaScript code outside of a browser .

quite often we use no to build *back-end services* also called **api's** or application programming interfaces .

these are the services that *power* (serve) our client
applications like a web app running
inside of a web browser or mobile app
running on a mobile device .

these client apps are simply what the user sees and
interacts with . (they're just the surface)

they need to talk to some *services* sitting on the *server* or in the cloud to store data send emails or push notifications .

Node is ideal for building highly scalable data intensive and real-time back-end services that power our client
applications .

Node is easy to get started and can be used for prototyping and agile development but it can also be used for building super fast and highly scalable services .

it's used in production by large companies such as PayPal uber Netflix Walmart and so on .

node is an excellent choice for building highly scalable services .

another reason for using node is that it has the largest number of open source libraries available to you.
so for pretty much any features or building blocks you want to add your application there is some free open source library out there that you can use so you don't have to build this building blocks from scratch and instead you can focus on the core of your application .

## The Architecture of Node

so in the last video you learned that
note is a runtime environment for
executing JavaScript code but what is a
runtime environment really well before
node we use JavaScript only to build
applications that run inside of a
browser so every browser out there has
what we call a JavaScript engine that
takes our JavaScript code and converts
it to code that a computer can
understand.

for example Microsoft edget
uses *chakra*, Firefox uses *spider monkey*
and chrome uses *v8* and it's because of
these varieties of engines that
sometimes JavaScript code can behave
differently in one browser or another.

now a browser provides a runtime
environment for JavaScript code for
example you probably know that in
browsers we have the window or the
document object these objects allow us
to work with the environment in which
our code is running now up to 2009 the
only way to execute JavaScript code was
inside of a browser .

in 2009 **Brian Dahl** the creator of node came up
with a brilliant idea he thought it would be great to execute JavaScript outside of a browser so he took Google's
v8 engine which is the fastest JavaScript engine out there and embedded it inside a C++ program and called that
program node.

so similar to a browser node is a runtime environment for
JavaScript code.
it contains a JavaScript engine that can execute our JavaScript code but it also has certain objects
that provide an environment for our JavaScript code but these objects are different from the environment objects
we have in browsers for example we don't
have the document object instead we have
other objects that give us more
interesting capabilities.

for example we can work with the file system listen for requests and a given port and so on we
can't do stuff like that inside of a
browser right so in essence node is a
program that includes the v8 JavaScript
engine plus some additional modules that
give us capabilities not available
inside browsers. we can work with the file
system or the network and so on both
chrome and node share the same
JavaScript **engine** but they provide
different runtime environments for
JavaScript.

now I've seen people comparing node to c-sharp or Ruby or some other programming languages but this
comparisons are fundamentally wrong
because node is not a programming
language it's like comparing a car with
an apple by the same token note should
not be compared with frameworks such as
a spool of meth or rails or Django and
so on these are frameworks for building
web applications note is not a framework
it's a runtime environment for executing
JavaScript code.

## how node works

node applications are highly scalable and
this is because of the ***non-blocking*** or
***asynchronous*** nature of node .

### Asynchronous Architecture

what asynchronous mean?
let me give you a metaphor, imagine you go to a restaurant
a waiter comes to your table takes your order and gives it to the kitchen then he move on to serve another table while the chef is preparing your meal, so the same person can serve many different tables. they don't have to wait for the chef to cook one meal before they serve another table this is what we call
non-blocking or asynchronous architecture and this is how node
applications work.

the waiter is like a thread allocated to handle a request so a ***single thread*** is used to handle multiple requests.

in contrast to non-blocking or asynchronous architecture we have ***blocking*** or ***synchronous architecture***
let's see how that works.

so back to our restaurant example, imagine you go to
another restaurant and in this restaurant a waiter is allocated to you he take your order and give it to the kitchen now he is sitting in the kitchen waiting for the chef to prepare your meal and at this time he is not doing anything else he is just waiting. he is not going to take an order from
another table until your meal is ***ready*** .this is what we call ***blocking*** or ***synchronous architecture*** and that's how applications built with frameworks like
ASP.net.

in node we have a ***single thread*** to handle all requests when a request arrives that single thread is used to handle that request if we need to query a database, our thread doesn't have to wait for the database to return the data
while the database is executing our query that thread will be used to serve another client when the database
prepares the result it puts a message in what we call an ***event queue*** .

node is continuously monitoring this queue in the background
when it finds an event in this queue it will take it out and process it.

this kind of architecture makes node ideal for building applications that include a lot of disk or network access, we can serve more clients without the need to
throw in more hardware and that's why node applications are highly scalable.

in contrast node should not be used for CPU intensive applications like a video encoding or an image manipulation
service in this kind of applications we have a lot of calculations that should be done by CPU and few operations that
touch the file system or the network since node applications are single threaded when performing the calculations to serve one client other clients have to wait.

and that's why node should not be used or CPU intensive
applications it should only be used for building ***data intensive*** and ***real-time applications***.

## Node module system

now  we're going to look at the ***module*** system in node. you will learn what modules are, why we need them, and
how they work.

throughout this section we'll explore a feel of the modules built into the core of node such as **operating system** ,**file system** , **events** and **HTTP** .

we  will also see how to create our own modules now let's get started .

we use the ```console.log()``` function to log something on the console. now this console object is what we call a ***global object*** so it's part of the global scope which means we can access it anywhere and in any files.

we have a bunch of other **objects** and functions that are also globally available in node for example :

we have ```setTimeout()``` which you haveprobably seen before we use this to call a function after a delay like one second two second whatever so this is just part of the **standard JavaScript** we can use this on the client we can use this
inside of a browser or inside of node we also have ```clearTimeout()``` similarly we have ```setInterval()``` which we use to repeatedly call a function after a given delay we also have ```clearInterval()``` which we use to stop that
function from being called repeatedly.

so these are the ***global*** objects in JavaScript.

now in browsers we have this **window** object that represents our global scope so all the variables and functions that are defined globally we can access them via this **window** object so we can call ```window.console.log()``` or simply just
```console.log()``` the JavaScript engine will prefix this statement with window because that's where this object is defined.

## Http module 

The HTTP core module is a key module to Node.js networking.

The module provides some properties and methods, and some classes.

you create a web server by playing arround this module 

working with http is very low level 

so we use framworks such as express to make these thing easier

## express js

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.