# Hex Value Regex Tutorial

In this tutorial I will be explaining the functionality of a regex (specific regular expression). I will be breaking down the regex and explaining what each component consists of and what each component does.

## Summary

In this example we will be breaking down a regular expression that matches hex values.

For example we are going to create a rejex to find a specific color or catch an error if the parameters were not met in hex format. The following rejex will validate whether or not the hex code is valid.

Hex Value Rejex: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

It may look confusing now but we are going to break down the rejex to further explain what the rejex does.

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

-Anchors
-Quantifiers
-Grouping Constructs
-Bracket Expressions
-Character Classes
-The OR Operator
-Flags
-Character Escapes

### Anchors

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

Anchor in our example: ^ , $

Its purpose: A character that checks if the string matches a pattern. `^` Matches the position before. `$` Matches the position after.

### Quantifiers

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

Quantifier in our example: `?`

Its purpose: Specifies how many instances a character, group, or class must be present.

### Grouping Constructs

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

Grouping construct in our example:

Its purpose:

### Bracket Expressions

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

Bracket expression in our example: `[*******]`

Its purpose: The brackets `[]` is to indicate a set of characters to match. In our example the brackets contain the following `a-f0-9`, which is the format required to match a valid hex code. If the user writes in an invalid set or differently formatted set, the hex code will be invalid.

### Character Classes

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

Character class in our example: `a-f0-9`

Its purpose: The character class is the set of characters that is enclosed within the brackets. The `a-f` symbolize the range the hex code requires, meaning the code can begin with any letter between `a` though `f`. Also the hex code has `0-9` attached immediately after the `f`, which also allows the hex code to begin with any digit from `0` to `9`.

### The OR Operator

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

OR operator in our example: `|`

Its purpose: Allows the user to match either the expression/characters on the left or the right. The `|` is positioned in between two seperate expressions. One being `[a-f0-9]{6}` and the other being `[a-f0-9]{3}`. Simply putting the OR operator in between allows the user the ability to choose either one.

### Flags

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

Flag in our example:

Its purpose:

### Character Escapes

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

Character escape in our example:

Its purpose:

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
