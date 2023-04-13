# Regex-Tutorial

I want to be able to search for a phone number with regex. 

## Summary

I want to be able to search for a pattern within a phone number. The phone number can have (), ., - 

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

Matches phone number formats:

(555) 555-5555
555-555-5555
555.555.5555
555 555 5555

^\(?\d{3}\)?[-.\s]?\d{3}[-.\s]?\d{4}$

### Anchors
the ^ represents the beginning and the $ represents the end that needs to match, it has to match this pattern to be a valid phone number 
^ (caret), $ (dollar)

### Quantifiers
the {} and ? control the number of times a pattern should match in the text the {3} {3} matches the first 6 numbers and the {4} matches the last 4 and the ? is used for optional characters like (), -, . or space

### Grouping Constructs
() is used to group the area code within (555) the [] is used to match any of the -, ., or space.

### Bracket Expressions
[] is used to match any of the -, ., or space. This matches the different formats of phone numbers

### Character Classes
the /d matches any one digit character for the phone number and the /s matches any of the -, ., or space.

### The OR Operator
This does not have the OR operator

### Flags
This does not have flags

### Character Escapes
\() is used as a character escape, matches for optional parenthesis in phone number and the \ for . - and white space

## Author

Harrison Tran-Chung     

https://github.com/htranchung/Regex-Tutorial 