# About this React app

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This project is [deployed on Netlify](https://boisterous-panda-9f29a0.netlify.app/).

## Learning Concepts covered

### Nesting JSX == components

1. Consider the App.js file's structure in the second commit in this repo.
```jsx
<div className="App">
    <h1>Hello World!</h1>
    <h2>Hello again!</h2>
    <h3>Hello yet again!</h3>
    <h4>Once again!</h4>
</div>
```

What if I wanted to "group" all the headings together under a single label?

This is a very easy thing to achieve, using components.

In the third commit in this repo, I'm introducing another component, named `Headings.js`, and I'm taking the h1, h2, h3, and h4 elements, and returning them from this `Headings` component. In that same commit, I'm also importing and using the `<Heading />` JSX element inside `App.js`.

### Tasks

1. Your task is to add an h5 and an h6 to the `Headings` component, with some custom text of your own choosing. Note: The solution can be found in commit number 4.
