# REGEX TUTORIAL

REGEX is also called regular expression, regex is a text string that creates patterns to help us match, locate, and manage text.
regex code is unique by itself but mastering it will save our worktime especially if we are working with text or need to parse large amount of data.

## Summary

Here in this tutorial I will explain the regular expression code for E-mail matching.

`^[\w!#$&_*?^{}~-]+(\.[\w!#$&_*?^{}~-]+)*@([a-z0-9]+([a-z0-9-]*)\.)+[a-zA-Z]+$`

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
* [regex components](https://zone.ni.com/reference/en-XX/help/371714F-01/nirghelp/regular_expressions_components/)
* [regex components](https://analytics.webtrends.help/docs/regular-expression-components)
### Anchors
Anchors in regular expression is a specific position on the string where a match occurs.


- `^` : this cap size represents the beginning of the string. `/^[\w._%+-]` is the start of the email string as mentioned above.

- `$`:  this dollar size in regular expression means the macth must occur at the end of the string. `[a-zA-Z]{2,4}$/` here this represents the end of the email string.

### Quantifiers

Quantifiers specify how often the previous regular expression should match.

- `?`: This expression will try to match Zero or one time. ie, in the code above 
- `+`: This expression will try to match the single character, character set or  character group as one and that can match to appear one or more times.
example:  `^[\w!#$&_*?^{}~-]+` here in the above code this line means any letter, number or mentioned special characters will be a match even if it appears more that one time.

- `*`: this expression will match single character, character set, or character group as one that can appear zero or more time. 

### OR Operator

### Character Classes
- `.`: this character represent any characters that may match or not match in the regular expression.
- `d`: this character is to match digits between 0-9.
- `D`: this character will exclude the digit match.
- `w` : this character will match all letters a-z and A-Z (all cases) and also digits 0-9.
- `W`: this character will exclude all characters a-z and A-Z (all cases) and also digits 0-9.

### Flags
Flags are used in Regular expressions to  affect the search behaviour.

- `-g`: this is a global search flag that makes the regex to search all occurances matching the given pattern.

### Grouping and Capturing

By grouping and capturing method regex can match character sequence as show in the example below;
 - `()` use to group the characters as `(\.[\w!#$&_*?^{}~-]+)`, here are characters are all grouped together with `()`

### Bracket Expressions
Bracket expression in regex used to macth only one out of serveral characters. 
- `[]` here in between the bracket we simply place the match we want as `[\w!#$&_*?^{}~-]` here it matches any character in the set.


### Greedy and Lazy Match

- `greedy` means to match the longest string as possible where as `lazy` means shortest string as possible.

### Boundaries

Boundaries in Regex to implement what is the macth to the left and right of current position.

- `/` is an example of Regex boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Hi I am Amal Lohith.
I am a mechanical engineer striving to persue my passion for Web Development. 
[CLICK HERE FOR MY GITHUB](https://github.com/LohithAmal)


