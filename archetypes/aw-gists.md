+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"
#
# description is optional
#
# description = "An optional description for SEO. If not provided, an automatically created summary will be used."
tags = [{{ range $plural, $terms := .Site.Taxonomies }}{{ range $term, $val := $terms }}"{{ printf "%s" $term }}",{{ end }}{{ end }}]
linkGists="https://gist.github.com/dzakki/8d6f7d783501951ac5406f7d7a7411f1"
+++
