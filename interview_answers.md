# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

Context API solves the problem of prop drilling.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions are packets of information that contain an action type and associated data. Reducers are pure predictable immutable functions that execute actions on state data. The store is a JavaScript object that contains the state for the application. The store is known as the single source of truth in a redux application because it contains our state.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

Redux-thunk allows us to return functions and action objects. It changes our action-creators because it allows our action-creators functions to dispatch actions themselves.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

My favorite state management system I've learned has been Redux because it allows us to keep our code more organized by keeping all our stateful/logic data in one place and gets rid of prop drilling.