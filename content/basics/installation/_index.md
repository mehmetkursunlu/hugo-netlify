---
title: Installation
weight: 15
---

The following steps are here to help you initialize your new website. If you don't know Hugo at all, we strongly suggest you to train by following this [great documentation for beginners](https://gohugo.io/overview/quickstart/).

## Create your project

Hugo provides a `new` command to create a new website.

```
hugo new site <new_project>
```

## Install the theme

Install the **Hugo-theme-learn** theme by following [this documentation](https://gohugo.io/themes/installing/)

The theme's repository is: https://github.com/matcornic/hugo-theme-learn.git

Alternatively, you can [download the theme as .zip](https://github.com/matcornic/hugo-theme-learn/archive/master.zip) file and extract it in the themes directory

## Basic configuration

When building the website, you can set a theme by using `--theme` option. We suggest you to edit your configuration file and set the theme by default. By the way, add requirements for search functionnality to be enabled.

```toml
# Change the default theme to be use when building the site with Hugo
theme = "hugo-theme-learn"

# For search functionnality
[outputs]
home = [ "HTML", "RSS", "JSON"]
```

## Create your first chapter page

Chapters are pages containg other child pages. It has a special layout style and usually just contains a _chapter name_, the _title_ and a _brief abstract_ of the section.

```
### Chapter 1

# Basics

Discover what this Hugo theme is all about and the core-concepts behind it.
```