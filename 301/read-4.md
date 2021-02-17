# GridLayout && Regulare expressions


# GridLayout

"CSS Grid Layout excels at dividing a page into major regions or defining the relationship in terms of size, position, and layer, between parts of a control built from HTML primitives.

Like tables, grid layout enables an author to align elements into columns and rows. However, many more layouts are either possible or easier with CSS grid than they were with tables. For example, a grid container's child elements could position themselves so they actually overlap and layer, similar to CSS positioned elements."(1)

The grid container class must hold a grid value in the display property

The anatomy of a grid is made up of several parts. Not every part is present in every grid; it depends on the sort of grid. Here we will look at the most important parts of a grid.(2)

ex :

```display: grid;```

ex :

```<div class="grid-container">```

  ```<div class="grid-item1">1</div>```

  ```<div class="grid-item2">2</div>```

  ```<div class="grid-item3">3</div>```

  ```<div class="grid-item4">4</div>```

```</div>```

distance between the units can also the configure the gaps by entering
 ```grid-column-gap``` and ```grid-row-gap```

## reguler expressions 

a way for  describing strings by describing its components symbols .

and also describe the relations between these symbols .

ex :

```var rE = /hello/;```

```var sentence = 'hello world';```

```var result = rE.test(sentence);```

```console.log(result); // returns true```




# References
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
2. https://visme.co/blog/layout-design/