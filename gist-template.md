# Title (FunctionBreakDown)

In this project im going to break down a regex (regular expression) and explain what each part of said regex doses and how it functions. This will also explain how all the parts of the regex are defined and how each part of the function works idepedentially to get a result together.

## Summary

A regex is a sequence of characters that can be used to give specific search criteria to simplife the process of searching. This is benificial because is saves you from having to wright a function to do this same job. Regex expressions are not always the best practice becuse the expressions can take more resources because of the complexity of the expression vs the simplifed function with exact instuctions. This is the expresion I will be breaking down to a basic level.


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
literal characters: are the exact matches to the characters we are looking for, for example ifI needed to fine the characters in the word Coding. Each one of the characters in coding would be a literal character becuse it is the exact character we want to spell the word coding out.
Meta Character: a character that dose not include a single literal character but, instead references to a pattern that matches the operation in which we are trying to achieve.
### Anchors
Anchors: they are used a little differently in that they are used for positioning of a character before and after characters rather than the characters themselves. This is benificial for the purpose of knowing positioning which lets us place our character in the correct spot so the Regex can properly handle positioning.
### Quantifiers
Quantifiers: is refering more to the amount of characters in the Regex expression. Then is requiring the amount of characters to match said expression in order to get the correct characters in the Regex expression.
### OR Operator
OR (||): for the OR operator to be true one or more of the operants must also be true. Otherwise the OR operator must be false becuse there is no operator that was true there for it is false. The OR is generally used to return a boolean values, however that being said the OR operator can be used with no boolean values and will return those values if setup to do so.
### Character Classes
Character Classes: are used to determine which character are letters and numbers this is important to get the right character in the Regex expression. Both expressions are used to determine which character to use here. [bcd] = [b-d] The two expressions here are equal to each other. 
### Flags
Flags: There are six flags that can be used to effect the expression in JaveScript (i,g,m,s,u,y). Flags are used to provide the second parameter to the expression alot of the time. 
i=Case-Insensitive.
g=Seaches for all matches not just the first match.
m=Multiline mode.
s=Enables "dotall" mode this alowes the use of a dot.
u=Enables full Unicode support.
y="Sticky" mode This is uses to seach for an exact position in the text.
### Grouping and Capturing
A group of characters or digits wrapped together in paranthesis are a captured group of characters. This is used to give the specific group of characters orders or properties. We use Grouping and Capturing in JaveScript all the time it is very useful for specifing the group of characters you want to control.
### Bracket Expressions
The bracket is used to specify characters within them the match. Any character between the brackets [] will match, and you can also use a hyphen to define a set. Curly braces {} are used to specify an exact amount of things to match. Parentheses () represent remembered matches. All the diffrent symbols listed are important to the syntaxt of the expression.
### Greedy and Lazy Match
Greedy: For every position in the string Try to match the pattern at that position. If there’s no match, go to the next position.
Lazy: This as the name implies is the optosit of a greedy search in that it will repeat the pattern for a set minimum number of times.
### Boundaries
Boundaries: will match a position where one side is a word character is most of the time a letter,digit, or underscore and the opposite side is not a word character. 
### Back-references

### Look-ahead and Look-behind          

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
