# Badges for Visual Studio Code

[![The MIT License](https://flat.badgen.net/badge/license/MIT/orange)](http://opensource.org/licenses/MIT)
[![GitHub](https://flat.badgen.net/github/release/idleberg/vscode-badges)](https://github.com/idleberg/vscode-badges/releases)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/idleberg.badges.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=idleberg.badges)
[![Travis](https://flat.badgen.net/travis/idleberg/vscode-badges)](https://travis-ci.org/idleberg/vscode-badges)
[![David](https://flat.badgen.net/david/dev/idleberg/vscode-badges)](https://david-dm.org/idleberg/vscode-badges?type=dev)

Snippets to quickly insert [Shield.io](http://shields.io) badges into HTML, Markdown, reStructuredText or Textile documents — like those you can see above.

This package is also available for [Atom](https://github.com/idleberg/atom-badges) and [Sublime Text](https://github.com/idleberg/sublime-badges).

![Screenshot](https://raw.githubusercontent.com/idleberg/vscode-badges/master/screenshot.gif)

*Badge snippets in action (screenshot nicked from the Atom package, sorry!)*

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install idleberg.badges`

### CLI

With [shell commands](https://code.visualstudio.com/docs/editor/command-line) installed, you can use the following command to install the extension:

`$ code --install-extension idleberg.badges`

### Packaged Extension

Download the packaged extension from the the [release page](https://github.com/idleberg/vscode-badges/releases) and install it from the command-line:

```bash
$ code --install-extension path/to/badges-*.vsix
```

Alternatively, you can download the packaged extension from the [Open VSX Registry](https://open-vsx.org/) or install it using the [`ovsx`](https://www.npmjs.com/package/ovsx) command-line tool:

```bash
$ ovsx get idleberg.badges
```

### Clone Repository

Change to your Visual Studio Code extensions directory:

```bash
# Windows
$ cd %USERPROFILE%\.vscode\extensions

# Linux & macOS
$ cd ~/.vscode/extensions/
```

Clone repository as `badges`:

```bash
$ git clone https://github.com/idleberg/vscode-badges badges
```

### Usage

**Note:** By default, the quick suggestions are disabled for Markdown files. You can enable them by setting `editor.quickSuggestions` to `true`.

All snippets start with the prefix `svg-` and is followed by the service you're adressing, with some services offering multiple choices.

Examples:

* `svg-pypi-dl-day` - daily downloads on PyPI
* `svg-pypi-dl-month` - monthly downloads on PyPI
* `svg-travis` - build status on Travis
* `svg-travis-branch` - build status on Travis for a specific branch
* `svg-npm-ver` - the version of a Node package
* `svg-gpl3` - link to GNU General Public License, Version 3

Please refer to the [snippet guide](https://github.com/idleberg/vscode-badges/blob/master/snippets.md) for a complete list.

## License

This work is licensed under [The MIT License](https://opensource.org/licenses/MIT)

[ai]: http://www.androidicons.com
[brandico]: https://github.com/fontello/brandico.font
[cc]: https://github.com/cc-icons/cc-icons
[dashicons]: https://github.com/WordPress/dashicons
[devicons]: https://github.com/vorillaz/devicons
[ei]: https://github.com/outpunk/evil-icons
[el]: https://github.com/reduxframework/Elusive-Icons
[fa]: https://github.com/FortAwesome/Font-Awesome
[fi]: http://zurb.com/playground/foundation-icons
[fl]: https://github.com/Lukas-W/font-linux
[geomicon]: https://github.com/jxnblk/geomicons-open
[glyphicon]: https://getbootstrap.com/components/#glyphicons
[icono]: https://github.com/saeedalipoor/icono
[ion]: https://github.com/driftyco/ionicons
[line]: http://www.elegantthemes.com/blog/resources/how-to-use-and-embed-an-icon-font-on-your-website
[mdi]: https://github.com/Templarian/MaterialDesign-Webfont
[mfg]: https://github.com/MfgLabs/mfglabs-iconset
[mfizz]: https://github.com/fizzed/font-mfizz
[octicon]: https://github.com/github/octicons
[oi]: https://github.com/iconic/open-iconic
[openwebicons]: https://github.com/pfefferle/openwebicons
[pf]: https://github.com/vendocrat/PaymentFont
[ratchicon]: http://goratchet.com/components/#ratchicons
[st]: https://github.com/parkerbennett/stackicons
[typcn]: https://github.com/stephenhutchings/typicons.font
[ui]: http://semantic-ui.com/elements/icon.html
[wi]: https://github.com/erikflowers/weather-icons
[zmdi]: https://github.com/zavoloklom/material-design-iconic-font
