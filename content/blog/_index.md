---
title: "Blog"
date: 2023-11-18
draft: false
---

{{ range .Pages }}
   <article>
     <h2><a href="{{ .Permalink }}">{{ .Title }}</a></h2>
     <p>{{ .Summary }}</p>
   </article>
{{ end }}
