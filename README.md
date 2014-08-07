iolang-sublime-syntax
=====================

[Sublime Text](http://sublimetext.com/) syntax definition for the [Io language](iolanguage.org/).

Uses the [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev) package.

The file `io.YAML-tmLanguage` is the source file used together with AAAPackageDev to generate the `io.tmLanguage` syntax definition file.

Installation
------------

Copy the `io.tmLanguage` file to your Sublime Texts use package directory.

On Linux it should be copied to e.g. `$HOME/.config/sublime-text-3/Packages/User/io.tmLanguage` (for Sublime Text 3).

---


Note that the syntax definitions are not complete. Currently supports:

* Strings (both single and tripple quoted)
* Numbers
* Comments
* A few "keywords"

What still needs to be done:

* More possible escape-sequences for single-quoted string
* More "keywords" and special messages
* Multiple (and better) categories for special messages
