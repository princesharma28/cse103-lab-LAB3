# Markdown Syntax Guide

This file is a quick reference to common Markdown syntax used in GitHub README files and documentation.

## Headings

Start a line with one or more `#` characters. More `#` characters create smaller headings.

```markdown
# Heading 1 (largest)
## Heading 2
### Heading 3
```

## Text Formatting

```markdown
**Bold text**
*Italic text*
~~Strikethrough~~
```

Result: **Bold text**, *Italic text*, and ~~Strikethrough~~.

## Lists

### Unordered list

Use `-`, `*`, or `+` for bullets. Indent a nested item by two spaces:

```markdown
- Item A
- Item B
  - Nested item B1
```

Result:

- Item A
- Item B
  - Nested item B1

### Ordered list

Use numbers followed by periods:

```markdown
1. First step
2. Second step
```

Result:

1. First step
2. Second step

## Code

Use single backticks for inline code, such as `print("Hello")`.

Use three backticks to create a fenced code block. Add a language name after the opening fence for syntax highlighting:

```python
def greet(name):
    return f"Hello, {name}!"
```

## Hyperlinks

Put the link text in square brackets and the URL in parentheses:

```markdown
[GitHub](https://github.com)
```

Result: [GitHub](https://github.com).

## Tables

Use pipes to separate columns and hyphens to create the header divider. Colons control alignment.

```markdown
| Column 1 | Column 2 | Column 3 |
|----------|:--------:|----------:|
| Left     | Centre   | Right     |
```

Result:

| Column 1 | Column 2 | Column 3 |
|----------|:--------:|----------:|
| Left     | Centre   | Right     |

## Blockquotes

Start a line with `>` to mark a quotation or note:

```markdown
> An important note or reference goes here.
```

Result:

> An important note or reference goes here.

## Horizontal Divider

Place three hyphens on a line by themselves:

```markdown
---
```

Result:

---

## More References

- [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [Markdown Guide](https://www.markdownguide.org/)
