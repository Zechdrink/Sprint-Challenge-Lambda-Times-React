
- [1] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

        Prop-types define which props are required and define the type. Prop types are important
        because it is easier for a developer to check what props are required and what
        type they should be. React also gives you a message in the console in the event of an error, 
        and tells you what is wrong/missing and at what render method the issue is.

- [2] Describe a life-cycle event in React?

        The lifecycle can be broken down in 3 stages:
        The Birth/Mounting Phase which consists of when the component is being created from ground up,
        the initial data you have access to is defined on the constructor of this phase and the render 
        method gets invoked as well as componentDidMount getting called.

        The Growth/updating phase which is where setState() can be used to change a components state
        data, forcing a call to render.

        Death/un-mounting phase which is when a component is removed from the screen.

- [3] Explain the details of a Higher Order Component?

        Essentially, a Higher Order Component is a component that takes in other components as parameters
        and returns them with additional functionality that is dependent upon whatever the HOC is set to do.
        For example, in class we created a Higher Order Component that accepted two components as arguments and 
        then only returned one or the other, contingent upon what the state was set to.

- [4] What are three different ways to style components in React? Explain some of the benefits of each.

        #1.) Styled Components: This is a library that makes it possible for us to use our css inside of our JS files,
        which in and of itself is a benefit because you can write code with less files. 

        #2.) Good old fashioned CSS pages: It's familiar and intuitive, plus you don't have to import anything into your files
        to use it. But it does make your folders feel kind of crowded and messy when you are creating css files everywhere.

        #3.) Bootstrap/ReactStrap is a styling library for components: It's convenient because there are pre-built styled
        components built into the library that can be used.
