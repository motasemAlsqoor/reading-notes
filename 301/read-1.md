# Responsive Web Design RWD 

"is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes."(1)

Responsive web design is broken to three ingredients :

    1. flexible grid
    
    2. media queries
    
    3. flexible media

## Flexible Grid

a responsive web design practice  that build a website layout with  flexible grid to holds web elements that dynamically resizing  to any width . 

Flexible grids are built using relative length units, most commonly percentages or em units. These relative lengths are then used to declare common grid property values such as width, margin, or padding.(2)

## Media Queries
the W3C created a list of media types (http://bkaprt.com/
rwd/26/), attempting to classify each browser or device under a broad, media-specific category. The recognized media types are: all, braille, embossed, handheld, print, projection, screen, speech, tty, and tv.

In practice, that meant customizing the media attribute of a link
ex :
```<link rel="stylesheet" href="common.css" media="all" />```
```<link rel="stylesheet" href="style.css" media="screen" />```
```<link rel="stylesheet" href="paper.css" media="print" />```

these specifications suggest the browser would identify itself as belonging to one of the media types

if the browser was runnung on desktop the the *common* and *style* sheet will be applied to the document and so on .

another way to specifications is done by create @media block

ex :

```@media screen {```

  ```body {```

  ```font-size: 100%;```

```}```

```}```

```@media print {```

```body {```

```font-size: 15pt;```

```}```

```}```


## Flexible Media
 
flexible media stand for making the media scalable  such as images .

One quick way to make media scalable is by using the max-width property with a value of 100%. Doing so ensures that as the viewport gets smaller any media will scale down according to its containers width. (2)

```img, video, canvas {```

  ```max-width: 100%;```
  
```}```


## quiz
1) what does it take to create a responsive design?

    1. flexible grid
    
    2. media queries
    
    3. flexible media


## References
1. https://en.wikipedia.org/wiki/Responsive_web_design
2. https://learn.shayhowe.com/advanced-html-css/responsive-web-design/


