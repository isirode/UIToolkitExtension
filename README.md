# UIToolkitExtension

This is a Unity UI Toolkit library containing elements not provided by Unity:
* A select (in the same spirir as the one in HTML)
* A dropdown menu

![The menu](/Documentation/Resources/Menu.png)

## How to use

Clone the project and export the content as a package.

You can then customize the USS.

## Examples

Examples are provided in the Examples folder, one for the menu, two for the Select.

## Requirements

I am using Unity 2021.3.3f1.

## Known issues

If you attempt to use the Select inside a UI Document, as a node, if there is another input below in the hierarchy (a TextField for instance), the Select's dropdown will be draw behind the input.

As there is no z-index in Unity, there is no way to prevent this to happenning.

This is not occuring if you are instantiating it in a C# script. 

## Release Notes

### 0.0.1

- Initial release of the library.

