---
---
<div class="text-center">
  {{ range .Site.Menus.main }}
    <a href="{{ .URL }}" title="{{ .Title }}" class="{{ with .Params.class }}{{ . }}{{ end }}">
      {{- .Name -}}
    </a>
  {{ end }}
</div>