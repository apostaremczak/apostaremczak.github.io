# Blog by Angelika Postaremczak

A simple blog hosted on GitHub Pages. Used whenever I feel the need to share something with the world.

## Local development

To preview the changes, run

```shell
bundle exec jekyll serve
```

Pass the `--livereload` option to serve to automatically refresh the page with each change you make to the source files: 

```shell
bundle exec jekyll serve --livereload
```

## Writing new posts

Using the [jekyll-post](https://marketplace.visualstudio.com/items?itemName=rohgarg.jekyll-post) VSC plugin. Right click on the `_post` directory and choose "New post". It will follow the template from `.post-template`.

## Adding new tags

Create a `tag-name.md` file in `tags/` and start it with:

```
---
layout: tag
tag: visible-tag-name
title: Title of the article listing all the posts with this tag
---
```
