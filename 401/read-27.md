# Props and State

## Does a deployed React application require a server?

You don’t necessarily need a static server in order to run a Create React App project in production. It also works well when integrated into an existing server side app.

## Why do we prefer to test a React application at the behavior rather than the unit level?

When choosing testing tools, it is worth considering a few tradeoffs:

Iteration speed vs Realistic environment: Some tools offer a very quick feedback loop between making a change and seeing the result, but don’t model the browser behavior precisely. Other tools might use a real browser environment, but reduce the iteration speed and are flakier on a continuous integration server.
How much to mock: With components, the distinction between a “unit” and “integration” test can be blurry. If you’re testing a form, should its test also test the buttons inside of it? Or should a button component have its own test suite? Should refactoring a button ever break the form test?

## What does npm run build do?

npm run build runs the script "build" and created a script which runs your application

## Describe the actual composition / architecture of a React application

The key feature of React is composition of components. Components written by different people should work well together. It is important to us that you can add functionality to a component without causing rippling changes throughout the codebase.

## Term

### BDD

Behaviour Driven Development (BDD) is a synthesis and refinement of practices stemming from Test Driven Development (TDD) and Acceptance Test Driven Development (ATDD). BDD augments TDD and ATDD with the following tactics:

Apply the “Five Why’s” principle to each proposed user story, so that its purpose is clearly related to business outcomes
thinking “from the outside in”, in other words implement only those behaviors which contribute most directly to these business outcomes, so as to minimize waste
describe behaviors in a single notation which is directly accessible to domain experts, testers and developers, so as to improve communication
apply these techniques all the way down to the lowest levels of abstraction of the software, paying particular attention to the distribution of behavior, so that evolution remains cheap .

### Acceptance Tests

An acceptance test is a formal description of the behavior of a software product, generally expressed as an example or a usage scenario. A number of different notations and approaches have been proposed for such examples or scenarios. In many cases the aim is that it should be possible to automate the execution of such tests by a software tool, either ad-hoc to the development team or off the shelf.

Similar to a unit test, an acceptance test generally has a binary result, pass or fail. A failure suggests, though does not prove, the presence of a defect in the product.

Teams mature in their practice of agile  use acceptance tests as the main form of functional specification and the only formal expression of business requirements. Other teams use acceptance tests as a complement to specification documents containing uses cases or more narrative text.

