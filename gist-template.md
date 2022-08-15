## Matching an Email Regex Tutorial

    Regex, or regular expressions in JavaScript, are a list of numbers and characters that denote a pattern. The pattern that I am going to describe in this tutorial is the email matching regex, used to match email addresses. It is denoted as follows: 
    /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
    This regex can validate 99.9% of email addresses.

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

    The anchors in this regex are the ^ and $ characters. They fall in between the two slash marks. Since multilines are not enabled (denoted with the m character), the regex ends with the $.

### Quantifiers

    The quantifiers in this regex are the + character and the {2-6} expression. The + character concatenates the email name, service, and .com ending. {2-6} allows matching 2-6 characters from a-z.

### Grouping Constructs

    The three grouping constructs are ([a-z0-9_\.-]+), ([\da-z\.-]+), and ([a-z\.]{2,6}). The first group matches the user's email name while the second grouping construct matches the email service. Lastly, the third grouping construct captures the end of the email address (.com,.net, .biz, etc)

### Bracket Expressions

    Bracket expressions tell the regex which characters to validate and match for each part of the email address as explained above. The three bracket expressions are [a-z0-9_\.-], [\da-z\.-], and [a-z\.].

### Character Classes

    Character classes can be used to match particular characters. You do this by putting them in brackets [].  

### The OR Operator

    The OR operator (denoted as |) can be used to determine which character to use. They can be used to say that an eemail can include one character (or set of characters) or another.

### Flags

    The regex flags are i, g, m, s, u, and y. The email regex does not use any flags.

### Character Escapes

    There are many character escapes. The email regex uses \ (single backslash) and \d (single digit).

## Author

    Shrike6 is the author of this Regex Tutorial. He is a budding software developer doing his best to get through this coding bootcamp! Here is a link to his Github profile: https://github.com/Shrike6

