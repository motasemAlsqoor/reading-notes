# component

Ejs partials  mean repeatable parts of our site 

in real world application there will be a lot of code that is reused. We’ll define the reusable component  and include them where ever you need to use them 

## example of reusable component 

```nav```

```footer```

and any other component 

## Syntax for including an EJS Partial

Use ```<%- include('RELATIVE/PATH/TO/FILE') %>``` to embed an EJS partial in another file.

The hyphen ```<%-``` instead of just ```<%``` to tell EJS to render raw HTML.
The path to the partial is relative to the current file.





