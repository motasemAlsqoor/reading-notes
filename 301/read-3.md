# MUSTACHE and FLEXBOX

## MUSTACHE

Mustache.js make it easier to separate data from presentation 
allow you to write code that is easier to understand , maintain and extend .


### Include Mustache.js in your web page

To use mustachi.js you must include it to your page .

you must include the script with the mustache.js before any script in your page.

In addition to being a package to be used programmatically, you can use it as a command line tool.

You can get Mustache via npm.

$ npm install mustache --save

You can also download it as a js file and simply include it to your project 

### Html template 

```'<p>{{data}}</p>'```

```{{data}}``` this called a delimeter and it simply it tell the mustach to put data here 


### Render the template in html

you use ```Mustache.render(template,data)``` in order  render the template in html .

 ex : 

 ```var template = '<p>{{data}}</p>'```

 ``` var data='myName'```

 ```$('body').append(Mustache.render(template,data))```

 ## Flexbox

 'The specification describes a CSS box model optimized for user interface design. In the flex layout model, the children of a flex container can be laid out in any direction, and can “flex” their sizes, either growing to fill unused space or shrinking to avoid overflowing the parent. Both horizontal and vertical alignment of the children can be easily manipulated. Nesting of these boxes (horizontal inside vertical, or vertical inside horizontal) can be used to build layouts in two dimensions'.(1)

 

 ## References

 1. https://www.w3.org/TR/css-flexbox/