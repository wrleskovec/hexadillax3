# HeXadillaX

It's another version of `GhoSadillaX`, the theme of `Ghost`.

## Usage

### CONFIG

Copy `_config.sample.yml` to `_config.yml`.

And edit the subjects.

### TAGS && CATEGORIES

Create two folders under your `source` directory: `tags` and `categories`.

Create an `index.md` file under each folder that you've just created.

`tags/index.md`:

```markdown
layout: tags
title: tags
---
```

`categories/index.md`:

```markdown
layout: categories
title: categories
---
```

### DISQUS

Register your own [disqus](https://disqus.com/admin/signup/) account and replace `disqus_shortname` in `_config.yml`.


### Mathjax

 `_config.yml`  `mathjax: true`
