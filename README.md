# Matching an Email Regex Tutorial

This tutorial was created to help explain the function, features, and all the components of a Matching an Email Regex. Regex, or Regular Expression, is a sequence of characters used to help locate, validate or replace text. These character sequences are used in programing to identify strings. 

## Summary

This specific tutorial will focus on Regex used to match an email. It looks like this.

 /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

This specific sequence of characters can be used to discern whether a string of characters is an email or not.

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
Anchors in Regex are used to match the placement of the characters in the string. the two anchor characters are "^" and "$". the string will begin with a "^" and all characters to the right of it, will be taken into account. The "$" denotes the ending of the string.

### Quantifiers
Quantifiers in Regex determines the number of times a character must appear. The characters required are to the left of the quantifier. in this specific regex here is an example of one of the  quantifiers. 

/^([a-z0-9_.-]+)

The quantifier is the "+" located at the end of the string. these signs require that the strings being tested must contain at least one of the preceeding characters.

### Grouping Constructs
Grouping constructs are what divides the Regex into sections. this constructs are defined by parenthesis "()" at the begining and end each section. This specific Regex has three groups.

([a-z0-9_.-]+)   ,    ([\da-z\.-]+)    and    ([a-z\.]{2,6})

When this Regex is determining whether or not a string is an email it will look at these three groups and determine if the specified character are being used, and if they are used in the required amount.

### Bracket Expressions
Bracket Expressions are used to show character classes. Located inside of each of our Grouping constructs are the characters that we are able to use. For example,

our first grouping construct ([a-z0-9_\.-]+), contains a Bracket Expression. this expression holds the Character Classes that our regex will be looking for.

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

Paul Sturm is a current fullstack bootcamp student. the rest of his projects are located at https://github.com/paulisturm .
