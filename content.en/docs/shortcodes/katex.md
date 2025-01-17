---
title: KaTeX
---
# KaTeX

KaTeX shortcode let you render math typesetting in markdown document. See [KaTeX](https://katex.org/)

## Example
{{% columns %}}

```latex
{{</* kk >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /kk */>}}
```

<--->

{{< kk >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /kk >}}

{{% /columns %}}

## Display Mode Example

Here is some inline example: $\pi(x)$ with `$` characters, rendered in the same line. And below is "display" example with `$$` characters:
$$
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$
Text continues here.

And some more examples:
$ inline $
$$ display $$
\\( inline \\)
\\[ display \\]

<span>
\(inline\)
</span>

<span>
\[display\]
</span>