---
title: "Hugo Sewing Feature"
layout: "single-simple"
---

Hugo-Sewing is a simple, clean, and flexible Hugo theme suitable for personal blogs and group websites. This article will present the basic markdown and shortcode can be used in Hugo-Sewing.

# H1 Markdown Style

## H2 Markdown Style
### H3 Markdown Style
#### H4 Markdown Style
##### H5 Markdown Style
###### H6 Markdown Style

### List 

- Water
- Water
	1. Water
	2. Water
- Water
  - Water
  - Water
  	1. Water
  	2. Water

### Table

| Water     | *Water* | Water |
| --------- | ------- | ----- |
| Water     | Water   | Water |
| **Water** | Water   | Water |
| Water     | Water   | Water |

### Math

For example, 

`$1 + 1 = 11111111$`

You can add Tags & References:

`$$p(x) = \frac{1}{\sigma \sqrt{2 \pi}} exp \left(-\frac{1}{2}\left[\frac{x-\mu}{\sigma}\right]^2\right)\tag{1.1}\label{eq1.1}$$`

Aligning equations are also possible, 

`\begin{align}
\sqrt{37} & = \sqrt{\frac{73^2-1}{12^2}} \\
 & = \sqrt{\frac{73^2}{12^2}\cdot\frac{73^2-1}{73^2}} \\ 
 & = \sqrt{\frac{73^2}{12^2}}\sqrt{\frac{73^2-1}{73^2}} \\
 & = \frac{73}{12}\sqrt{1 - \frac{1}{73^2}} \\ 
 & \approx \frac{73}{12}\left(1 - \frac{1}{2\cdot73^2}\right)
\end{align}`

### Shake style

```markdown
{< shake effect="shake" >}Basic shake{< /shake >}

{< shake effect="shake-hard" >}Hard shake{< /shake >}

{< shake effect="shake-slow" >}Slow shake{< /shake >}

{< shake effect="shake-little" >}Little shake{< /shake >}

{< shake effect="shake-horizontal" >}horizontal shake{< /shake >}

{< shake effect="shake-vertical" >}vertical shake{< /shake >}

{< shake effect="shake-rotate" >}rotate shake{< /shake >}

{< shake effect="shake-opacity" >}opacity shake{< /shake >}

{< shake effect="shake-crazy" >}crazy shake{< /shake >}

{< shake effect="shake-freeze" >}freez shake{< /shake >}

{< shake effect="shake-constant" >}constant shake{< /shake >}

// double {{}}
```


{{< shake effect="shake" >}}Basic shake{{< /shake >}}

{{< shake effect="shake-hard" >}}Hard shake{{< /shake >}}

{{< shake effect="shake-slow" >}}Slow shake{{< /shake >}}

{{< shake effect="shake-little" >}}Little shake{{< /shake >}}

{{< shake effect="shake-horizontal" >}}horizontal shake{{< /shake >}}

{{< shake effect="shake-vertical" >}}vertical shake{{< /shake >}}

{{< shake effect="shake-rotate" >}}rotate shake{{< /shake >}}

{{< shake effect="shake-opacity" >}}opacity shake{{< /shake >}}

{{< shake effect="shake-crazy" >}}crazy shake{{< /shake >}}

{{< shake effect="shake-freeze" >}}freez shake{{< /shake >}}

{{< shake effect="shake-constant" >}}constant shake{{< /shake >}}




### Mark

```
{< mark text="Mark!" >}

// double {{}}
```

{{< mark text="Mark!" >}}



### Toggle

```
{< toggle "Toggle" >}
Suprise!
{< /toggle >}

// double {{}}
```

{{< toggle "Toggle" >}}

Suprise!

{{< /toggle >}}



### Colorful underline

```markdown
{< underline color="#183055" content="huge sewing test" >}
<br/>
{< underline color="#11AD45" content="huge sewing test" >}
<br/>
{< underline color="#ffdd00" content="huge sewing test" >}
<br/>
{< underline color="#ff2200" content="huge sewing test" >}

// double {{}}
```

{{< underline color="#183055" content="huge sewing test" >}}
<br/>
{{< underline color="#11AD45" content="huge sewing test" >}}
<br/>
{{< underline color="#ffdd00" content="huge sewing test" >}}
<br/>
{{< underline color="#ff2200" content="huge sewing test" >}}



### Blur words

```markdown
Hello <span class="blur">World!<br>Next line.</span>
```

Hello <span class="blur">World!<br>Next line.</span>



### Hide words

```markdown
Hello <span class="shady">World!<br>Next line.</span>
```

Hello <span class="shady">World!<br>Next line.</span>



### Colorful words

```markdown
<font class="colorfulfont"> Hello World!!<br>Hello! Hello! Hello! Hello! Hello!<br>Next line.</font>
```

<font class="colorfulfont"> Hello World!!<br>Hello! Hello! Hello! Hello! Hello!<br>Next line.</font>



### Align

```
{< align left "left" >}
{< align center "center" >}
{< align right "right" >}

// double {{}}
```

{{< align left "left" >}}
{{< align center "center" >}}
{{< align right "right" >}}



### Blockquote

```
{< blockquote author="Author" link="https://github.com" title="Source" >}

Test sentence.

{< /blockquote >}

// double {{}}
```

{{< blockquote author="Author" link="https://github.com" title="Source" >}}

Test sentence.

{{< /blockquote >}}



### Timeline

```
{< timeline date="2024/01/01" title="Happy New Year!" description="Happy New Year!" tags="Hello"  >}

{< timeline date="2023/01/01" title="Happy New Year!" description="Happy New Year!" tags="Hello"  >}

{< timeline date="2022/01/01" title="Happy New Year!" description="Happy New Year!" tags="Hello"  >}

// double {{}}
```

{{< timeline date="2024/01/01" title="Happy New Year!" description="Happy New Year!" tags="Hello"  >}}

{{< timeline date="2023/01/01" title="Happy New Year!" description="Happy New Year!" tags="Hello"  >}}

{{< timeline date="2022/01/01" title="Happy New Year!" description="Happy New Year!" tags="Hello"  >}}


### Spotify

```
{< spotify type="track" id="3TxjMrMGWFP0jkIy0tVvVn" height="80px">}

// double {{}}
```

{{< spotify type="track" id="3TxjMrMGWFP0jkIy0tVvVn" height="80px">}}


### Single picture

```markdown
{< figure src="https://unsplash.it/1920/1080/?random=4" title="Unplash Random" caption="Caption" width="500">}

// double {{}}
```

{{< figure src="https://unsplash.it/1920/1080/?random=4" title="Unplash Random" caption="Caption" width="500">}}


### Image Carousel

```
{< imgloop "/blog/hugo-sewing3.jpg,/blog/hugo-sewing2.jpg,/blog/hugo-sewing1.jpg" >}}

// double {{}}
```

{{< imgloop "/blog/hugo-sewing3.jpg,/blog/hugo-sewing2.jpg,/blog/hugo-sewing1.jpg" >}}


### Gallery

```
<gallery>![name1](/blog/hugo-sewing1.jpg)![name2](/blog/hugo-sewing2.jpg)![name3](/blog/hugo-sewing3.jpg)</gallery> // markdown

<gallery>
    <img src="https://haiyankong.github.io/project/project.png">
	<img src="https://haiyankong.github.io/project/project.png">
	<img src="https://haiyankong.github.io/project/project.png">
</gallery> // link
```

<gallery>![name1](/blog/hugo-sewing1.jpg)![name2](/blog/hugo-sewing2.jpg)![name3](/blog/hugo-sewing3.jpg)</gallery>


### Youtube

```markdown
{< youtube 4UOeBM5BwdY >}

// double {{}}
```

{{< youtube 4UOeBM5BwdY >}}



### Vimeo

```markdown
{< vimeo 146022717 >}

// double {{}}
```

{{< vimeo 146022717 >}}



### Gist

```markdown
{< gist spf13 7896402 >}

// double {{}}
```

{{< gist spf13 7896402 >}}


### PDF/PPT

```
{< pdf src="/info/cv.pdf" >}

// double {{}}
```

{{< pdf src="/info/cv.pdf" >}}



# Reference

- [https://fourxiajiao.github.io/2022/hugo-blog/](https://fourxiajiao.github.io/2022/hugo-blog/)
- [https://www.sleepymoon.cyou/2023/hugo-shortcodes/](https://www.sleepymoon.cyou/2023/hugo-shortcodes/)
