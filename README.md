# Smooth Scroll To JS

## TODO:
- [  ] Clean up the code.
- [  ] Write up some more documentation
- [  ] Create a demo page to test functionality against
- [  ] Unit and functional tests
- [  ] Allow for custom animation functions


## API:
> `smoothScrollTo(options)`

### **`options`**

**`to`** - *`required`*

The destination *`Dom Node`* to which the container must scroll.

**`container`** - *`[window]`*

The scrollable container. Its scroll position will be animationed by smoothScrollTo

**`duration`** - *`[20]`*

The duration of the animation in number of steps. `1` is instant.

**`data`** - `[true]`

An object that will be returned when the animation ends