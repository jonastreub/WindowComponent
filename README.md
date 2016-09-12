# WindowComponent

Allows for quick and easy creation of Mac and Browser windows. Ideal for making responsive designs.

Note: be sure not to use `window` and `document` as variable names. These names are reserved and will break your prototype.

## Example

- [Mac Desktop](http://share.framerjs.com/x4681kxzyizk/)

## Properties

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
