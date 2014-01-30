textareaHelper
--------------

A small library that mirrors a textarea's content onto a div to add some interesting functionality.

[Demo](http://jsfiddle.net/5KqmF/112/).

# Running the tests

    open test/tests.html


# Usage

    $('#myText').textareaHelper();
    $('#myText').textareaHelper(method);

## Methods

### .textareaHelper('height')

Gets the textarea's content height.

### .textareaHelper('caretPos')

Gets the XY coordinates of the textarea's caret relative to the textarea. You can pass an index, which will return the XY coordinates of that index in the textarea relative to the textarea.  

### .textareaHelper('setCaretPos', index)

Sets caret position

### .textareaHelper('getOriginalCaretPos')

Gets the index of the caret position

### .textareaHelper('destroy')

Destorys the helper mirror object. Use for cleanup.

# License

MIT
