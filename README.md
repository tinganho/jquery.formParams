jquery.formParams
=================

jQuery plugin for serializing forms to JS objects

Returns an object of name-value pairs that represents values in a form. It is able to nest values whose element's name has square brackets.

Example html:
```html
<form>
  <input name="foo[bar]" value='2'/>
  <input name="foo[ced]" value='4'/>
<form/>
```

Example code:
```javascript
$('form').formParams() //-> { foo:{bar:2, ced: 4} }
```
