---
permalink: /about/
toc: false
---

My name is Hai Le \\(a^2+b^2=c^2\\).
Let $M$ be the maximum of $u$ in $\bar \Omega$. We need to show that if $u(x_0)=M$ for some $x_0\in \Omega$ then $u$ is constant. Let ${S_M} = \{ x \in \Omega \;|\;u(x) = M\} $. Since $u$ is continuous, $S_M$ is relatively closed in $\Omega$. We will show that $S_M$ is also relatively open in $\Omega$, then $\Omega$ being connected will imply $S_M=\Omega$.\\
Consider an open ball $B=B(x_0,r)$ center $x_0$ radius $r$ contained in $\Omega$. Consider an arbitrarily smaller ball $B_1=B_1(x_0,r_1)$ inside $B$ with $0<r_1<r$.  We can find a function $h\in C^2(B_1)\cap C^0(\bar B_1) $ satisfying
\[\left\{ \begin{array}{l}
\Delta h = 0\;\;\text{ in } B_1\\
\;\;\;h = u \;\;\text{ on } \partial B_1
\end{array} \right.\]
Since $u$ is locally subharmonic, we have that $u\le h$ in $B$. This implies that
\[M = u({x_0}) \le h({x_0}) = \fint_{\partial B_1} {h(x)dx}  = \fint_{\partial B_1} {u(x)dx}  \le M.\]
Hence, equality must occur, and since $u$ is continuous, $u(x)=M$ on $\partial B_1$. Since $r_1$ is arbitrary, we have that $u(x)=M$ in $B$. Hence, $B\subset S_M$. The proof is complete.

I am a PhD student in Mathematics at Penn State $\mu(x)=0$.

[I'm an inline-style link](https://www.google.com)

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

Three or more...

---

Hyphens

***

Asterisks

___

Underscores

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

In the words of Abraham Lincoln:

> Pardon my French
