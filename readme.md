#cobalt2
A Sublime Text theme based on our old blue friend cobalt.

A refined colour scheme that is easy on the eyes and takes small UI elements into account. Includes full sublime theme (sidebar, search, tabs, etc...) as well as support for SublimeLinter, git diffing and a growing number of plugins.

See below for examples. [Read more at http://wesbos.com/cobalt2-theme-sublime-text-2/](http://wesbos.com/cobalt2-theme-sublime-text-2/)

## Installation

1. Open package control `tools` → `Command Palette` and type `Install Package`
2. Search for Cobalt2 and hit enter
3. Penultimately, open `Preferences` → `Settings - User`. Add the following lines. Only the first two are required but I recommend using all of them: 
   
   ```json
   "color_scheme": "Packages/Theme - Cobalt2/cobalt2.tmTheme",
   "theme": "Cobalt2.sublime-theme",   
   "highlight_line": true,
   "indent_guide_options": [ "draw_normal", "draw_active" ],
	"highlight_modified_tabs": true,
	"line_padding_bottom": 1,
	"line_padding_top": 1,
	"wide_caret": true,
	"caret_extra_bottom": 2,
	"caret_extra_top": 2,
	"caret_extra_width": 3,
	"caret_style": "phase",
	"bold_folder_labels": true,
   ```

4. Finally, restart Sublime for the Theme to be fully applied.

`color_scheme` defines how the code looks and `theme` defines how the sidebar, tabs, search, command palette work.

## Options
#### Sidebar Font Size
Change the sidebar's font size by using these settings in your user config:
```json
{
"sidebar_font_big": true,
"sidebar_font_small": true
}
```
#### Sidebar Padding
Adjust the sidebar's padding by using these settings in your user config:
```json
{
"sidebar_medium": true,
"sidebar_large": true,
"sidebar_xlarge": true
}
```

## Requirements

* For sidebar icons, you need to be running the latest version of Sublime Text 3 - this feature is very new and not supported in older versions of Sublime Text.

## Screenshots

![](http://wes.io/YIjn/content)

### Sidebar Icons

![](http://wes.io/YIjh/content)

### Dirty Tab and Selected Tab
![](http://wes.io/YIZx/content)

### Indentation Guides — Guide, Stacked Guide and Active Guide

Use `"indent_guide_options": ["draw_normal", "draw_active"]` for this 

### GitGutter Support

![](http://wes.io/YIu3/content)

### Autocomplete

![](http://wes.io/YItl/content)

### Command Palette 

![](http://wes.io/YIpV/content)

### GoTo Anything

![](http://wes.io/YIhm/content)

### Tabs, Spaces and Comments

![](http://wes.io/YIho/content)

### Folding Lines

![](http://wes.io/YImN/content)

### Searches
![](http://wes.io/YIj0/content)

### Highlighted Line

![](http://wes.io/YIpZ/content)

### JavaScript
![](http://wes.io/Lwc6/content)

### CSS
![](http://wes.io/YIqI/content)

### PHP
![](http://wes.io/YIa5/content)

### Ruby
![](http://wes.io/YIpO/content)

### Python
![](http://wes.io/YIuH/content)

### Markdown

![](http://wes.io/YJMN/content)

## Contributing
While cobalt2 covers all languages, I write mostly JavaScript and CSS so I welcome any additions for other languages.

### Thanks

Some icons from [Soda Theme by Ian Hill](https://github.com/buymeasoda/soda-theme/)

[Kyle Knight](https://twitter.com/kyleknighted) for pushing cobalt2 past the code screen and styling the entire editor.

Seti UI Atom theme for the sidebar icons

## Official Colours

Yellow: #ffc600
Orange: #FF9D00
Mint: #2AFFDF
Blue: #193549
Off Blue: #0D3A58 (use on variable bgs)
Dusty Blue: #35434d
Dark Blue: #15232D
Pink: #FB94FF
Light Blue: #9EFFFF

### You may also like:

- Cobalt2 Theme for iTerm <https://github.com/wesbos/Cobalt2-iterm>
- Cobalt2 for Alfred <https://github.com/wesbos/Cobalt2-Alfred-Theme>
- Cobalt2 for Atom (WIP) <https://github.com/wesbos/cobalt2-atom>

I also wrote the [Sublime Text Power User Book and video package](https://SublimeTextBook.com) - if you want to become amazing with Sublime Text, check it out!
