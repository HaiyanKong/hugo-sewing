---
title: "Hugo-Sewing Shortcodes"
date: 2024-05-20
author: Your Name
slug: hugo-sewing-shortcodes
draft: false
categories:
  - Hugo-Sewing
---

## Reference

- [https://fourxiajiao.github.io/2022/hugo-blog/](https://fourxiajiao.github.io/2022/hugo-blog/)
- [https://www.sleepymoon.cyou/2023/hugo-shortcodes/](https://www.sleepymoon.cyou/2023/hugo-shortcodes/)

## Spotify
-   1 usage

```
< spotify type="track" id="6DJ3dfsY7fOU161ZMjzWIH" height="80px">

// please use double {{ }}
```

-   2 showing

{{< spotify type="track" id="6DJ3dfsY7fOU161ZMjzWIH" height="80px">}}


## Mark

-   1 usage

```
{< mark text="Mark!" >} 

// please use double {{ }}
```

-   2 showing

{{< mark text="Mark!" >}}


## Abbreviation

- 1 usage

```
{< abbr title="real test" text="this shortcodes can only show on PC" >} 

// please use double {{ }}
```

- 2 showing

{{< abbr title="real test" text="this shortcodes can only show on PC" >}}


## Toggle

- 1 usage

```
< toggle "Toggle" >
Suprise!
< /toggle >

 // please use double {{ }}
```

- 2 showing

{{< toggle "Toggle" >}}

Suprise!

{{< /toggle >}}


## Align

- 1 usage

```
{< align left "left" >}
{< align center "center" >}
{< align right "right" >}

// please use double {{ }}
```

- 2 showing

{{< align left "left" >}}
{{< align center "center" >}}
{{< align right "right" >}}

## Blockquote

- 1 usage

```
{< blockquote author="René Descartes" link="https://github.com/eallion/memos.top" title="Source" >}
<p>Je <del>memos</del>, donc je suis.</p>
{< /blockquote >}

// please use double {{ }}
```

- 2 showing

{{< blockquote author="René Descartes" link="https://github.com/eallion/memos.top" title="Source" >}}

<p>Je <del>memos</del>, donc je suis.</p>

{{< /blockquote >}}


## Keyboard Style

- 1 usage

```
<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd>
```

- 2 showing

<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd>

## Image Carousel

- 1 usage

```
{< imgloop "/blog/hugo-sewing3.jpg,/blog/hugo-sewing2.jpg,/blog/hugo-sewing1.jpg" >}

// please use double {{ }}
```

- 2 showing


{{< imgloop "/blog/hugo-sewing3.jpg,/blog/hugo-sewing2.jpg,/blog/hugo-sewing1.jpg" >}}

## Gallery

### 1 usage

```
<gallery>![name1](/blog/hugo-sewing1.jpg)![name2](/blog/hugo-sewing2.jpg)![name3](/blog/hugo-sewing3.jpg)</gallery> // markdown

<gallery>
    <img src="https://haiyankong.github.io/hugo-sewing-demo/info/profile.png">
	<img src="https://haiyankong.github.io/hugo-sewing-demo/info/profile.png">
	<img src="https://haiyankong.github.io/hugo-sewing-demo/info/profile.png">
</gallery> // link
```

### 2 showing

<gallery>![name1](/blog/hugo-sewing1.jpg)![name2](/blog/hugo-sewing2.jpg)![name3](/blog/hugo-sewing3.jpg)</gallery>

## PDF/PPT

- 1 usage
```
{< pdf src="/blog/hugo-sewing.pdf" >}
```

- 2 showing
{{< pdf src="/blog/hugo-sewing.pdf" >}}
