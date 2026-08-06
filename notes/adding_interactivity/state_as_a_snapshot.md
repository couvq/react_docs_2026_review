* Setting state requests a new render
* React stores state outside of your component
* When `useState` is called, React gives your component a snapshot of its state for that render
* Every render creates new variables and event handlers, they don't "survive" between renders
* Every render will see the snapshot of state for that particular render (and event handlers inside it)
* Event handlers created in the past have the state values from the render in which they were created.
