+++
date = '2025-05-17T10:00:37-07:00'
draft = false
title = 'First Post'
+++

# Heading 1: Main Title of the Document

This is a standard paragraph. It contains a few sentences to demonstrate basic text flow. Markdown is a lightweight markup language with plain-text-formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supported HTML.

This paragraph has a line break
right here, achieved by ending the preceding line with two or more spaces.

## Heading 2: Text Formatting and Emphasis

This section demonstrates various ways to style text.

### Heading 3: Basic Emphasis

- **Bold text using double asterisks.**
- __Bold text can also be done with double underscores.__
- *Italic text using single asterisks.*
- _Italic text can also be done with single underscores._
- ***Bold and italic text using triple asterisks.***
- ___Bold and italic text can also be done with triple underscores.___
- ~~Strikethrough text is achieved with double tildes.~~

You can use `inline code` by wrapping text in backticks. For example, `const variable = "value";`.

---

### Heading 3: Lists

#### Unordered Lists

An unordered list can be created using asterisks, pluses, or hyphens.

* Red
    * Dark Red
    * Light Red
        * Pink
+   Green
-   Blue
    -   Navy Blue

#### Ordered Lists

An ordered list uses numbers followed by periods.

1.  First item
2.  Second item
    1.  Sub-item 2.1
    2.  Sub-item 2.2
        1. Nested sub-item 2.2.1
3.  Third item
42. The actual number used doesn't affect the HTML output's numbering (it will be sequential), but it's good practice to number them correctly in Markdown.

#### Task Lists (GitHub Flavored Markdown)

- [x] Write the introduction.
- [ ] Develop the main content.
  - [ ] Section A
  - [x] Section B (already done)
- [ ] Write the conclusion.

---

### Heading 3: Links and Images

#### Links

There are several ways to create links:

- Inline link: [Visit Google](https://www.google.com "Google's Homepage")
- Reference-style link: [Markdown Guide][mdg]
- Autolink: <https://www.example.com>

[mdg]: https://www.markdownguide.org "The Markdown Guide"

#### Images

Images are similar to links but are prefixed with an exclamation mark.

- Inline image: ![A cute orange cat](https://placehold.co/300x200/FFA500/FFFFFF?text=Cute+Cat&font=lora "An orange cat placeholder")
- Reference-style image: ![A blue square][blue-square]

[blue-square]: https://placehold.co/100x100/0000FF/FFFFFF?text=Blue&font=montserrat "Blue Square Placeholder"

---

### Heading 3: Blockquotes

Blockquotes are used for quoting text from another source.

> This is a blockquote.
> It can span multiple lines.
>
> > Nested blockquotes are also possible.
> > This adds another level of quotation.
>
> Blockquotes can contain other Markdown elements, such as *italics*, **bold**, or `inline code`.

---

### Heading 3: Code Blocks

#### Indented Code Blocks

    // This is an indented code block.
    // It's created by indenting each line with at least four spaces or one tab.
    function example() {
      console.log("Indented code block.");
    }

#### Fenced Code Blocks

Fenced code blocks are often preferred and allow specifying the language for syntax highlighting.

```javascript
// This is a JavaScript fenced code block
function greet(name) {
  // A simple greeting function
  return `Hello, ${name}!`;
}

let user = "World";
console.log(greet(user));
```python
# This is a Python fenced code block
def add(a, b):
  """This function adds two numbers."""
  return a + b

result = add(5, 3)
print(f"The result is: {result}")
```html
<!DOCTYPE html>
<html>
<head>
    <title>Sample Page</title>
</head>
<body>
    <h1>Hello Markdown!</h1>
    <p>This is a paragraph in HTML.</p>
</body>
</html>
This is a generic fenced code block without a specified language.It's useful for plain text examples or data.Any leading spaces are preserved.
---

### Heading 3: Tables (GitHub Flavored Markdown)

Tables are created using pipes `|` and hyphens `-`. Colons can be used for alignment.

| Left-aligned Header | Center-aligned Header | Right-aligned Header |
| :------------------ | :-------------------: | -------------------: |
| Cell 1              |        Cell 2         |               Cell 3 |
| Item A              |        Item B         |               Item C |
| Short               |   Medium length text  | A very long piece of text that might wrap |
| `code`              | **bold** and *italic* | [Link](#)           |

---

### Heading 3: Horizontal Rules

Horizontal rules can be created using three or more hyphens, asterisks, or underscores on a line by themselves.

---

***

___

---

### Heading 3: Escaping Characters

To display a literal character that has special meaning in Markdown syntax, precede it with a backslash `\`.

\*This is not italic.\* \[This is not a link label.]
\# This is not a heading.
\`This is not inline code.\`
\\This is a literal backslash.

---

### Heading 3: Inline HTML

Markdown allows for inline HTML, though its interpretation can vary between parsers.

<p style="color: green; font-weight: bold;">This paragraph is styled using inline HTML to be green and bold.</p>

<div>
  This text is inside an HTML &lt;div&gt; element.
  <ul>
    <li>HTML List Item 1</li>
    <li>HTML List Item 2</li>
  </ul>
</div>

<details>
  <summary>Click to expand (HTML Details Element)</summary>
  <p>This is some hidden content that appears when the summary is clicked. Useful for spoilers or lengthy explanations.</p>
</details>

---

## Heading 2: Extended Syntax (Support Varies)

Some Markdown parsers support extended syntax features.

### Heading 3: Footnotes

Here's some text with a footnote.[^sample_footnote] And another one for good measure.[^another-fn]

[^sample_footnote]: This is the content of the footnote. It can be a bit longer and explain things in more detail.
    It can even have multiple paragraphs if subsequent lines are indented.

[^another-fn]: This is another footnote. Footnotes are typically rendered at the bottom of the document.

### Heading 3: Definition Lists (Not Standard, but Common Extension)

Apple
:   A fruit, often red, green, or yellow.

Orange
:   A citrus fruit, known for its vitamin C content.
:   Also a color.

---

This concludes the comprehensive Markdown sample. It covers a wide range of elements commonly found in Markdown documents and its various flavors.

