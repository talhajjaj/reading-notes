**Introduction to React and Components**


What Is React?
React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”. 
>(React Tutorial through ‘Passing Data Through Props’ -the reference- ).


to use the react you should have some knowlodege in HTML and JavaScript , because you wil use let ,const and class and alot of javascript features. 

the components uses to tell react what the user want to see on the screen , when you change the data. 
and it takes in parameters , called props (properties) .
The render method returns a description of what you want to see on the screen. React developers use a special syntax called “JSX” because it makes  the structures easier to write.

JSX comes with the full power of JavaScript. You can put any JavaScript expressions within braces inside JSX. Each React element is a JavaScript object that you can store in a variable or pass around in your program.

the react has three components:

- Square 
- Board
- Game

The React DevTools let you check the props and the state of your React components.
There are generally two approaches to changing data. The first approach is to mutate the data by directly changing the data’s values. The second approach is to replace the data with a new copy which has the desired changes.
-Data Change with Mutation
-Data Change without Mutation
and the end result is the same..

**Function Components**

In React, function components are a simpler way to write components that only contain a render method and don’t have their own state. Instead of defining a class which extends React.Component, we can write a function that takes props as input and returns what should be rendered. Function components are less tedious to write than classes, and many components can be expressed this way.


simple example code with react :
ReactDOM.render(
  <h1>Welcome</h1>,
document.getElementById('root')
);

Rendering elements ;
it describe what you want to see on the screen .
We call this a “root” DOM node because everything inside it will be managed by React DOM.

Applications built with just React usually have a single root DOM node.
To render a React element into a root DOM node, pass both to ReactDOM.render():.
React elements are immutable ,the only way to update the UI is to create a new element, and pass it to ReactDOM.render().


components and props :
 Components are like JavaScript functions. They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen , and components can refer to other components in their output.


- All React components must act like pure functions with respect to their props.




