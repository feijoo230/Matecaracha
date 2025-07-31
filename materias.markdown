---
layout: default
title: "Materias"
---

<header>
  <img src="{{ site.logo }}" alt="Logo Matecaracha">
  <h1>{{ site.title }}</h1>
</header>

<nav>
  <a href="/">Inicio</a>
  <a href="/materias">Materias</a>
  <a href="/profesores">Profesores</a>
  <a href="/desafio">Desafío</a>
  <a href="/contacto">Contacto</a>
</nav>

<section>
  <h2>Materias que ofrecemos</h2>
  <ul>
    {% for materia in site.materias %}
      <li>{{ materia }}</li>
    {% endfor %}
  </ul>
</section>
