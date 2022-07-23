# Title (Regex Intro)

Regex, Or Regular Expressions isn't a library nor is it a programming language. It is a sequence of characters that specifies a search pattern in any given text. A text can consist of pretty much anything from letters to numbers, special characters.

## Summary

The Regex I will be summarizing is the Matching an Email regex. " /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/"

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
Anchors match a position rather than a single character.

The ^ and $ characters are anchors that fix a match to the beginning or end of a line of text.

`/^$/`

### Quantifiers
Quantifiers tell how many instances of a character must be present for there to be a positive match.

` { n , m }? matches from n to m times`

### OR Operator
An OR Operator only assigns if one portion is falsy.

`x || y`
### Character Classes
A Character class matches any one of the enclosed characters.

`a-z 0-9`
### Flags
Flags are an advanced searches, like global searching or case-insensitive searching.
I dont see one with in the Matching Email.

### Grouping and Capturing
Matches for x and remember the match. Its possible to have many with in a regex expression
`(?<Name>x)`
### Bracket Expressions
A bracket expression (an expression enclosed in square brackets, "[]" )
`[a-z0-9_\.-]`


## Author

github.com/Wolfe-Nate
