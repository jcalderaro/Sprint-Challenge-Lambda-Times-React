## Self-Study/Essay Questions

- [x] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

    Proptypes are used for defining data or properties and passing it down from parent to child copmonents. 
    It can act as an organizational check to see if the code is working or if an error will occur.

- [x] Describe a life-cycle event in React?

    A life-cycle event in React has three phases. This is broken down into Mounting, Updating, and Unmounting. However sometimes you can also break it down into basically is a component being mounted to the DOM, or is a component getting more data. Usually it starts with componentDidMount() after render() is used, then when the data needs to be removed or updated we use componentWillUnmount() to continue. 

- [x] Explain the details of a Higher Order Component?

    A Higher Order Component is a function that accepts React components as parameters. It retursn a new component and can add data or features onto an existing component. 

- [x] What are three different ways to style components in React? Explain some of the benefits of each.

    The three ways to style components in React are through: CSS, SCSS, or just Styled Components.
    
    (1) CSS allows you to create files for each component or import the file over. It's the most basic. 
    (2) SCSS is a preprocessor that works with Reacts functionality to use more of CSS's ability. Like it can also use nesting, variables, mixins, and selectors among other things. This makes it a better and easier alternative to standard CSS. 
    (3) Styled components are made from referencing the library and are existing html elements.