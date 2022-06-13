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
- [Bracket Expressions](#bracket-expressions)





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

### Bracket Expressions
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

The [] claim everything thats in them and finds anything included, if its attached to things that arent specified but has what it needs at minimum in them it will pull it in. Its not a scope but a shotgun if left to vague.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
