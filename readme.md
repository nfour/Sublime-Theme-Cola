## Cola, it's a kind of Soda

A [Soda](https://github.com/buymeasoda/soda-theme) variant theme for ST3 3062+.
Because Soda is apparently abandoned and we can't have that.

![Cola](http://i.imgur.com/zj6q7yS.png)

### Features and Differences
- Sidebar icon support
- Darker and less overall harsh contrast, while not being unreadable
- Improved status bar sharpness and border styling
- Tabs
	- Taller tabs, 30px
	- Slightly greater horizontal tab padding
	- All tabs are always minimal width, ensuring symetrical padding
	- Added `show_tab_scroll_buttons` option.
		- By default tab scroll buttons (left side of tab bar) are hidden. The dropdown can be disabled as usual.
- Sidebar
	- Maintains a left-indent of 16px, aligning open files, headings and folders.
	- Increased row bottom padding by 1px
	- Headings (FOLDERS, OPEN FILES) are now very low contrast as they are least important
	- Folders are transparent when not selected, further directing importance
	- Added hover effect to rows
	- Slimmed up horizontal padding, sidebar is far more succinct in space while not cramped
	- Fixed sidebar titles causing their own indentation

### Install
- Install via Package Control or clone this repo as `./Data/Packages/Theme - Cola`.
- Use the package `themr` to switch themes, or edit your preferences file.

### Want to customize something?

Either edit `/Data/Packages/Theme - Cola/Cola.sublime-theme` or google for how you can edit themes from the `/Data/User` directory.

Some subjective things:

- `Cola.sublime-theme`
	- Line `15 to ~100`. Tab customization. The tab width, tab height etc.
	- Line `621`. This is the sidebar label color, currently a very pale gold

- Throw in a different icon pack into `./icons/`

### What is that Color Scheme and Coffeescript .tmLanguage!?

Yes, that *is* function call highlighting and embedded CJSX!  

[Color Scheme - Pastels](https://github.com/nfour/Sublime-Scheme-Pastels)
[CoffeeScript Syntax](https://github.com/nfour/Sublime-Coffeescript-Syntax)
