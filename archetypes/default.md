---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
authors: {{ .Site.Params.Author }}
---