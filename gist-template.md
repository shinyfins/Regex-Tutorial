## Introduction to Regex
The following will explain and highlight the key components that make up regex rules and boundaries.
How to manuever and specify what it is that your looking for.

## Summary
Ive decided to do the email as my example-
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Every email is composed of the same characteristics but with the slight variations to name of choice and platform it belongs to. Now ill explain in depth how to identify and email with regex patterns.
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
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

The front ^
Any character attached with ^ will bring the following string with it. But only works with the front of the string cannot be applied mid or late into the string, otherwise you will be left with missing pieces.

The back $
Any character attached with $ will be introduced but like what we have above used mid way will leave pieces behind.
### Quantifiers
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

The + wants to match the pattern atleast one time but as many as possible while staying within the specified boundaries.

The {} are saying they want to match atleast 2 times with a maximum of 6 times. 

### Character Classes
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

The specifcied a-z and 0-9 imply that it will except any of the following shown and all inbetween.
### Flags
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Grouping and Capturing
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Bracket Expressions
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Greedy and Lazy Match
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Boundaries
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Back-references
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Look-ahead and Look-behind
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
