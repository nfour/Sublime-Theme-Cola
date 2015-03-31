## Cola, it's a kind of Soda

A [Soda](https://github.com/buymeasoda/soda-theme) variant theme for ST3 3062+.
Because Soda is apparently abandoned and we can't have that.

[![Cola](http://i.imgur.com/P0udiXH.png)](http://i.imgur.com/P0udiXH.png)

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
	- Reduced left-indent to 16px, aligning icons up with the text.
	- Increased row bottom padding by 1px
	- Removed leftmost margin so that selected item overlay spans entire width
	- Headings (FOLDERS, OPEN FILES) are now very low contrast as they are least important
	- Folders are transparent when not selected, further directing importance
	- Added hover effect to rows
	- Slimmed up horizontal padding, sidebar is far more succinct in space while not cramped
	- Fixed sidebar titles causing their own indentation

### Want to customize something?

Either edit `/Data/Packages/Theme - Cola/Cola.sublime-theme` or google for how you can edit themes from the `/Data/User` directory.

Some subjective things:

- `Cola.sublime-theme`
	- Line `15 to ~100`. Tab customization. The tab width, tab height etc. it's all rather straightforward.
	- Line `621`. This is the sidebar label color, currently a very pale gold

- Throw in a different icon pack into `./icons/`

### Progress

It's quite satisfactory, although...

- Been meaning to try some font variants, especially for the sidebar
- Dim the lower panel and tab's background color to match the sidebar/statusbar


### What is that Color Scheme and Coffeescript .tmLanguage!?

Yes, that *is* function call highlighting!
Custom built. Happy to release them properly should anyone care.

### License

Go nuts.