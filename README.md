# React Testing

This repo builds upon the topic of client-side testing by extending it into the realm of React.

## Project Description

The objectives of this repo are the following:

- To write tests for a React application using Jest and Enzyme. These two libraries are commonly used in production for testing React components and applications.
- To practice reading over and understanding code which you did not write, but that you do need to test.


I'll be using [Jest](https://facebook.github.io/jest/docs/en/expect.html) and [Enzyme](http://airbnb.io/enzyme/) in order to test React components.

## Initialization and Setup

You can run the complete application by installing Node modules with the `npm` command, and then running `npm start`.

Run `npm test` in order to run the test suite. Of course, this isn't going to actually test anything yet, since you haven't written the tests!

## Stretch Goals

Add additional test files `calculate.test.js` and `operate.test.js` in the `tests` directory to test the files in the `./src/logic` folder. The files in this directory aren't React components, so for testing them you'll actually just be using Jest without Enzyme.
