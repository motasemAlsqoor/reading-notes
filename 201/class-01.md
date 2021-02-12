# Topics Summarizing

from the ducket Html book , i read the following :

* Introduction (PP.2-11)
* HTML Chapter1: "Structure" (pp.12-39)
* HTML Chapter 8: "Exrta Markup" (P.176-199)
* HTML Chapter17: "HTML5 layout" (pp.428-451)
* HTML Chapter 18: "Process & Design" (PP.452-475)

So i will summarize these topics as follow :

## 1. different ways in which people access the web

### 1. BROWSERS

People access websites using
software called a web browser.
Popular examples include
Firefox, Internet Explorer, Safari,
Chrome, and Opera.

### 2. WEB SERVER

When you ask your browser for
a web page, the request is sent
across the Internet to a special
computer known as a web
server which hosts the website

### 3. SCREEN READERS

Screen readers are programs
that read out the contents of a
computer screen to a user. They
are commonly used by people
with visual impairments.

### 4. DEVICES

People are accessing websites
on an increasing range of devices
including desktop computers,
laptops, tablets, and mobile
phones. It is important to
remember that various devices
have different screen sizes and
some have faster connections to
the web than others.

## 2. What happen when we open the browser

website, it is most likely that
your browser will be receiving
HTML and CSS from the web
server that hosts the site. The
web browser interprets the
HTML and CSS code to create
the page that you see

## Structure

In all kinds of documents, structure is very important in helping
readers to understand the messages you are trying to convey
and to navigate around the document. So, in order to learn how
to write web pages, it is very important to understand how to
structure documents

The HTML code  is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags

## DOCTYPE

Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included).
We will therefore be including
one in each example for the rest
of the book

```<!DOCTYPE html>```

## Comments in html

If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:

```<!-- comment goes here -->```

It is a good idea to add
comments to your code because,
no matter how familiar you
are with the page at the time
of writing it, when you come
back to it later (or if someone
else needs to look at the code),
comments will make it much
easier to understand

## ID ATTRIBUTE

Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Its value should start with
a letter or an underscore (not a
number or any other character).
It is important that no two
elements on the same page
have the same value for their id
attributes (otherwise the value is
no longer unique)

```<p id="pullquote">Every time I view the sea I feel a calming sense of security, as if visiting my ancestral home; I embark on a voyage of seeing.</p>```

## CLASS ATTRIBUTE

Every HTML element can
also carry a class attribute.
Sometimes, rather than uniquely
identifying one element within
a document, you will want a
way to identify several elements
as being different from the
other elements on the page.
For example, you might have
some paragraphs of text that
contain information that is more
important than others and want
to distinguish these elements, or
you might want to differentiate
between links that point to other
pages on your own site and links
that point to external sites.

```<p class="important admittance">Hours: 10:00 – 18:00 (No admittance after 17:30)</p>```

## HTML5 LAYOUT

For a long time, web page authors used ```<div>``` elements to group
together related elements on the page (such as the elements that form a
header, an article, footer or sidebar). Authors used class or id attributes
to indicate the role of the ```<div>``` element in the structure of the page.

HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already.

### The ```<header>``` and ```<footer>```

elements can be used for:

* The main header or footer
that appears at the top or
bottom of every page on the
site.

* A header or footer for an
individual ```<article>``` or
```<section>``` within the page

### THE ```<nav>``` ELEMENT

The ```<nav>``` element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.

### THE ```<article>``` ELEMENT

The ```<article>``` element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.

This could be an individual
article or blog entry, a comment
or forum post, or any other
independent piece of content.

### THE ```<section>``` ELEMENT 

The ```<section>``` element groups
related content together, and
typically each section would
have its own heading.

## PROCESS AND DESIGN SUMMARY

* It's important to understand w XX ho your target audience is, why they would come to your site, what information they want to find and when they are likely to return

* Site maps allow you to plan the structure of a site.
XX Wireframes allow you to organize the information that
will need to go on each page.

* Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.

* You can differentiate between pieces of information
using size, color, and style

* You can use grouping and similarity to help simplify
the information you present

## KEY CONCEPTS IN COMPUTER PROGRAMMING

A. What is a script and how do I create one?

B. How do computers fit in with the world around them ? 

C. How do I write a script for a web page ?

### A

A script is a series of instructions that a
computer can follow to achieve a goal.

### B

computer create models of the world using data , model use objects to represent physical things

### C

write i javascript code in file with js extension
