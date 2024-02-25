# What is React?

- React is a javascript library for building user interfaces, particularly single page applications.
  
# Who made React?

- React was creatd by Jordan Walke, a software engineer at Facebook.

# What is Babel?

- Babel is a javascript compiler that allows developers to write code using the latest ECMScript standards and than convert it into backward-compatible versions of javascript that can run in older browsers.
  
# How does Babel convert HTML code in React into valid code?

- Babel primarily transpiles JSX syntax, which is often used in React, into regular JavaScript code that browsers can understand.

# What is ReactDOM used for? Write an example?

- ReactDOM is a package that provides DOM-specific methods for React. It's used to render React components into the DOM.
Example:
import React from 'react';
import ReactDOM from 'react-dom';

const element = <h1>Hello, world!</h1>;
ReactDOM.render(element, document.getElementById('root'))

# What are the packages that you need to import for React to work with?

- You typically need to import react and react-dom packages to work with React.

# How do you add React to a web application?

- You can add React to a web application by including the React and ReactDOM libraries in your project and then writing components using React syntax.

# What is React.createElement?

- React.createElement is a function used to create React elements, which are the building blocks of React applications.

# What are the three properties that createElement accepts?

- React.createElement accepts three arguments: the type of element (such as a string representing an HTML tag or a React component), the element's properties or attributes (often referred to as props), and the element's children.

# What is the meaning of render and root?
- Render is a method provided by ReactDOM that takes a React element and mounts it into the DOM. root typically refers to the root DOM node where the React application will be rendered. In the example above, document.getElementById('root') specifies the DOM node with the id of 'root' where the React element will be rendered.
