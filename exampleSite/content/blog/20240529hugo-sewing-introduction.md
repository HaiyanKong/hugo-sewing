---
title: "Hugo-Sewing Introduction"
date: 2024-05-29
author: Haiyan Kong
slug: hugo-sewing-introduction
draft: false
categories:
  - Hugo-Sewing
---

<div align="center">

![Static Badge](https://img.shields.io/badge/license-MIT-blue.svg)

[Demo site](https://haiyankong.github.io/hugo-sewing-demo/)

</div>

Hugo-Sewing is a simple, clean, and flexible Hugo theme suitable for personal blogs and group websites.

## Background

Hugo-Sewing is heavily based on [Hugo-Xmin](https://github.com/yihui/hugo-xmin), with modifications mainly inspired by [Shayan Hosseini's website](https://github.com/shayanh), [Hugo-Astatine-Theme](https://github.com/hugcis/hugo-astatine-theme), and [Hugo-Holy](https://github.com/serkodev/holy):

- The base of Hugo-ht is [Yihui Xie](https://github.com/yihui)'s [Hugo-Xmin](https://github.com/yihui/hugo-xmin).
- The academic layout ("Home", "Project", "Publication", and "People") is modified the code from [Shayan Hosseini's website](http://shayanh.com/) by [Shayan Hosseini](https://github.com/shayanh) and [Hugo-Astatine-Theme](https://github.com/hugcis/hugo-astatine-theme) by [Hugo Cisneros](https://hugocisneros.com/)
- The visual styles (navigation, index list, and footer) based on the [Hugo-Holy](https://github.com/serkodev/holy) theme by [SerKo](https://serko.dev/).
- Markdown style based on [Hugo-HT](https://github.com/hongtaoh/hugo-ht) theme by [Hongtao Hao](https://hongtaoh.com/).
- Shortcode ported from: [tutorial](https://www.sleepymoon.cyou/2023/hugo-shortcodes/) by [https://www.sleepymoon.cyou/](https://www.sleepymoon.cyou/) and [tutorial](https://fourxiajiao.github.io/2022/hugo-blog/) by [https://fourxiajiao.github.io/](https://fourxiajiao.github.io/).
- Toc style ported from: [tutorial](https://www.sulvblog.cn/posts/blog/hugo_toc_side/) by [Kevin Xu](https://www.sulvblog.cn/).
- ......

This amalgamation of influences led to the name "Hugo-Sewing," symbolizing the process of intricately stitching together these diverse elements to create a cohesive theme.

## Installation

This theme requires Hugo Extended >= 0.128.0.

> Note: If you encounter a "443: Timed out" error when using either method, it's likely due to internet connectivity issues. In that case, you can download the repository and place the `hugo-sewing` folder inside the `themes` directory. Then, simply copy the files from `hugo-sewing/exampleSite` to the root folder and run `hugo server -D`.

### Direct Clone

```
hugo new site demosite
cd demosite/themes
git clone https://github.com/HaiyanKong/hugo-sewing
cd ..
cp -r themes/hugo-sewing/exampleSite/* .
```

```
hugo server -D
```
Then, open `http://localhost:1313/`, then you will see the website.

### Submodule

You can also add hugo-sewing as a submodule:

```
hugo new site demosite
cd demosite
git init
git submodule add https://github.com/HaiyanKong/hugo-sewing.git themes/hugo-sewing
cp -r themes/hugo-sewing/exampleSite/* .
```

```
hugo server -D
```
Then, open `http://localhost:1313/`, then you will see the website.

#### Update with submodule

```
cd themes/hugo-sewing
git checkout main && git pull
cd ..
git add hugo-sewing
git commit -m "updating submodule to latest"
cd ..
```
> The above code copied from [hongtaoh](https://github.com/hongtaoh)/[hugo-ht](https://github.com/hongtaoh/hugo-ht)
> The difference between two methods:
>
> If you add it as a submodule, the `hugo-sewing` theme you use is connected to this repository. The benefit is that you can keep it updated, but there is a caveat: if you make lots of changes to the styles based on your personal preferences, these changes might be lost.
>
> Simply `git clone` is recommended if:
>
> - You pretty satisfied with the current version of `hugo-sewing`; and/or
> - You are going to make changes according to your personal taste; and/or
> - You are not familiar with Git and do not know how to update the submodule.
>
> To update the submodule, run the following codes at the root directory of your hugo project:
>
> ```
> cd themes/hugo-sewing
> git checkout main && git pull
> cd ..
> git add hugo-ht
> git commit -m "updating submodule to latest"
> cd ..
> ```
>
> The above codes came from [paularmstrong](https://github.com/tj/git-extras/pull/80#issuecomment-3992323).
