# awesome-gists

Bismillah.

awesome-gists is collection of usefull gists that I have collected for helping me to develop app.

## Rules

- Only accept gists with max 2 file.
- gists must be public access.

## Contribute

1. Fork repo
2. Inside your fork navigate to content/aw-gists
3. Create here new file about gists you want to add. File must have .md extension, i.e. javascript-es6.md
4. Use next template for content

```
+++
title = "Javascript es6"
date = "2021-9-30"
tags = [
    "javascript",
    "es6",
]
#
# description is optional
#
# description = "An optional description for SEO. If not provided, an automatically created summary will be used."
tags = [{{ range $plural, $terms := .Site.Taxonomies }}{{ range $term, $val := $terms }}"{{ printf "%s" $term }}",{{ end }}{{ end }}]
# link gists is link of repo gists not link embed gists!
linkGists="https://gist.github.com/dzakki/8d6f7d783501951ac5406f7d7a7411f1"
+++
```

## Thanks to

- [hugo-bearblog](https://github.com/janraasch/hugo-bearblog)
- all contributes
