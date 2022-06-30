# Forms and JS Events

## HTML: Forms

1. Forms allow the user to interact with application, as they are the primary way the application gains data from the user.

2. Some things to keep in mind when designing ui/ux:

    1. Minimize the size of the form.

    2. Make the interactable objects clear.

    3. Put elements where people will expect them.

3. There are some useful elements specifically for creating forms.

    1. `<form>` is the container element or a form (shockingly).

    2. `<label>` tells the user what the form piece is. It has a `for` attribute to connect it to its partner.

    3. `<input>` is an empty element that produces a single-line interactable object. It has an `id` attribute to connect it to its `label` and a `type` attribute that changes how it appears and behaves.

    4. `<textarea>` produces a multi-line text field. It also has an `id` attribute.

    5. `<button>` is a button (good job, semantic tags).

## JS: Introduction To Events

1. An event is anthing that happens in a system that the program can react to.

2. An event listener method requires an event that triggers it and the function it triggers.

3. The `target` property of an event object is a reference to the element that the event occurred on.

4. Event capturing starts at the outermost ancestor registering the event, then moving down child by child to the inner-most child for which the event registers. Event bubbling then starts at the innermost childand runs the event handler before moving up parent by parent and doing the same (unless stopped by a `stopPropagation`).
