* Event handlers run in response to specific interactions.
* Effects run whenever synchronization is needed.
* Logic inside event handlers is not reactive.
* Logic inside Effects is reactive.
* You can move non-reactive logic from Effects into Effect Events.
* Only call Effect Events from inside Effects.
* Don’t pass Effect Events to other components or Hooks.