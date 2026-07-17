* Event handlers must be passed, not called! `onClick={handleClick}`, not `onClick={handleClick()}`. The former is correct while the latter will call the `handleClick` function each time the component renders, which could lead to unexpected bugs.
* Conventionally, event handlers passed as props start with `on` while event handlers defined inside of a component locally start with `handle`.
* Just like in javascript, events propogate upwards in the DOM which can sometimes lead to unexpected bugs. If you want to stop this behavior your would call `event.stopPropogation()`.
* Some events have default behavior. For example, clicking a button inside of a form will reload the page by default. If you want to stop this behavior, you would call `event.preventDefault()`.
