# React

React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.

## JSX 

React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

## Name 5 Javascript UI Frameworks (other than React)

Angular

Vue

BackBone

Ember

Meteor

## What’s the difference between a framework and a library?

The technical difference between a framework and library lies in a term called inversion of control.

When you use a library, you are in charge of the flow of the application. You are choosing when and where to call the library. When you use a framework, the framework is in charge of the flow. It provides some places for you to plug in your code, but it calls the code you plugged in as needed.


## Term 

Rendering : the process of drawing elements on the screen

Templates :  blueprint of an model

State :  React components can have state by setting this.state in their constructors. this.state should be considered as private to a React component that it’s defined in
