1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object?

-concat, map, Object.assign
-We use Object.assign()

1.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

-Actions tell reducers what function we should run and what data to pass

 -Reducers recieve actions and state in order to implement a new state

 -A store holds the application's state

 -Stores are single sources of truth because they hold the state and all relevant data at that time.

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?

-An applications state is global however a components state is local to that component
-When you want to use another components state you should use application state, however use component state if you are working locally or are passing props.

1.  What is middleware?

- It is a function which is invoked after an action but before a reducer

1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

-Redux thunk is a middleware, it allows us to return functions instead of actions.

1.  Which `react-redux` method links up our `components` with our `redux store`?

-Connect