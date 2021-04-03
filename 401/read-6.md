# Authentication

## Singleton

In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance (1)

## Singleton pattern can be used with Node modules .

as in all other programming language we need an static method responsible for create the instance { if the instance is null create new instance else return it } 

the trick is no private constructor in javascript , the solution is to create a class and simply not export it , export an interface class that interact with it 
notice the interface class should throw an error in the constructor because we dont need to instatiate this object with new keyword

## If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

Singleton 


## References

1. https://en.wikipedia.org/wiki/Singleton_pattern