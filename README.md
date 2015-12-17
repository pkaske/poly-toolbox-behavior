# poly-toolbox-behavior
Simple polymer behavior that provides some useful functions.

## Functions

Visit the [component page](http://pkaske.github.io/poly-toolbox-behavior) for demos and in-depth docs.

### closest(node, selector, pierce)
Find closest parent node matching the selector.
First node that's checked is `node` itself.
If `pierce` is `true` the method will travel even through shadow dom boundaries.

### arrayMove(oldIndex, newIndex)
Moves an array item from `oldIndex` to `newIndex`.
This is done on the array itself, without returning a copy.

### getElementIndex(el)
Gets the index of `el` in its parent `children` collection.

### waitFor(testFn, maxTries)
Iterates `testFn` till it returns true. Returns a promise that's resolved if successful.
Useful to wait for a element to render, for example. Uses `requestAnimationFrame`.
