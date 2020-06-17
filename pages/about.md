---
layout: page
title: Обо мне
permalink: /about/
weight: 3
---

# **Обо мне**

Привет, я **{{ site.author.name }}** :wave:,<br>
Я копирайтер.

Это значит - я управляю словом. Я помогаю мысли, облаченной в слово дойти до читателя. 
Больше всего на свете я обожаю тексты. Читать, писать, править и вычитывать. 

Я всегда готов поработать над интересным проектом. 

<div class="row">
{% include about/skills.html title="Интересна работа:" source=site.data.programming-skills %}
{% include about/skills.html title="Я умею:" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
