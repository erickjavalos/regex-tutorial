# Regex Tutorial

Regex (short for Regular Expression) is a pattern-matching language used to search, manipulate, and validate text. It consists of a sequence of characters that define a search pattern. This pattern can be used to match, replace or extract specific sequences of characters from a string. Below you will be able to see different applicaitons of Regex. 

## Summary



'''
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
'''

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

The regular expression uses the caret (^) and dollar sign ($) anchors to match the entire string, ensuring that the email address is the only thing in the string.

### Quantifiers

The regular expression uses the + quantifier to match one or more characters in the username and domain name parts of the email address. It also uses the {2,6} quantifier to match between 2 and 6 characters in the top-level domain part of the email address.

### OR Operator

The regular expression does not use the OR operator, however if so, (|) is a special character used in regular expressions that allows you to match one of several possible patterns. 

### Character Classes

The regular expression uses character classes such as [a-z0-9_], [\d], and [a-z] to match specific sets of characters in the email address.

### Flags

The regular expression does not use any flags. 

In general, flags are special characters that modify the behavior of a pattern match. They are typically written after the closing delimiter of a regular expression and are usually represented by a single letter.


### Grouping and Capturing

The regular expression uses three groups to capture the username, domain name, and top-level domain parts of the email address.

### Bracket Expressions

The regular expression uses bracket expressions such as [\da-z\.-] and [a-z\.] to match specific sets of characters in the email address.

### Greedy and Lazy Match

The regular expression uses greedy matching by default, meaning that it matches as many characters as possible while still allowing the overall pattern to match.

In summary, greedy matching and lazy matching are two different ways of matching patterns in regular expressions. Greedy matching matches as much of the input string as possible, while lazy matching matches as little as possible while still satisfying the pattern.

### Boundaries

The regular expression does not use any boundaries.

In summary boundaries are special characters that mark the beginning or end of a word, line, or string. They are used to restrict matches to specific parts of the input text and are essential for precise pattern matching.

Some common boundary characters in regular expressions include ^ and $ (which match the beginning and end of a line or string), \b and \B (which match word boundaries), and \A and \Z (which match the beginning and end of the entire string, respectively).

By using boundaries in regular expressions, you can ensure that your pattern matches only the exact parts of the input text that you want, and not any extraneous or overlapping matches.

### Back-references

The regular expression does not use any back-references.

In general, back referencing is a feature in regular expressions that allows you to reference a previously captured group within the same pattern. When a capturing group matches a subpattern, the contents of the group can be stored in memory and later referenced using a back reference

### Look-ahead and Look-behind

The regular expression does not use any look-ahead or look-behind assertions.

Look-ahead and look-behind assertions are powerful tools in regular expressions, allowing you to create more complex patterns that depend on the context of the input string. They are particularly useful in situations where you need to match a pattern only if it is preceded or followed by certain other patterns, without actually including those patterns in the final match.

## Author

Erick Avalos: Github: https://github.com/erickjavalos