# FUN-Model

## About
I spent long time in last month in flux like libraries and there is my notes for presentation purposes. I hope that should be helpful for you in your decisions about flux. Why fun?
* f - functional
* u - unidirectional
* n - I don't know
* model - just Model or ViewModel

## Resources
### Bobril
* https://github.com/Bobris/Bobril

### Flux
* https://facebook.github.io/flux/docs/overview.html#content

### Reflux
* https://github.com/spoike/refluxjs

### Redux
* reducers + flux
* immutability
* pure functionality
* https://www.youtube.com/watch?v=xsSnOQynTHs
* https://github.com/gaearon/redux

## Notes
### Common keywords
* 1 store with 1 application state
* application state is composition of substates
* action calls has specified cursor and own handler function
 * replaces part of global state
 * creates new state instance
* Bobril and ReactJs is only rendering tool
 * "components are stateless"
* support for unit testing
