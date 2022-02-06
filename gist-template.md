# Regux Tutorial

Hello, my name is Evan Bulliner and I will be explaining what regular expressions are and how they work.

## Summary

A regular expression, or regex is a sequence of characters that define a search pattern. It's a a string of text that allows you to create patterns tha thelp match, locate, and manage text.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

An Anchor which commonly uses a '^' or '$'. The ^ anchor is used to match the beginning of the text, and the $ anchor is used to match the end of a text.

Examples: $, ^

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. In otherwords, they set the limits of the string that your regex search matches. Examples are: '+' which means one or more. '?' means 0 or 1 or '{0,1}'. They use "curly brackets".

### Grouping Constructs

Grouping constructs describe/portray the subexpressions of a regular expression. Unlike bracket expressions, subexpressions look for an exact match. Every subexpression is split using a colon (:). It also uses (()) to section off portions of whatever search is being conducted.


### Bracket Expressions

Anything inside of a set of brackets '[]' represents a specific search. It can represent a range of characters in a search. An example of a positive bracket search is [abc] - that will only search for the letters abc in the search. An example of the negative is when you use a carot ^. [^abc] would only match any character except a, b, or c.

### Character Classes

The character class is a basic regex concept that looks for a literal match. It is a shortcut to define an overall set of characters. \d could mean any digit and [a-z] could stand for any lowercase letter from a to z. It's a very useful shortcut to use to save a lot of space and text. It's a lot easier to read as well.

### The OR Operator

The OR operator (|) can split up a group construct. An example of that is, instead of (xyz) which only search for and match xyz...Using the OR operator, you could search (x|y|z), and that would mean you are searching for x, y, or z, or any combo of the construct.

### Flags

A regular expression consists of a pattern and optional flags. Flags can be g, which matches the pattern multiple times on a global scale. i: makes the regex case insensitive. Which means the case should be ignored while attempting to match a certain string. m: enables multi-line mode. u: enables support for unicode. s: short for single line and it causes the '.' to also match new line characters.

### Character Escapes

An escape character is a character tha tinvokes an alternative interpretation on the following characters in a character sequence. What this means is if the character that is attached to a following sequence of characters, they can be seen in a different way. In regex " character is the expression that denotes a specific character is an escaped character.

example: \l will match a single lowercase letter (a-z) & \L matches a single character that is not lowercase (^a-z)

## Author

Author: Evan Bulliner

For any further assistance, you may contact me at:

  * Github: [ebulliner](<https://github.com/ebulliner>)

  OR

  * Email: evan_bulliner@yahoo.com