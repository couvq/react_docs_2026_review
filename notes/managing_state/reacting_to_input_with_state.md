* Imperative vs Declarative UI programming. Iterative UI programming involves writing out step by step what needs to change in the UI, in Javascript this looks like using DOM apis to describe what changes for each Element. Declarative UI programming involves describing the different states your app can be in and how to move between the states, the UI library handles the DOM manipulation stuff under the hood for you. React is a Declarative UI library.
* When developing a component:
    1. Identify all its visual states.
    2. Determine the human and computer triggers for state changes.
    3. Model the state with useState.
    4. Remove non-essential state to avoid bugs and paradoxes.
    5. Connect the event handlers to set state.
* Article actually suggested modeling out your state with a state machine diagram which I am a fan of.