# Regex Tutorial Starter Code
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/   The regex pattern used is for matching email addresses.

/^( This is matching the beginning of the input. 

[a-z0-9_\.] This part of the expression is allowing letters(a-z),digits(0-9),Underscore(_),Dash(-), and a dot(.) from the beginning to end to be entered into the field.

+)@( The middle of this expression is taking the front of the feild and adding it to the at symbol. FakeEmail12@

[\da-z\.-] It looks like this is taking a single digit from 0-9 any character from a-z (case sensitive) also the characters - dash, _ underscore, and . dot.

+) This is acting like the middle of the expression and adding the [\da-z\.-] this time after the @ symbol for the domain of your email address.

\.([a-z\.] This is looking for matches for any character a-z (case sensitive) and the dot . character.

{2,6})$/ This is using the greedy match method show to us by the use of the + Quantifier becuse it is greedy it will return as many matches as possible. The other Quantifier used was the Curly Braces {} this is important because it also is a greedy quantifier this is used to match the last group we need to find {2,6}.