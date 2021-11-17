# Regex tutorial

Learn Regex with this short tutorial down below

## Summary

What is Regex? Regex, short for "regular expression", is a sequence of characters that specifies a search pattern. It helps locate and manage text. They are mostly used to replaced with something else such as a string and to validate input. For example, the following regular expression can be used to verify that user input is a valid email address:
`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)


### Anchors
Anchors match a postion before, after and between characters. Used to help the regex match at a specific position. In a string 'abc', the character '^' matches with a. 
### Quantifiers
A quantifier reapeats a token as many times as possible. The benefit of using quantifiers is to speed up the regex. 
### Grouping Constructs
Placing a regex inside a group, allows you to apply a quantifier to that entire group. 
### Bracket Expressions
These are a special kind of classes. 
### Character Classes
Also known as character sets, you can tell regex to match only one of the characters.
## Author

Brandon Kemboi
- https://github.com/kembo001