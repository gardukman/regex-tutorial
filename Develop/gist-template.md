# RegEx Tutorial by: Garrett Manwaring

In this tutorial, I'll explain what RegEx (Regular Expression) is and how it is used. I'll also provide a few examples of different RegEx code snippets and explain how and what they do. I'm no expert in RegEx, but I hope that my limited knowledge and explanations will help broaden your understanding on this coding language.

## Summary

A RegEx, or regular expression is basically a string of characters that help define a search parameter. Each character in the string is set to search for specific things within a larger string of characters. RegEx uses algorithms to find the patterns set in the search. The examples below are different expressions used in building regular expression search algorithms.

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

The components used for RegEx help determine and define the users search and what they are trying to match. Components are what are entered in to the RegEx string that find the specific matches to what each component is set to find.

### Anchors

Anchors are unique when it comes to RegEx because they don't search for characters in a string, but rather they match positions within a string. For instance, "^" matches the beginning of the string and "$" matches the end of the string.

### Quantifiers

Quantifiers allow you to set a specific quantity to the pattern that is being matched. For instance, the user might need to match a specific number of characters, or find every string between a minimum and maximum parameter set in the quantifier. Examples of quantifiers include "*" which match zero or more of the preceding character, "'char'\{'num'\}" would find the exact "num" of the "char" (m\{3} would match mmm), and "'char'\{'num1','num2'\}" would match no fewer than 'num1' but no more than 'num2' of 'char'.

### OR Operator

### Character Classes

Character classes help match characters only on their classification when searching for text. The two main classes are "word" characters, which are letters and numbers, and "non-word" characters, like spaces and punctuation marks. Some examples include "\w" which matches word characters, "\W" which matches non-word characters, "\s" which finds whitespace characters, "\S" which finds non-whitespace characters, and "." which matches any single character except the newline character. 

### Flags

### Grouping and Capturing

Grouping lets you treat another expression as a single unit. For example, in \('expression'\), 'expression' will match as a group.

With capturing, a part of the pattern can be enclosed in parenthesis which allows to get part of the match as a separate item in the result array, and if a quantifier is placed after the parenthesis, it applies to the parenthesis as a whole.

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

 Boundaries work by matching strings and their positioning within words and phrases. For instance, "\b" matches a word boundary between a word character and a non-word character or position, and "\B" matches any position that is not a word boundary.

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
