# Color Schemes - Perv #

> "**Actually, as a native from Perv, I prefer to be called a '_Pervect_'**" <_Aahz:japanese_ogre: in [Myth Directions][md]_>

[![release badge]][release] [![sublime text badge]][sublime-text] [![Package Control](https://packagecontrol.herokuapp.com/downloads/Perv%20-%20Color%20Scheme.svg?color=50C32E)](https://packagecontrol.io/packages/Perv%20-%20Color%20Scheme) [![licence badge]][licence] [![stars badge]][repo] [![issues badge]][issues] [![paypal badge]][paypal]

## Introduction ##

The color schemes are created so that the same code in different languages should look the same, with consistent color palettes.

The project started a couple of years back, when there were nearly to none color schemes, which covered the syntax I was interested in. The majority of the available color schemes back then, even didn't highlight the settings (`JSON`) or tmTheme files (`XML`).

This version is a complete rewrite from scratch in the new JSON Format (`.sublime-color-scheme`) for Sublime Text. It is heavily customized for the standard syntax highlighter for `Python`, `JavaScript`, `Ruby`, `PHP`, `Java`, `Rust`, `C++`, `Go`, `CSS`, `reStructuredText` and `Markdown`.

<!-- ZZZ for later usage

Additionally, the schemes currently support the following syntax highlighters and packages (please, check the [Update](#update-history) section for more details about new additions and changes):

|         Syntax        |                                    Package                                    |         Syntax        |           Package            |
| --------------------: | :---------------------------------------------------------------------------- | --------------------: | :--------------------------- |
|     `Markdown`, `GFM` | [Markdown Editing][12] (recommended), [knockdown][11], Default                |    `reStructuredText` | Default, [ReST extended][13] |
| `CSS`, `SCSS`, `SASS` | Default, [SCSS][15], [Syntax Highlighting for SASS][16], [SASS][17]           |        `JSON`, `YAML` | Default                      |
|         `Ruby`, `ERB` | Default                                                                       |              `Python` | Default                      |
|         `Git`, `Diff` | [Git][20], [Sublime Git][21], [Git Gutter][22], [SubliMerge Pro][23], Default |              `Linter` | [Sublime Linter][24]         |
|              `BBCode` | [BBCode][30]                                                                  |               `C/C++` | Default                      |
|              `Config` | [Generic Config][26], [Dotfile][27], [nginx][28]                              | `Bracket Highlighter` | [Bracket Highlighter][29]    |

Supports: "RestructuredText Improved"

|               `Swift` | [Swift][25]                                                                   |       `TWiki/FOSWiki` | [TWiki][31]                  |

Config:

- Generic Config (recommended)
- SSh Config
- Git Config
- Dotfile Syntax Highlighting (for shell files)
- nginx

-->

## The Perv Color Schemes ##

### Perv Orange :tangerine: Family ###

The colors are grouped together based on the following scopes:

* **Comments**: Grey
* **Keywords & Tags**: Orange
* **Functions**: Red
* **Function Parameters:** Light Red
* **Classes, Objects & other Entities**: Blue
* **Class Parameters:** Light Blue
* **Storages**: Yellow
* **Strings & Constants**: Greens

#### Perv Orange ####

Dark and retro:
<!-- ZZZ ![Perv Orange][img-orange] -->

#### Perv Orange New Moon ####

With a darker background and a hicontrast:
<!-- ZZZ ![Perv Orange New Moon][img-orange-nm] -->

#### Perv Orange High Noon ####

With a white background for use during the day ;):
<!-- ZZZ ![Perv Orange High Noon][img-orange-hn] -->

<!-- ZZZ
## Advanced usage ##

There are so many different personal tastes that it is nearly impossible to make one color scheme, which satisfies even those guys, who's color taste is the same.  Some guys don't like _italics_ or **bold** font faces, other's dislike the selection color.  You can edit the color scheme to fit your personal taste.

> **Note:** As of [Sublime Text 3][52] packages are normally installed as an archive with the suffix `.sublime-package`, the below changes cannot be done directly.  You either need to install the package through `Add Repository` in [Package Control][53], use Git to clone the repository or by extracting the package archive.

In order to edit the specific scheme file, you want to amend, please select the `Preferences &#8594; Browse Packages` menu entry in [Sublime Text][51].  That will open the packages directory either in the "Finder" (on Mac OS X), "_flavoured_ file explorer" (on Linux) or in "Explorer" (on Windows).  Go into the _Color Schemes - Perv_ directory and drag'n'drop the color scheme file, which you would like to use, to your [Sublime Text][51] editor.  After the file is loaded, do the following depending on the desired change:

+ *Switch of italic or bold font faces*: search for either "italic" or "bold" in the file.  Just comment the line you find, rinse and repeat for all font faces you want to remove.
+ *Change the gutter and line highlight color*: search for "lineHighlight" and either change the color value to one to your liking or use one of the available presets.

> **Hint:** as you're already using [Sublime Text][51]--commenting and uncommenting is as easy as a key-press: Mac: <kbd>&#x2318;</kbd>+<kbd>/</kbd> and for the PCs: <kbd>CTRL</kbd>+<kbd>/</kbd>)
-->

## Installation ##

### Sublime Text ###

<!-- ZZZ
For the [Sublime Text][51] editor the schemes can be installed easily using [Package Control][53] and searching for the `Color Scheme - Perv` package in the official repository.
 -->
Otherwise, first you need to locate your [Sublime Text][51] packages directory--use the `Preferences &#8594; Browse Packages` menu from within [Sublime Text][51], if you don't know where the directory is located.

Now either create a `Color Scheme - Perv` folder within this directory, and copy the contents of the GitHub repository, or clone the repository using the Git software within the packages directory:

    git clone https://github.com/micck/perv-colorscheme "Color Scheme - Perv"

Now simply use the `"Color Schemes…"` option of your preferences menu and search for "Perv" to switch between the schemes & enjoy!

### Other editors & tools ###

In the future, I'm going to adapt the color scheme to other editors (currently planned are [Visual Studio Code][60], [JetBrains IDE's][69], [Atom][61], [VIM][63], [XCode][64]) as well as other tools ([iTerm2][65], [Gnome Terminal][66], [Fish Shell][67], [Powerline][68]).  There is no roadmap so far, but I'll start porting after the 2.0 release.

## Update history ##

### Version 2.0 ###

* completely rewritten from scratch. Mainly retained the coloring, but did a few changes:
  * brackets are now always white (those glitches are gone :relieved:)
  * angular brackets for tags (they have the same color as the respective tag)
  * more consistency for module or function calls (always the some color; italics for argument definition, normal font for call)
  * classes, modules, objects and entities now share the same color
* HTML: DocType
* Comments in Moonlight are darker now
* …

## Contribute ##

If you have any kind of problems or enhancement requests, please don't hesitate to open an issue.  And if you want to make an improvement, please don't hesitate to fork. If you would like to add another syntax/scope, please use the [Perv Color Schemes: Color Tables][90].

**Before** you submit a pull request, please be sure you have done these steps:

1. Fork the _Color Scheme - Perv_ repository if you haven't already.
2. Create a new branch from the master
3. Make your changes.
4. Commit your changes.
5. Push your branch to your fork.
6. Go to your fork on github and make a pull request. Please give as much information in the description as possible, including the conditions under which the bug occurs, which code and what lines are affected, sample code which caused the error, etc.

## Thanks ##

Very big thanks goes to @dsander and @elseym for their invaluable support and feedback all the time. :yellow_heart:

Also, thanks to my family at [Mayflower][91] for all their help and support! Additionally I would like to thank my friends at [FlavourSys][92] for their support to release the first version.

*Always have fun:sunny: in what you're doing and* "DON'T PANIC"...:rocket:

**Enjoy!**

<!-- reference section -->
--------------------------
[md]: https://en.wikipedia.org/wiki/Myth_Directions
[release]: https://github.com/micck/perv-colorscheme/releases
[sublime-text]: http://www.sublimetext.com/
[licence]: <LICENSE.txt>
[repo]: https://github.com/micck/perv-colorscheme
[issues]: https://github.com/micck/perv-colorscheme/issues
[paypal]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=P3BWGA5FT2SY6

[release badge]: https://img.shields.io/github/release/micck/perv-colorscheme.svg
[sublime text badge]: https://img.shields.io/badge/Sublime%20Text-v2%2C%20v3-green.svg
[licence badge]: https://img.shields.io/badge/license-MIT-blue.svg
[stars badge]: https://img.shields.io/github/stars/micck/perv-colorscheme.svg
[issues badge]: https://img.shields.io/github/issues/micck/perv-colorscheme.svg
[paypal badge]: https://img.shields.io/badge/paypal-donate-ff69b4.svg

[11]: https://packagecontrol.io/packages/knockdown
[12]: https://packagecontrol.io/packages/MarkdownEditing
[13]: https://github.com/jhaubrich/Jesse-s-Sublime-Mods "abandoned"
[14]: empty:link4ReStructuredText###
[15]: https://packagecontrol.io/packages/SCSS
[16]: https://packagecontrol.io/packages/Syntax%20Highlighting%20for%20Sass
[17]: https://packagecontrol.io/packages/Sass
[18]: empty:link###
[19]: empty:link###
[20]: https://packagecontrol.io/packages/Git
[21]: https://www.sublimegit.net/
[22]: https://packagecontrol.io/packages/GitGutter
[23]: http://www.sublimerge.com/
[24]: http://www.sublimelinter.com/
[25]: empty:link4swift###
[26]: https://packagecontrol.io/packages/Generic%20Config
[27]: https://packagecontrol.io/packages/Dotfiles%20Syntax%20Highlighting
[28]: https://packagecontrol.io/packages/nginx
[29]: https://packagecontrol.io/packages/BracketHighlighter
[30]: https://packagecontrol.io/packages/BBCode%20Syntax
[31]: https://packagecontrol.io/packages/TWiki

[img-orange]: https://raw.githubusercontent.com/micck/miccks-packages/master/screenshots/perv/perv-orange.png
[img-orange-nm]: https://raw.githubusercontent.com/micck/miccks-packages/master/screenshots/perv/perv-orange-moonlight.png
[51]: http://www.sublimetext.com/
[52]: http://www.sublimetext.com/3
[53]: https://packagecontrol.io/installation

[60]: https://code.visualstudio.com
[61]: https://atom.io/
[62]: http://brackets.io
[63]: http://www.vim.org/about.php
[64]: https://developer.apple.com/xcode/
[65]: https://www.iterm2.com/
[66]: https://help.gnome.org/users/gnome-terminal/stable/
[67]: http://fishshell.com/
[68]: https://github.com/powerline/powerline
[69]: https://www.jetbrains.com

[Scope Hunter]: https://packagecontrol.io/packages/ScopeHunter

[90]: http://blog.hohmann.org/blog/2013/04/15/perv-schemes-color-table/
[91]: https://www.mayflower.de/
[92]: http://www.flavoursys.com
