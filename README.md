# meteor-htmldiff
### HTML Diffing in JavaScript (ok, CoffeeScript actually.). repackaged for Meteor


`meteor-htmldiff` is a meteor package of https://github.com/tnwinc/htmldiff.js.git

This is diffing that understands HTML. Best suited for cases when you
want to show a diff of user-generated HTML (like from a wysiwyg editor).

##Install

`meteor add long:htmldiff`

##Usage
You use it like this:
```coffee
  console.log htmldiff '<p>this is some text</p>', '<p>this is some more text</p>'
```
And you get:

```html
<p>this is some <ins>more </ins>text</p>
```

Licensed under the MIT License. See the `LICENSE` file for details.
