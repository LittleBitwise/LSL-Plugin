This is primarily a syntax definition for Linden Scripting Language (LSL). It has been hand-written from scratch with accurate syntax in mind for maximum theming support.

It also includes a completely custom theme _and_ code color scheme for Sublime Text.

### Big thank you to [Makopo's LSL package for Sublime Text](https://github.com/Makopo/sublime-text-lsl), which I have been using for years!

The syntax definition of that package has been a little lacking, so I wrote this as a small learning experience. I intend to use this as a drop-in replacement, rather than dive into the code that would generate this file.

To use this syntax as a replacement, replace the contents of `Sublime Text/Packages/LSL/LSL.sublime-syntax` with the file from this repo.
The "LSL > LSL" language option will become "LSL > Bitwise-LSL"

Some specific improvements include:
- doesn't break if preprocessor definitions include templates / functions / scopes
- opening braces are marked correctly with `.begin`
- vector / rotation literals can be highlighted properly (nested expressions are still WIP)
- function / event parameter separators (commas) and surrounding parentheses can be highlighted
- loop statement parentheses and body braces can be highlighted separately from others
- operators can be highlighted independently from each other
- control flow keywords can be highlighted separately from each other (including `jump` and `@label`)
- and many more little details

#### Detail preview:
![Bitwise Theme details](https://imgur.com/mcBbyOo.png)

#### Normal code preview:
The font is Cascadia Code.

![Bitwise Theme code](https://imgur.com/rOx2Rmr.png)

#### Dracula theme preview:
![Dracula Theme preview](https://imgur.com/FebxqY0.png)
