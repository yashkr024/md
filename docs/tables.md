# **Tables**

Markdown supports creation of tables to organize data in tabular format. Here is how you can create a table in Markdown.

---

## **Basic Table Structure**

To create a table, use pipe `|` to sepatate columns, and atleast three hyphens `-` in the second row to define column header. You can create tables with as many columns (rows) as required. You must include a blank line before and after the table in order for it to render correctly. For example,

<div markdown = "1" class="example">

```md
| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |
```

This renders as

| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |

</div>

Note that the cells can vary in width and they do not need to be perfectly aligned with columns.

---

## **Table Alignment**

You can adjust the column alignment using colon `:` with the hyphens in the header row. For example,

<div markdown = "1" class="example">

```md
| Left-aligned | Centered | Right-aligned |
| :--- | :---:| ---: |
| Left | Center | Right |
| Left | Center | Right |
```

This renders as

| Left-aligned | Centered | Right-aligned |
| :--- | :---:| ---: |
| Left | Center | Right |
| Left | Center | Right |

</div>

---