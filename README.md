# Regex tutorial

Introductory paragraph (replace this with your text)

## Summary

What Is a Regex? Regular expression -> Regex is a sequence of characters that define a specific search pattern When it's included in code or search algorithms, regex can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are frequently used to validate input.

# Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operators](#or-operators)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

# Regex Components

## Anchors
Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.

### Example code
/^\d\d:\d\d$/.test('12:05')

## Quantifiers
Quantifiers match a number of instances of a character, group, or character class in a string.

### Example code
/\d{4}/ matches a four-digit number. It is the same as /\d\d\d\d/

## OR Operators
By adding | to the grouping contructs, you give it the same logic as bracket expression.

### Example code
(a|b|c):(x|y|z)

## Character Classes
Also called “character set”, you can tell the regex engine to match only one out of several characters. Simply place the characters you want to match between square brackets. If you want to match an a or an e, use [ae]. You could use this in gr[ae]y to match either gray or grey.

## Flags
A flag changes the default searching behavior of a regular expression. It makes a regex search in a different way. 
A flag is denoted using a single lowercase alphabetic character (g, i, m, u, s, y)

### Example code
new RegExp('a', 'i') 'i' meaning we would ignore casing 

## Grouping and Capturing
Check multiple parts of a string to determine that different sections fulfill different requirements. breaking up sections = (). each section within () is SUBEXPRESSION. A grouping construct can be made non-capturing by adding ?: at the beginning of an expression inside the ()

### Example code
(abc):(xyz) subexpression is looking for an exact match

## Bracket Expressions
An expression enclosed in square brackets, "[]" match a specific set of single characters, and may match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.

## Greedy and Lazy Match
'Greedy' means match longest possible string. 'Lazy' means match shortest possible string.

## Boundaries
The metacharacter \b is an anchor like the caret and the dollar sign. It matches at a position that is called a “word boundary”. The following three positions are qualified as word boundaries: Before the first character in a string if the first character is a word character. After the last character in a string if the last character is a word character. Between two characters in a string if one is a word character and the other is not.

## Back-references
Back-references are regular expression commands which refer to a previous part of the matched regular expression. Back-references are specified with backslash and a single digit (e.g. ' \1 '). The part of the regular expression they refer to is called a subexpression, and is designated with parentheses.

## Look-ahead and Look-behind
The lookbehind asserts that what immediately precedes the current position is a lowercase letter. And the lookahead asserts that what immediately follows the current position is an uppercase letter.

# Author

My name is Hannah Brownson. I am a Jr. software engineer at Krumware in Columbia, SC. I recieved my certificate for web developement from UNC Chapel Hill. You can preview some of my work here [GitHub](https://github.com/Hannahbird)
