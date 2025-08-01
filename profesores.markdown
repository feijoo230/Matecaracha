---
layout: default
title: "Profesores"
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
  <h2>Nuestros profesores</h2>
  <ul>
    {% for profe in site.profesores %}
      <li><strong>{{ profe.nombre }}</strong> – {{ profe.especialidad }}</li>
    {% endfor %}
  </ul>
</section>
