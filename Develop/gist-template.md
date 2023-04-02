# Regular Expressions (REGEX) Discussion

In the following paragraphs below we will discuss regular expressions. Regular expressions also known as Regex are an incredibly useful tool to use when searching for specific words or characters or they can be used to validate data (typically user input). Regex use a sequence of characters which define a search pattern that is applied to the body of a text. This sequence of characters can be literal, e.g when searching for a specific word in a Microsoft word document and you use the find function. The power of regex is significantly increased by incorpating meta .. which allow us to search for multiple variations of data based on the desired output. 


## Summary

For the purpose of this tutorial we will be reviewing the following regex obtained from UNB Bootcamp resources. This is typically used to verify user inputs as it pertains to emails:

Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Please note that the regex is between the the first / and last /.

We will be specifically reviewing the "Anchors", " Quantifiers" and "Bracket Expressions" componenents of the regex above. 

## Table of Contents

- [Anchors](#anchors)
- [Bracket Expressions](#bracket-expressions)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)

- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Given the regex in the summary the ^ and $ characters at the beginning and at the end of the regex are considered to be anchors. The ^ character defines where the string begins with the $ character defining where the string ends. Between the anchors is where the search pattern is defined. As alluded to above the search pattern could either be a literal character or a meta character.

An example of a search pattern containing a literal character would be if we were searching for the word "Regex" in this document, this could be represented by ^Regex. This would find all instances of the word Regex, and note that this is case senstive.

An example of a meta character is the example in the summary. A extract of a meta character from the email validation is "a-z0-9". This will seacrh the user input for all the characters between a - z and numbers between 0 - 9. This allows for an expansion of the search range.

### Bracket Expressions

### Quantifiers



### OR Operator

### Character Classes

### Flags

### Grouping and Capturing



### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
