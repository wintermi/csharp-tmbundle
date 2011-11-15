# C# TextMate Bundle #

This is a substantial rewrite of the original C# bundle.
It was heavily inspired by the Java bundle.

It has a hierarchical definition, allowing inner classes, etc.
The symbol list will show up to several layers deep.

Regions are marked in the symbol list as well at an appropriate depth.

# Todo #

## Planned Features ##

* Symbol List: Operators
* Parser: Accurate Property Bodies
	* Only expose get/set/add/remove keywords here
	* { #code }
* Parser: Proper function parameter lists
	* Only expose params keyword here
	* ( #builtinTypes, params )

## Known Issues ##

* Properties: Not accurate marked when { is on newline
* Control statements (if/switch) sometimes look like fcn calls
