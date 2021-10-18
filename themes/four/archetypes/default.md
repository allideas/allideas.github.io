---
draft: true
date: {{ .Date }}
title: "{{ replace .TranslationBaseName "-" " " | title }}"
slug: {{ .BaseFileName }}
url: /{{ .BaseFileName }}.html
author: "{{ $author }}"
tags:
    - Resep Mudah

categories:
    - Resep

image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160

---