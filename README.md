# vscode-svg-icons

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![GitHub](https://img.shields.io/github/release/idleberg/vscode-svg-icons.svg?style=flat-square)](https://github.com/idleberg/vscode-svg-icons/releases)
[![Travis](https://img.shields.io/travis/idleberg/vscode-svg-icons.svg?style=flat-square)](https://travis-ci.org/idleberg/vscode-svg-icons)
[![David](https://img.shields.io/david/dev/idleberg/vscode-svg-icons.svg?style=flat-square)](https://david-dm.org/idleberg/vscode-svg-icons?type=dev)

Snippets for a variety of icon fonts ([see details](https://github.com/idleberg/vscode-svg-icons#prefixes)).

This package is also available for [Atom](https://github.com/idleberg/atom-svg-icons) and [Sublime Text](https://github.com/idleberg/sublime-svg-icons)

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install svg-icons`

### Packaged Extension

Download the package extension from the the [release page](https://github.com/idleberg/vscode-svg-icons/releases) and install it from the command-line:

```bash
$ code --install-extension svg-icons.vsix
```

### Clone Repository

Change to your Visual Studio Code extensions directory:

```bash
# Windows
$ cd %USERPROFILE%\.vscode\extensions

# Linux & macOS
$ cd ~/.vscode/extensions/
```

Clone repository as `svg-icons`:

```bash
$ git clone https://github.com/idleberg/vscode-svg-icons svg-icons
```

### Usage

Snippets are limited to the `html` scope. Typing the class name of an icon using the designated prefix will complete to a SVG tag for the icon.

### Prefixes

Prefix         | SVG Icons                           | Version
---------------|-------------------------------------|--------
`ei`           | [Evil Icons][ei]                    | 1.8.0
`octicon`      | [GitHub Octicons][octicon]          | 5.0.0
`oi`           | [Open Iconic][oi]                   | 1.1.0
`si`           | [SmartIcons Glyphs][si]             | 1.1

## License

This work is licensed under [The MIT License](https://opensource.org/licenses/MIT)

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/vscode-svg-icons) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`

[ei]: https://github.com/outpunk/evil-icons
[octicon]: https://github.com/github/octicons
[oi]: https://github.com/iconic/open-iconic
[si]: https://github.com/frexy/glyph-icons
