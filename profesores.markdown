---
layout: default
title: "Profesores"
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
  <h2>Nuestros profesores</h2>
  <ul>
    {% for profe in site.profesores %}
      <li><strong>{{ profe.nombre }}</strong> – {{ profe.especialidad }}</li>
    {% endfor %}
  </ul>
</section>
