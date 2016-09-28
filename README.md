# WindowComponent

Allows for quick and easy creation of Mac and Browser windows. Ideal for making responsive designs.

Note: be sure not to use `window` and `document` as variable names. These names are reserved and will break your prototype.

## Example

- [Basic Setup](http://share.framerjs.com/cvnfqelnpkto/)
- [Mac Desktop](http://share.framerjs.com/pehxi6fey0eo/)

## Properties

- **`resizable`** *\<bool>*
- **`minWidth`** *\<number>*
- **`minHeight`** *\<number>*
- **`toolbarHeight`** *\<number>*
- **`topConstraint`** *\<number>*

```coffee
{WindowComponent} = require "WindowComponent"

docWindow = new WindowComponent
```

## Events

- **`onResize`** (window, content *\<layer>*)

```coffee
docWindow.onResize (window, content) ->
	# update layout
```
