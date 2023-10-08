# **Codeblock**

Markdown provides ways to format code snippets both inline and as fenced code block. This is particularly useful when you want to present code examples or highlight specific code within your text.

---

## **Inline Code**

To format a code inline, enclose the code snippet within backticks <code>`</code>. For example,

<div markdown = "1" class="example">

```md
Markdown filename extensions are `.md`, `.markdown`
```

This renders as

<div markdown="1" class="output">

Markdown filename extensions are `.md`, `.markdown`

</div>

</div>

---

## **Fenced Code Block**

For longer code snippets or multiline code, use triple backticks <code>```</code> to create a code block. You can add an optional language identifier after the opening backticks to enable syntax highlighting. Syntax highlighting changes the color and style of source code making it easier to read. For example,

<div markdown = "1" class="example">

````md
```java
public class Main {
    public static void main (String[] args) {
        System.out.println("Happy Coding!");
    }
}
```
````

This renders as

```java
public class Main {
    public static void main (String[] args) {
        System.out.println("Happy Coding!");
    }
}
```

</div>

---