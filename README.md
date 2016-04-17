jQuery - Copy to clipboard Plugin
================

jQuery Copy to clipboard plugin - copy any text to the user site's clipboard. Operates on the basis of creating hidden text field and executing "copy" command.

You can see [DEMO](http://mmkyncl.github.io/jquery-copy-to-clipboard/) page.


## Usage

### 1. Including jQuery

Be sure you have jQuery included in your website.

```html
<script type="text/javascript" src="/MYPATH/jquery.js"></script>
```

### 2. Include copy-to-clipboard script

```html
<script type="text/javascript" src="/MYPATH/jquery.copy-to-clipboard.js"></script>
```

### 3. Apply on any element

Works on any kind of element.

There are two ways to use this plugin.

- 1. Apply CopyToClipboard plugin with a JS Code.

```javascript
$(document).ready(function() {
  $('.element').CopyToClipboard();
});
```

- Add data-clipboard attribute to any HTML element, executes on click.

```html
<button data-clipboard-text="Text to copy.">Copy me!</button>
```

- or with jQuery selector...

```html
<button data-clipboard-target=".element">Copy another element's value!</button>
```

### 4. More information

jQuery CopyToClipboard is based on creating hidden text field, inserting text and executing "copy" command.
