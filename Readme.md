# caret

Listen to and manipulate the text caret.

## Installation

Install with [component(1)](http://component.io):

    $ component install lepture/caret

## API

All methods are refered to the instance of `Caret`:

```js
var caret = new Caret(element)
```

### .selection()

Get the selection object.

### .range()

Get the range object.

### .parent()

The parent node of caret.

```js
var node = caret.parent()
```

### .blockParent()

Block level parent node of caret.

```js
var node = caret.blockParent()
```

### .save(range)

Save caret position.

### .restore(range)

Restore caret position.

### .on(event, fn)

Bind delegate event handler.

### .off(event, fn)

Unbind delegate event handler.

## Events

Events that caret emits.

### `select(event, selection)`

When it has selected text.

### `change`

When caret moved.

## License

MIT
