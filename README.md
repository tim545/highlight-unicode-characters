# Unicode character highlighter for Sublime Text 2 & 3

This plug-in highlights characters such as non breakable space, characters that often break compilers and scripts and is almost impossible to spot in the editor.

## Installation

Clone the repository and copy the whole project directory into the `Packages` folder, you can open your sublime packages with a menu option `SSublime Text -> Preferences -> Browse Packages...`

## Customization

You can override the following parameters within your file settings:

`highlight_unicode_max_file_size`: Restrict this to a sane size in order not to DDOS your editor. Defaults to 1048576 (1 Mio).

`highlight_unicode_color_name`: Change this to a valid scope name, which has to be defined within your theme. Defaults to 'invalid'.
