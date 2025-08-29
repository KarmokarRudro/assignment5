Q1: Difference between getElementById, getElementsByClassName, querySelector, and querySelectorAll

getElementById → Used to select a single element by its unique id. Always returns one element.

getElementsByClassName → Selects all elements that have the same class name. Returns a collection.

querySelector → Uses a CSS selector and returns only the first matched element.

querySelectorAll → Uses a CSS selector but returns all matching elements in a list.

Q2: How to create and insert a new element into the DOM

To create: use document.createElement("tagName"). Example: document.createElement("p") creates a paragraph element.

To insert: use methods like append, appendChild, prepend, or insertBefore to place the new element inside the DOM.

Q3: What is Event Bubbling and how does it work?
Event bubbling means when an event happens on a child element, it doesn’t stop there. The event goes upward through its parent elements. For example, if you click a button inside a div, first the button’s click happens, then the div’s click, then the body, and so on.

Q4: What is Event Delegation in JavaScript? Why is it useful?
Event delegation means adding an event listener to a parent element instead of each child element separately. When a child is clicked, the event bubbles up to the parent, and the parent handles it. It is useful because it saves memory, improves performance, and keeps code simpler.

Q5: Difference between preventDefault() and stopPropagation()

preventDefault() → Stops the browser’s default action for an event. Example: stopping a form submit button from reloading the page.

stopPropagation() → Stops the event from moving upward to parent elements. Example: preventing a button’s click from also triggering the parent div’s click.
