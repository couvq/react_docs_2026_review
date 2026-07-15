* Components must be pure functions in order to avoid unintended consequences. Pure components:
   1. Mind their own business, they don't change any objects or variables that existed before their creation.
   2. Same inputs, same output. The component should yield the same result provided the same inputs.  
* Rendering can happen at any time, so components should not depend on each others’ rendering sequence.
* In React there are three kinds of inputs that you can read while rendering: props, state, and context. You should always treat these inputs as read-only.
* React offers a “Strict Mode” in which it calls each component’s function twice during development. By calling the component functions twice, Strict Mode helps find components that break these rules.