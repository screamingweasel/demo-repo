# Markdown Language Guide

This file demonstrates the most common Markdown constructs.

## Headings

Headings use `#` symbols. More `#` symbols mean smaller headings.

### Third-Level Heading

#### Fourth-Level Heading

## Lists

### Bulleted List

- First item
- Second item
  - Nested item
  - Another nested item
- Third item

### Numbered List

1. First step
2. Second step
   1. Sub-step A
   2. Sub-step B
3. Third step

##  Code Snippets

Use backticks for `inline code` like variable names or commands.

For multi-line code blocks, use triple backticks with an optional language:

```sql
SELECT name, email
FROM users
WHERE active = true
ORDER BY name;
```

```python
def greet(name):
    return f"Hello, {name}!"
```

---

## Text Formatting

You can make text **bold** with double asterisks, *italic* with single asterisks, and <ins>underlined</ins> with `<ins>` tags. You can also combine them: ***bold and italic***.

| Syntax | Result |
|--------|--------|
| `**bold**` | **bold** |
| `*italic*` | *italic* |
| `<ins>underline</ins>` | <ins>underline</ins> |
| `***bold and italic***` | ***bold and italic*** |


## Tables

| Feature | Supported | Notes |
|---------|-----------|-------|
| Headings | Yes | H1 through H6 |
| Lists | Yes | Bulleted and numbered |
| Code blocks | Yes | Syntax highlighting |
| Tables | Yes | Pipe-delimited |

## Links

- Inline link: [Snowflake Documentation](https://docs.snowflake.com)
- Reference-style link: [Markdown Guide][1]
- Bare URL: https://github.com

## Images
- ![A cute puppy]([https://puppy.jpeg)

[1]: https://www.markdownguide.org
