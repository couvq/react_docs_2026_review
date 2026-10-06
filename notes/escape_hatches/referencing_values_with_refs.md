* Refs are an escape hatch to hold onto values that aren't needed for rendering, not needed often
* Like state, refs let you retain information between re-renders of a component
* Unlike state, setting the ref’s `current` value does not trigger a re-render.
* Don’t read or write `ref.current` during rendering. This makes your component hard to predict.

