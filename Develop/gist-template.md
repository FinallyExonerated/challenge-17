# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author
Author Jordan Smith

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)



    Regex Tutorial
With this tutorial we will be going over how to use Regex, specifically when it comes to searching for a username.

What is Regex?
Regex is considered a literal. meaning the pattern needs to be wrapped in slash characters.

Table of Contents
Anchors
Quantifiers
Grouping Constructs
Bracket Expressions
Character Classes
The OR Operator
Flags
Character Escapes
Regex Components

Anchors
$ and ^ both are anchors. ^ is a string that begins with characters that follow it. $ is a string with characters that precede it.

Quantifiers

There are some random group of characters can be a specifc Regex pattern. Regex is a literal, meaning it needs to be enclosed both ways, with slashes //

Grouping Constructs
Grouping Constructs are really valible. They help locate certain patterns in specific places in the string. Everything in the () will be known as a Sub-Expression. Expression (abc):(xyz) will give you "abc:xyz"

Bracket Expressions
[] means an array of multiple values. Any value that is in the [] will represent the range of characters the search is looking for. However, bracket expressions will look for the specified characters in any order, and will look for the values/characters to match.


Character Classes
Character Classes defines a set of characters

The . is compatible with with most characters
The /d is equivelent to [0-9].
/w matches with any character
/s matches a single whitespace characterincluding tabs and line breaks.

The OR Operator
with the Or Operator you can search for (a|b|c):(x|y|z) and receive "cba:zyx"

Flags
Are located outside of the slash character and should be placed after the second slash.

g is for the global search meaning the regex will be tested on all and any outcomes in a string
i represents the case-insensitive search meaning the case will be ignored while attempting to match in string
m is for the multi-line search meaning a multi line input should be regarded as multiple lines

Character Escapes
Open curly brace meaning { is used to start a quantifier and the backslash added to the open curly brace meaning \{ interprets that the regex should search for the { instead of the beginning to define a quantifier


   Author Jordan Smith
