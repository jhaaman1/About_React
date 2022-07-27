# About_React

## 1. What is React?

### Soln:- React is a javascript library or framework for bulding User Interface(UI). React is also made around the concept of reusable components.

## 2. Who made React?

### Soln:- Jordan Walke

## 3. What is Babel?

### Soln:- Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.

## 4. How does Babel convert html code in React into valid code?

### Soln:- Browser doesn't understand JSX out of the box, so most React user rely on a compiler like Babel or TypeScript to transform Jsx code into the javascript. So when we use JSX, the compiler transform it into the React functions calls that the browser can understand. The old jsx transform it into the React.createElement().

## 5. What is ReactDOM used for? Write an example?

### Soln:- The react-dom packages provides DOM specific method which can used at the top level of a web app to enable an efficient way of managing DOM elements of the web page. Syntax is ReactDOM.render(element, container, callback).

## 6. What are the packages that you need to import for react to work with?

### Soln:- First we need to install the npm packages which provides us facility to use the react app. Then we need to install the React packages from React doc and the we can start to use it. 

## 7. How do you add react to a web application?

### Soln:- We can add react to a web application in just few steps :- 
### Step 1: Add a DOM Container to the HTML
### Step 2: Add the Script Tags
### Step 3: Create a React Component
### That's it.

## 8. What is React.createElement?

### Soln:- Using React without JSX  is especially convenient when you don't want to set up compilation in your build environment. Each JSX element is just syntactic sugar for calling React. createElement(component, props, ...children) . So, anything you can do with JSX can also be done with just plain JavaScript.

## 9. What are the three properties that createElement accept?

### Soln:- 1. Creating new div  2. Creating new list items  3. Creating a script element type

## 10. What is the meaning of render and root?

### Soln:- The term “render prop” refers to a technique for sharing code between React components using a prop whose value is a function. A component with a render prop takes a function that returns a React element and calls it instead of implementing its own render logic.
### The root is where the application layout structure is defined. It is typically the first UI element a user interacts with. The root can be changed multiple times during the lifespan of the application.
