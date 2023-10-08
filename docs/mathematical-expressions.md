# **Mathematical Expressions**

Markdown supports writing mathematical expressions using $\LaTeX$-style syntax. You can use this syntax to render mathematical formulae and equations beautifully. Here is how to write mathematical expressions in Markdown.

---

## **Inline Mathematical Expression**

To include a math expression inline along with the text, enclose the expression in single dollar `$` sign. For example,

<div markdown = "1" class="example">

```
The pythagorean theorem is: $h^2=p^2+b^2$
```

This renders as

<div markdown="1" class="output">

The pythagorean theorem is: $h^2=p^2+b^2$

</div>

</div>

---

## **Displayed Mathematical Expression**

To add a math expression as a block, start a new line and enclose the expression between two dollar signs. For example,

<div markdown = "1" class="example">

```
$$
\int_{0}^{1} x^2 dx
$$
```

This renders as

$$
\int_{0}^{1} x^2 dx
$$

</div>

You can find the list of supported functions at <a href="https://katex.org/docs/supported.html" target="_blank">katex.org</a>.

Markdown's support for $\LaTeX$-style math notation allows seamlessly integration of mathematical expressions into your documents, making them suitable for scientific, technical, or educational content.

---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.css">
<script src="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/contrib/auto-render.min.js" onload="renderMathInElement(document.body);"></script>

<script type='text/javascript'>

(function()
{
  if( window.localStorage )
  {
    if( !localStorage.getItem('firstLoad') )
    {
      localStorage['firstLoad'] = true;
      window.location.reload();
    }  
    else
      localStorage.removeItem('firstLoad');
  }
})();

</script>