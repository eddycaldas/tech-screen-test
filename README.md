# CSS

- What are CSS selectors?
- What is the specificity of those selectors?
- What is the difference between `.class1.class2` and `.class1 .class2` as a selector?
- How do you center something in CSS?
- How do floats work? 
- How do you get something to not display using CSS?

# JS

- *What are let and const?*
    .Let allow declare variables inside of a scope. (inner block)
    .Const is declared as a universal, and its available to any function, and cannot
      be changed.
- *What is var?*
  var is a declaration of a variable. it defines variable globally or locally to
  an entire function regarless of the block scope.
- *How is var different than let?*
  the mix of those two above
- *How do you define a global variable?*
  Its a variable defined outside of the function definition, its value is available
  and modifiable through the program.
- *How do you define a global variable inside of a function?*
  By  declaring the variable outside the function, then assigning its value inside of it.
- *What does iife mean?*
  iife: Immediately invoked function expression. It'a function that has to run
  as soon as is defined.
- *What's a closure?*
  A closure is an inner function that has access to the outer function's function variable.
  A closure has access to three scope chains (variable defined within its curly brakes, the
    outer function variables and the global variables.)
- *How does event bubbling work?*
  Its related to the order in which event handlers are called when one element
  is nested inside a second element and both elements are registered a listener for the 
  same event.
- How do you avoid event bubbling?
- What is the difference between == and ===?
- What is the difference between null and undefined?
- What are the primitive data types?

# React

- *What is the one lifecycle hook that is in every class component?*
  render
- *Name as many lifecycle hooks as you can?*
  render
  didUpdate
  didMount
  willUnmount
  willMount
  willReceiveProps
  shouldUpdate
  willUpdate
- *What is the difference between state and props?*
    .State refers to the state of the component and only can be used and modified 
    from inside of it.
    .Props makes components to be reusable by giving components the ability to 
    pass data from their parent components.
- *Can you set state more than once?*
  yes, everything will be updated at once. That's called batching.
- *How does React use the virtual DOM?*
  .A virtual DOM object is a representation of the DOM object, a lightweight copy.
  .Virtual DOM object has the same properties as the DOM object.
  .When virtual DOM object is updated, react compares it with the previous
    virtual DOM snapshot that was taken before the update, then react figures out
    which virtual DOM object was changed (diffing), and updates it.
  