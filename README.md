# Regex Tutorial

My challenge this week is to create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does.

## Summary

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

I will be describing the following expression Matching a Hex Value and explaining what each component means 
`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors

`^` This is the carrot symbol and you can use it at the start of a regular expression to indicate that a match must occur at the beginning of the searched text.

`$` This is the dollar sign symbol and you put it at the end of the regex to indicate the string must end with that regex pattern.

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

`?` This is the question mark quantifier and it means “zero or one”, is makes the symbol optional. Meaning it will match `{0,1}` hatch marks.

`{3}` This is the simplest quantifier, its appended to a character and specifies how many we need.

### OR Operator

`|` This is the OR operator and it means I can have either one of those two bracketed expressions meaning `[a-f0-9]{6}` or `[a-f0-9]{3}`

You can use the operator to match characters or expression of either the left or right of the operator.

### Character Classes

`[ABC]` This is called Character Classes they match a character from a specific set. There are a number of predefined character classes and you can also define your own sets.

The Character Set thats similar to mine for example, `[A-Z]` it means that I am matching A-Z and that is a bracketed expression. Adding a dash between two characters will select a Range.

### Grouping and Capturing

`(ABC)` The paranthesis are the grouping and capturing, it will allow you to read exactly which characters were matched. The expression between the parantheis is a group and I have an option to use `[a-f0-9]{6}` or `[a-f0-9]{3}`

### Bracket Expressions

`[a-f0-9]` A Bracketed Expression is enclosed in square brackets is a regular expression that matches a single character, or collating element. So everything between the `[]` is called a bracketed expression. 

## Author

My name is Viviana Rodriguez and I take Coding Boot Camp course at Rutgers University, below is my github profile.

[MyGithubRepo](https://github.com/vivianarodriguez1712/)

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
