# **Basic Formatting Syntax**

## **Headings**

To create heading in Markdown, simply use the number sign `#` followed by the heading text. The number of `#` symbols before the heading text determines the level of the heading.

- `# Heading 1`
- `## Heading 2`
- `### Heading 3`

Similarly it goes upto six levels of headings.

---

## **Text Styling**

In Markdown, there are great options to style text, add emphasis, and add visual variety to your content. Here's a breakdown of different text styling techniques along their corresponding syntax and output.

| Style | Syntax | Output |
| --- | --- | --- |
| Bold | `This is **bold** text` | This is **bold** text |
| Italic | `This text is *italicized*` | This text is *italicized* |
| Bold & Italic | `This text is ***bold & italicized***` | This text is ***bold & italicized*** |
| Strikethrough | `This was a ~~mistake~~` | This was a ~~mistake~~ |
| Highlight | `This is ==important==` | This is ==important== |
| Subscript | `H~2~O` | H~2~O |
| Superscript | `n^th^` | n^th^ |

---

## **Layout and Structure**

Markdown offers some simple ways to control the layout and structure of your content, including - horizontal lines, line brakes, and paragraphs.

### **Horizontal Rule**

To create a horizontal rule, use atleast three hyphens `-`, or astrisks `*`, or underscores `_` on a new line and then return. For example,

<div markdown = "1" class="example">

```
---
```

This renders as

---

</div>

### **Line Break**

For a simple line within a paragraph, end a line with atleast two spaces. This produces a soft break, maintaining the text within the same paragraph. For example,

<div markdown = "1" class="example">

```
This is first line.  
This is second line.
```

This renders as

<div markdown="1" class="output">

This is first line.  
This is second line.

</div>

</div>

### **Paragraph**

Markdown automatically creates paragraphs for blocks of text seperated by one blank line. For example,

<div markdown = "1" class="example">

```
This is first paragraph.

This is second paragraph.
```

This renders as

<div markdown="1" class="output">

This is first paragraph.

This is second paragraph.

</div>

</div>

---

## **Blockquotes**

Blockquotes can be used to effectively highlight and separate quoted text from the main content.

To create a blockquote, use `>` followed by a space before the quoted text. For example,

<div markdown = "1" class="example">

```
> Be so good they can't ignore you.
```

This renders as

<div markdown="1" class="output">

> Be so good they can't ignore you.

</div>

</div>

---

## **Adding Emoticons**

One can seamlessly integrate emojis into a Markdown document.

To include an emoji, use `:emoji_code:`. You can even add emojis by directly pasting it into the Markdown document. For example,

<div markdown = "1" class="example">

```
I'm feeling lucky! :smiley:  
Copy and paste emojis directly. 👍
```

This renders as

<div markdown="1" class="output">

I'm feeling lucky! :smiley:  
Copy and paste emojis directly. 👍

</div>

</div>

You can find a wide range of emojis at <a href="https://emojipedia.org/" target="_blank">emojipedia.org</a>.

---