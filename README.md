# praatSublimeSyntax

#### Praat syntax highlighting for Sublime Text

## Features

* Highlighting of Praat's numerals, keywords, form elements,
commands, operators, comments, quoted texts, methods, objects,
objectDirectives, systemDirectives, fileDirectives, directives, colors,
predefinedVariables, functions, object functions and procedures.
* Code folding for blocks.
* Auto completion snippets for loops, conditional jumps and forms.

## Installation

This syntax highlighter, just as [Sublime Text][], can be installed in Windows,
Linux and (Mac) OS X. These are the instructions:
* Download `praat.tmLanguage` and the six snippet files (you can just clone
the whole repository if you want).
* Open Sublime Text and go to `Preferences` > `Browse Packages...`.
* There, create a folder called "Praat" and save all the downloaded files inside
that new folder.
* Restart Sublime Text.

All your files ending in any of the most common Praat script extensions
(`.praat`, `.script`, `.psc`, `.praat_script`, `.praatscript`,
`.praat-script`, `.praat-batch`, `.proc`) should automatically be
identified and highlighted by Sublime Text. Alternatively, you can
select highlighting for Praat by selecting `View` > `Syntax` > `Praat`.

## Inspiration for this highlighter

This Praat syntax highlighter is very much and shamelessly inspired in
José Joaquín's Praat [syntax highlighter for Kate][]. Besides some small additions,
the lists of command definitions are pretty much the same. The quotation
and double quotation highlighting method was taken from the R syntax
highlighter for Sublime Text. The procedure highlighting is inspired in
the system used in Python's syntax highlighter for Sublime Text.

## Disclaimer

Although this Praat syntax highlighter already works well in [Sublime Text][],
it still contains some bugs that need some attention. On the same note, several
functionalities of the highlighter could be refined to improve efficiency.

So far, it aims to work with the latest Praat syntax. Compatibility with
previous syntax versions is only partial. I hope to gradually improve
compatibility as I'm able to work on newer versions.

[syntax highlighter for Kate]: https://github.com/jjatria/praatKateSyntax
[Sublime Text]: http://www.sublimetext.com/