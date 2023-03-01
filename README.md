# Regex(Regular Expression Tutorial)

Introductory paragraph (replace this with your text)
Computer Science for JavaScript Challenge: Regex Tutorial


1.	Tutorial : Regular expression

This tutorial has been made for the purpose of helping anyone who need to learn Regular expressions.
The Regular expression that we will be using is the one to search an email address such as tutorial@hotmail.com and will be able to return a match and check if all criteria of the email are matching.


2.	Conclusion

Regex (regular expression ) is a statement that describes a specific pattern of characters that can be searched in a file or a folder, compared and matched them. After that returned to be utilized by a user or program to serve various use cases.
For each Regex , the purpose is to return a match for a serie of characters.
We can also modifie inside of a regex : the type of characters, the number of characters and the order.

3.	Table of Contents
4.	The structure of a basic email address:
-	The user-name and domaine name separated by an @ ,the a . “dot” followed by the “domain-expression”.
-	This is how the structure will look like:
bertintshisuaka@hotmail.com





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
in this tutorial, you’ll learn about regular expression anchors that allow you to match a position before or after characters.

Anchors have special meaning in regular expressions. They do not match any character. Instead, they match a position before or after characters:

 ^ – The caret anchor matches the beginning of the text.
 $ – The dollar anchor matches the end of the text.
See the following example:

Reference:www.rexegg.com/regex-anchors.html

### Quantifiers
A quantifier is a syntactic structure in regular expressions that indicates the number of times a character occurs in sequence in the input text.

Reference:www.javascripttutorial.net/regular-expression-quantifiers

### Grouping Constructs
Grouping constructs delineate the subexpressions of a regular expression and capture the substrings of an input string. You can use grouping constructs to do the following:

Match a subexpression that is repeated in the input string.

Apply a quantifier to a subexpression that has multiple regular expression language elements. For more information about quantifiers, see Quantifiers.

Include a subexpression in the string that is returned by the Regex.Replace and Match.Result methods.

Retrieve individual subexpressions from the Match.Groups property and process them separately from the matched text as a whole.
Reference:https://learn.microsoft.com/en-us/dotnet/standard/base-types/grouping-constructs-in-regular-expressions

### Bracket Expressions
Within a bracket expression, a range expression consists of two characters separated by a hyphen. It matches any single character that sorts between the two characters, based upon the system’s native character set. For example, ‘[0-9]’ is equivalent to ‘[0123456789]’. (See Regexp Ranges and Locales: A Long Sad Story for an explanation of how the POSIX standard and gawk have changed over time. 

Reference:www.gnu.org/software/grep/manual/html_node/Character-Classes-and-Bracket …
### Character Classes
The character class is the most basic regex concept after a literal match. It makes one small sequence of characters match a larger set of characters. For example, [A-Z] could stand for any uppercase letter in the English alphabet, and d could mean any digit. Character classes apply to both POSIX levels.

reference:https://developer.mozilla.org/en-us/docs/web/javascript/guide/regular_expressions

### The OR Operator
The “or” operator can be used to provide options to match where one of the options should match provided with the “or” operator. The “or” operator is also called as “or” logic too. In this tutorial, we examine how to use “or” logic/operator with the regular expressions (regex).

Reference:developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical…
### Flags
A flag is an optional parameter to a regex that modifies its behavior of searching. A flag changes the default searching behavior of a regular expression. It makes a regex search in a different way. A flag is denoted using a single lowercase alphabetic character.
reference:www.codeguage.com/courses/regexp/flags

### Character Escapes
The backslash (\) in a regular expression indicates one of the following:

The character that follows it is a special character, as shown in the table in the following section. For example, \b is an anchor that indicates that a regular expression match should begin on a word boundary, \t represents a tab, and \x020 represents a space.

A character that otherwise would be interpreted as an unescaped language construct should be interpreted literally. For example, a brace ({) begins the definition of a quantifier, but a backslash followed by a brace (\{) indicates that the regular expression engine should match the brace. Similarly, a single backslash marks the beginning of an escaped language construct, but two backslashes (\\) indicate that the regular expression engine should match the backslash.

Reference: https://learn.microsoft.com/en-us/dotnet/standard/.

## Author
BERTIN
kabundi tshisuaka
Bachelor Degree in Information Technology Software Engineering
Student in Boot camp at Georgia Tech (Full stack web developer)


