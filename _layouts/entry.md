---
layout: faq
{% for faq in site.data.coba %}
title: {{ faq.Index }}
date: {{ faq.Tanggal }}
category: {{ faq.Kategori }}
tags: {{ faq.Tema }}
author: {{ faq.Editor }}
---

{{ faq.Pertanyaan }}

---

{{ faq.Jawaban }}

`{{ faq.Editor }}`
{% endfor %}