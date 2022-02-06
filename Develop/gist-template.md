# Regex Tutorial (matching an Email)

Often times a user of an application needs to provide their email address. The application will then need to validate the email. You can do this with RegEx or through a regular expression. 

## Summary

This tutorial will use the regular expression that validates the email. It will break down the parts that go into the expression and provide specific examples of invalid and valid emails.

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

These are the characters that have special meaning in regex: ., +, *, ?, ^, $, (, ), [, ], {, }, |, .

### Anchors

Do not match any character, they match a position before, after, or between characters. They are used to “anchor” the regex match at a certain position. This makes it so that there are no extra characters after the end like a space or a new line character that could result from human error.

### Quantifiers

Quantifiers dictate how many times a character, group, or character class will occur.

\* - Match zero or more times.  
\+ - Match one or more times.  
\? - Match zero or one time.  
{ n } - Match exactly n times.   
{ n ,} - Match at least n times.   
{ n , m } - Match from n to m times. 

### OR Operator

| - this allows you to match different options on either side of it. 

### Character Classes

To search a character string for a set or class of characters you can use a character class or character set. Place the search set between brackets.

### Flags

Optional flags allow you to tailor the search output. 

d	- Generate indices for substring matches.  	 
g	- Global search.  
i - Case-insensitive search.	  
m	- Multi-line search.	  
s	- Allows . to match newline characters.	  
u	- "unicode"; treat a pattern as a sequence of unicode code points.	  
y	- Perform a "sticky" search that matches starting at the current position in the target string. See sticky.  

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Abi Beggs is a marketing operations specialist working to obtain a web development certificate. 

[GitHub Profile](https://github.com/beggsaj)