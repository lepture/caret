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

### .prepend(str)

Insert before caret:

```js
caret.prepend('<strong>enhance</strong>')
```

### .append(str)

Insert after caret:

```js
caret.append('<strong>enhance</strong>')
```

### .parentUtil(tags)

Recursive find parent node util it matches the tags.

```js
caret.parentUtil('ul')
```

### .save

Save caret position.

### .restore

Restore caret position.

### .on(event, fn)

Bind delegate event handler.

### .off(event, fn)

Unbind delegate event handler.

## Events

Events that caret emits.

### select

When it has selected text.

### change

When caret moved.

## License

MIT
