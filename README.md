# Regex Tutorial

Welcome to the Regex Tutorial! This comprehensive guide will teach you the ins and outs of Regular Expressions (regex) - a powerful tool for pattern matching and text manipulation. Whether you're a beginner or want to deepen your understanding, this tutorial will take you through regex step by step.

## Summary

Regex is a text pattern matching language used in various programming languages and tools. It allows you to search, match, and manipulate text based on specific patterns. In this tutorial, we will cover various components of regex, providing you with the knowledge to create and use regex effectively.

## Table of Contents

1. [Introduction to Regex](#introduction-to-regex)
2. [Regex Components](#regex-components)
   - [Anchors](#anchors)
   - [Quantifiers](#quantifiers)
   - [Grouping Constructs](#grouping-constructs)
   - [Bracket Expressions](#bracket-expressions)
   - [Character Classes](#character-classes)
   - [The OR Operator](#the-or-operator)
   - [Flags](#flags)
   - [Character Escapes](#character-escapes)
3. [Examples and Exercises](#examples-and-exercises)
4. [Author](#author)

---

## Introduction to Regex

### What is Regex?
Regular Expressions (regex) is a powerful tool for working with text patterns. It allows you to define specific patterns you want to search for within a larger text. Whether you want to validate user input, extract data, or search through documents, regex is an invaluable tool.

### When to Use Regex
Regex can be used in various scenarios, such as:
- Validating email addresses, phone numbers, and other input forms.
- Extracting data from logs or text files.
- Parsing HTML or XML documents.
- Replacing text with desired patterns in text editors or code.

In this section, we'll introduce you to the world of regex and help you understand its significance.

---

## Regex Components

Regex patterns are composed of various components, each serving a specific purpose. Let's explore these components in detail.

### Anchors

Anchors are special characters that define the position of a match within a string. They allow you to specify where in the text a particular pattern should occur. Common anchors include:

- `^` (caret): Matches the start of a line or string.
- `$` (dollar sign): Matches the end of a line or string.
- `\b` (word boundary): Matches the position between a word character (alphanumeric) and a non-word character.

For example, using `^` at the beginning of a regex pattern ensures that the match starts at the beginning of a line or string.

### Quantifiers

Quantifiers are symbols that specify how many times a character or group should appear. They allow you to indicate repetition in your regex patterns. Common quantifiers include:

- `*` (asterisk): Matches zero or more occurrences.
- `+` (plus): Matches one or more occurrences.
- `?` (question mark): Matches zero or one occurrence.
- `{n}`: Matches exactly n occurrences.
- `{n,}`: Matches n or more occurrences.
- `{n,m}`: Matches between n and m occurrences.

Quantifiers are essential for specifying how many times a character or group should be repeated in a pattern. For example, `\d{3}` would match exactly three digits.

### Grouping Constructs

Grouping constructs are used to group parts of a regex pattern together. They are enclosed in parentheses `( )`. Groups serve several purposes:

- They allow you to apply quantifiers to multiple characters or groups as a single unit.
- They enable capturing, which means you can extract the matched content from a group.
- They help you organize and structure complex regex patterns.

For example, `(abc)+` would match one or more occurrences of the sequence "abc" as a whole.

### Bracket Expressions

Bracket expressions, denoted by square brackets `[ ]`, allow you to define custom character sets. You use them to specify a set of characters that you want to match. For example, `[aeiou]` matches any vowel.

Bracket expressions are handy when you need to match specific characters or ranges of characters within your text.

### Character Classes

Character classes are predefined sets of characters that are represented by shorthand notations. They provide a convenient way to match common character types. Some common character classes include:

- `\d`: Matches any digit (0-9).
- `\w`: Matches any word character (alphanumeric plus underscore).
- `\s`: Matches any whitespace character (space, tab, newline).

Character classes simplify pattern creation and make your regex patterns more concise.

### The OR Operator

The OR operator, represented by `|` (pipe), allows you to specify alternative patterns. It matches either the pattern on its left or the pattern on its right. For example, `cat|dog` would match either "cat" or "dog" in the text.

The OR operator is useful when you want to provide multiple possibilities for matching.

### Flags

Flags, also known as modifiers, are optional settings that affect the behavior of a regex pattern. They are usually added at the end of a regex pattern as single characters or letters. Common flags include:

- `i` (case-insensitive): Makes the pattern match characters regardless of case (e.g., "a" matches "A").
- `g` (global): Matches all occurrences in the input string, not just the first one.
- `m` (multi-line): Allows the `^` and `$` anchors to match the start and end of each line, not just the entire input.

Flags enable you to customize how your regex patterns behave to suit your specific needs.

### Character Escapes

Character escapes are used to match characters with special meanings in regex as literal characters. They allow you to match characters like `.`, `*`, `?`, or any special character as plain text. To escape a character, you prepend it with a backslash `\`.

For example, to match a period (.) as a literal character, you use `\.`.

Understanding and effectively using these regex components will empower you to create powerful and precise patterns for text manipulation and pattern matching tasks. Each component plays a unique role in building regex patterns tailored to your needs.

---

## Examples and Exercises

To solidify your understanding of regex, this section provides real-world examples and interactive exercises. You'll have the opportunity to apply what you've learned in practical scenarios.

Feel free to explore the provided examples and challenge yourself with the exercises. Practice is key to mastering regex!

---

## Author

This tutorial was created by [Sanjeeth Tharmarajah](https://github.com/SanjeethTharmarajah). Feel free to reach out for questions or further assistance.

![Author's GitHub Profile](https://github.com/SanjeethTharmarajah.png)

By following the table of contents and reading through each section, you'll gain a comprehensive understanding of regex and its components. If you have any questions or feedback, don't hesitate to contact the author via their GitHub profile. Happy regex learning!
