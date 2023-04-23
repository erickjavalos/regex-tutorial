# Regex Tutorial

Regex (short for Regular Expression) is a pattern-matching language used to search, manipulate, and validate text. It consists of a sequence of characters that define a search pattern. This pattern can be used to match, replace or extract specific sequences of characters from a string. Below you will be able to see different applicaitons of Regex. 

## Summary

In this tutorial, we will cover the basics of regex tutorial with a email regex. We will investigate what the anchors, quantifiers, character classes, grouping and capturing, bracket expressions, and greedy match.

The email regex is here:

```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

The regular expression uses the caret (^) and dollar sign ($) anchors to match the entire string, ensuring that the email address is the only thing in the string.

### Quantifiers

The regular expression uses the + quantifier to match one or more characters in the username and domain name parts of the email address. It also uses the {2,6} quantifier to match between 2 and 6 characters in the top-level domain part of the email address.

### Character Classes

The regular expression uses character classes such as [a-z0-9_], [\d], and [a-z] to match specific sets of characters in the email address.

### Grouping and Capturing

The regular expression uses three groups to capture the username, domain name, and top-level domain parts of the email address.

### Bracket Expressions

The regular expression uses bracket expressions such as [\da-z\.-] and [a-z\.] to match specific sets of characters in the email address.

### Greedy and Lazy Match

The regular expression uses greedy matching by default, meaning that it matches as many characters as possible while still allowing the overall pattern to match.

## Author

Erick Avalos: Github: https://github.com/erickjavalos