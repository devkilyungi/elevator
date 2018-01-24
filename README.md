A JavaScript Elevator
=====================

An introduction to programming for the Internet of Things through a metaphoric code explained through blog posts.

### Demos

  * [the doors](https://webreflection.github.io/elevator/the-doors/) of a lift have at least a motor and a sensor (unless it chops people that are passing through). Doors can close or open, and everything is asynchronous and cancelable (unless you want to chop people that are passing through).
  * [the light button](https://webreflection.github.io/elevator/the light button/) does exactly what a button does, but it has an extra `switch(state)` method to switch on or off its internal light. It's important to understand that pressing the button, does not necessarily mean switching on the light. Remember, an elevator is a list of hardware driven by a controller, not a set of stand-alone modules with a proper purpose.
