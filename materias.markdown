---
layout: default
title: "Materias"
---

<header>
  <img src="{{ site.logo }}" alt="Logo Matecaracha">
  <h1>{{ site.title }}</h1>
</header>

<nav>
  <a href="https://feijoo230.github.io/matecaracha/">Inicio</a>
  <a href="https://feijoo230.github.io/matecaracha/materias">Materias</a>
  <a href="https://feijoo230.github.io/matecaracha/profesores">Profesores</a>
  <a href="https://feijoo230.github.io/matecaracha/desafio">Desafío</a>
  <a href="https://feijoo230.github.io/matecaracha/contacto">Contacto</a>
</nav>

<section>
  <h2>Materias que ofrecemos</h2>
  <ul>
    {% for materia in site.materias %}
      <li>{{ materia }}</li>
    {% endfor %}
  </ul>
</section>
