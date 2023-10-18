# **Lists**

Lists allow you to organize your contents efficiently and improve readability. Whether you are making a to-do list, outlining steps, or creating bullet points, Markdown lists make it easy to structure your information.

---

## **Unordered List**

To create an unordered list, use an asterisk `*`, or a plus `+`, a hyphen `-` followed by a space before each list item. For example,

<div markdown = "1" class="example">

```md
- item 1
- item 2
- item 3
```

This renders as

<div markdown="1" class="output">

- item 1
- item 2
- item 3

</div>

</div>

---

## **Ordered List**

To create an ordered list, use number followed by a period and a space before each list item. For example,

<div markdown = "1" class="example">

```md
1. item 1
1. item 2
1. item 3
```

This renders as

<div markdown="1" class="output">

1. item 1
1. item 2
1. item 3

</div>

</div>

---

## **Nested List**

To nest list items, indent the item to nest by using a space to a tab character. For example,

<div markdown = "1" class="example">

```md
1. item 1
    - nested item 1
    - nested item 2
        - another item
1. item 2
    1. nested item
```

This renders as

<div markdown="1" class="output">

1. item 1
    - nested item 1
    - nested item 2
        - another item
1. item 2
    1. nested item

</div>

</div>

---

## **Task List**

Markdown also supports creation of task list, which is essentially an unordered list with checkboxes. In a task list, `[x]` is used to represent completed tasks, and `[ ]` to represent incomplete tasks. For example,

<div markdown = "1" class="example">

```md
- [x] task 1
- [x] task 2
- [ ] task 3
```

This renders as

<div markdown="1" class="output">

- [x] task 1
- [x] task 2
- [ ] task 3

</div>

</div>

---

## **Definition List**

In Markdown, you can create definition list to associate terms to their corresponding definition. Here is how you can create a definition list.

<div markdown = "1" class="example">

```md
Term 1
: definition of term 1

Term 2
: definition of term 2

Term 3
: definition of term 3
```

This renders as

<div markdown="1" class="output">

Term 1
: definition of term 1

Term 2
: definition of term 2

Term 3
: definition of term 3

</div>

</div>

---