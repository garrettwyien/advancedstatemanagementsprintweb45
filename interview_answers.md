# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

Context API helps solve the problem of deeply nested components being deprived of efficient access to data. Instead of being passed down one step at a time through each child component to get where it needs to go, data can be passed down directly from ancestor to child through provider-consumer pairings. 

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Reducers are functions that take current state and an action as arguments and then change the state according to those paramteres. Actions are two property objects, type and payload, that describe what the action is doing and what data is being used for that action, respectively. Reducers receive these actions which inform them how to alter the state. The store is an object that holds state for our application. When state is updated, it is cloned and then modified and then replaces the original state. Because the original state is never changed, it is known as a single source of truth. 


3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

Redux-thunk allows us to create async reducer functions and subsequently make API calls from our action creators. It changes our action creators by making them asynchronous, too. 


4. What is your favorite state management system you've learned and this sprint? Please explain why!

I barely understand almost all of it. I'll answer this when I have a stronger grasp on the material. 