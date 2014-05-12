# praatSublimeSyntax

#### Praat syntax highlighting for Sublime Text 2

## Disclaimer

Although this Praat syntax highlighter already works relatively
well in Sublime Text 2, the highlighter is currently under heavy
development. Many aspects still need to be defined, refined and/or fixed.

So far, the syntax highlighter aims to work with the latest Praat
syntax. Compatibility with previous syntax versions is only partial. I
hope to improve compatibility in future editions of this project.

## Features

* Highlighting of Praat's numerals, keywords, form elements,
commands, operators, comments and quoted texts.
* Code folding for all types of blocks.
* Auto completion snippets for most common loops and conditional jumps.

## Installation

* Download `praat.tmLanguage` and the snippet files.
* Save them into your package folder. Under Windows 7, the path should be:
`C:\Users\YOUR_USER_NAME\AppData\Roaming\Sublime Text 2\Packages\User`
* Restart Sublime Text 2.

If your files end in any of the most common Praat script extensions
(`.praat`, `.script`, `.psc`, `.praat_script`, `.praatscript`,
`.praat-script`, `.praat-batch`), they should automatically be identified
and highlighted by Sublime Text 2. Alternatively, you can select
highlighting for Praat by selecting `View/Syntax/Praat`.

## Inspiration for this highlighter

This Praat syntax highlighter is very much and shamelessly inspired in
José Joaquín's Praat syntax highlighter for Kate
(https://github.com/jjatria/praatKateSyntax). Besides some small additions,
the lists of command definitions are pretty much the same. The quotation
and double quotation highlighting method was taken from the R syntax
highlighter for Sublime Text 2.