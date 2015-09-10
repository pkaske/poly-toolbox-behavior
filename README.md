# poly-toolbox-behavior
Simple polymer behavior that provides some useful functions.

## Functions

Visit the [component page](http://pkaske.github.io/poly-toolbox-behavior) for demos and in-depth docs.

### closest(node, selector)
Find closest parent node matching the selector.
First node that's checked is `node` itself.

### arrayMove(oldIndex, newIndex)
Moves an array item from `oldIndex` to `newIndex`.
This is done on the array itself, without returning a copy.
