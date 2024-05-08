# Regular Expression in Python

Regular expressions (regex) are a powerful tool used in programming for matching text patterns. This functionality is available in many programming languages, including Python, Java, and JavaScript, among others. Regular expressions allow you to specify and identify strings of text that match complex patterns. This can be particularly useful for validating inputs, searching and replacing substrings, and parsing text data efficiently.



## Basic Components of Regular Expressions:
1. Literals: These are the simplest form of pattern matching. For example, the regex cat will match "cat" in any string.
2. Character Classes: These match any one character out of a set of characters. For example, [abc] will match any single 'a', 'b', or 'c'. You can also specify a range of characters, like [a-z] to match any lowercase letter.
3. Predefined Character Classes:
> \d: Matches any digit, equivalent to [0-9].  
> \w: Matches any word character (letter, digit, underscore), equivalent to [a-zA-Z0-9_].  
> \s: Matches any whitespace character (spaces, tabs, line breaks).  
4. Negated Character Classes: These start with ^ and match any character not in the set.
> [^a-z]: Matches any character that is not a lowercase letter.
5. Quantifiers:
> *: Matches 0 or more occurrences of the preceding element.  
> +: Matches 1 or more occurrences of the preceding element.  
> ?: Makes the preceding element optional (0 or 1 occurrences).  
> {n}: Matches exactly n occurrences of the preceding element.  
> {n,}: Matches n or more occurrences of the preceding element.  
> {n,m}: Matches between n and m occurrences of the preceding element.  
6. Anchors:
> ^: Anchors the match at the start of the string. For example, ^A will match an 'A' only at the start of a string.
> $: Anchors the match at the end of the string. For example, A$ will match an 'A' only at the end of a string.
7. Grouping and Capturing:
> Parentheses () are used to group part of a regex together. This lets you apply quantifiers to the entire group and can also capture the contents of the group for use later in the regex or as part of the result.
8. Alternation:
> The pipe symbol | acts like a logical OR. For example, cat|dog will match "cat" or "dog".
9. Escape Special Characters:
> Backslash '\\' is used to escape special characters in regex. For example, to match a '.' literally, you use '\\.'.
