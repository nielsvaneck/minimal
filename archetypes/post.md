---
title: "{{ replace (replace .TranslationBaseName "-" " ") (now.Format "2006 01 02 ") "" | title }}"
date: {{ dateFormat "2006-01-02" .Date }}
tags: []
draft: true
---
