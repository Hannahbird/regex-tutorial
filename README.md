# Regex tutorial

Introductory paragraph (replace this with your text)

## Summary

What Is a Regex? Regular expression -> Regex is a sequence of characters that define a specific search pattern When it's included in code or search algorithms, regex can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are frequently used to validate input.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.

#### Example code
/^\d\d:\d\d$/.test('12:05')

### Quantifiers
Quantifiers match a number of instances of a character, group, or character class in a string.

#### Example code
/\d{4}/ matches a four-digit number. It is the same as /\d\d\d\d/

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
