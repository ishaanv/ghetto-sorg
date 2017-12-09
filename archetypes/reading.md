---
Book: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
rating: {{ .Rating }}
draft: true
---