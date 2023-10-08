# **Links and Images**

Markdown provides convenient syntax to add both links and images within your document. Here is how you add links and images in your document.

---

## **Links**

### **Inline Link**

To create a clickable link inline, use square brackets `[]` for the link text followed by parentheses `()` containing the URL. For example,

<div markdown = "1" class="example">

```md
Search for it on [Google](https://www.google.com/)
```

This renders as

<div markdown="1" class="output">

Search for it on [Google](https://www.google.com/)

</div>

</div>

The above example uses *absolute link* to link to other page. You can also use *relative link* to link files present locally on you computer. The below example shows how to link a file named `codeblock.md` present within the current working directory.

<div markdown = "1" class="example">

```md
Click [here](./codeblock.md) to see how to format code in markdown.
```

This renders as

<div markdown="1" class="output">

Click [here](./codeblock.md) to see how to format code in markdown.

</div>

</div>

### **Section Link**

You can also link to different sections within a Markdown document. For example,

<div markdown = "1" class="example">

```md
Click [here](#) to go back to top.  
Click [here](#links) to see how to add links in Markdown.
```

This renders as

<div markdown="1" class="output">

Click [here](#) to go back to top.  
Click [here](#links) to see how to add links in Markdown.

</div>

</div>

Some key points:

- `#` links back to top of a page.
- Markdown automatically generates `id` for every heading and is used to link to different sections within a document. In the above example, `links` is an `id`.

---

## **Images**

To add an image, use an exclamation mark `!`, followed by square brackets `[]` for alt text, and then parentheses `()` for the image path.

<div markdown = "1" class="example">

```md
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
```

This renders as

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

</div>

You can also give a title to an image using the following syntax.

<div markdown = "1" class="example">

```md
![alt-text](image_url "title")
```

</div>

You can even use *relative path* to link to an image present locally on your computer.

---