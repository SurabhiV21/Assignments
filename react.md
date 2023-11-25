1. What is React?

React is a JavaScript library for building user interfaces. It's maintained by Facebook and a community of individual developers and companies.

2.Who made React?

React was developed by a software engineer named Jordan Walke at Facebook.


3.What is Babel?

Babel is a JavaScript compiler that allows developers to write code using the latest ECMAScript standards and then converts it into JavaScript code that can run in older browsers.

4.How does Babel convert HTML code in React into valid code?

Babel primarily works with JavaScript, not HTML. React code is typically written in JSX, a syntax extension for JavaScript recommended by React. Babel translates JSX into regular JavaScript that browsers can understand.

5.What is ReactDOM used for? Write an example.

ReactDOM is the package responsible for rendering React components into the DOM. For example:
jsx

import React from 'react';
import ReactDOM from 'react-dom';

const element = <h1>Hello, React!</h1>;
ReactDOM.render(element, document.getElementById('root'));

6. What are the packages needed to import for React to work with?

The core packages are react and react-dom. You also need a build tool like Webpack and a package manager like npm or Yarn.

7.How do you add React to a web application?

Install React using npm or Yarn, set up a build system (e.g., Webpack), create React components, and use ReactDOM to render them into the DOM.

8.What is React.createElement?

React.createElement is a function used to create React elements, which are the building blocks of React applications.

9.What are the three properties that createElement accepts?

The type of element (e.g., HTML tag or React component), optional properties or attributes, and the content of the element.

9.What is the meaning of render and root?

render is the process of converting React elements into the actual UI that users see. The "root" usually refers to the root DOM node where your React app will be rendered, often identified by an HTML element with an id of '
