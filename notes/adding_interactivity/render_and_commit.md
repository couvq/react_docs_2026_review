React updates the screen in three steps:
1. Trigger - either initial render or trigger a state update that will cause a re-render.
2. Render - Run component functions whose state have changed. This is recursive, so if the component has children those child component functions will be called as well until we hit the end of the tree.
3. Commit - React applies the minimal amount of updates needed to the DOM based on what has changed, if nothing has changed then nothing rerenders.