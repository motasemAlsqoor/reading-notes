# EJS

Embedded JavaScript templating.

What is the "E" for? "Embedded?" Could be. How about "Effective," "Elegant," or just "Easy"? EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript.(1)

## Features (1)

1. Fast compilation and rendering

2. Simple template tags: <% %>

3. Custom delimiters (e.g., use [? ?] instead of <% %>)

4. Sub-template includes

5. Ships with CLI

6. Both server JS and browser support

7. Static caching of intermediate JavaScript

8. Static caching of templates

9. Complies with the Express view system


## Install

```$ npm install ejs```

## use 

```let ejs = require('ejs');```

```let people = ['geddy', 'neil', 'alex'];```

```let html = ejs.render('<%= people.join(", "); %>', {people: people});```

## References
1. https://ejs.co/