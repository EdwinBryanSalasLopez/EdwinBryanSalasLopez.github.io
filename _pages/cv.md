---
layout: archive
title: "Currículum académico"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

# Edwin Bryan Salas López

Profesor investigador y estudiante de doctorado en Ciencias Naturales e Ingeniería en la Universidad Autónoma Metropolitana.

## Formación académica

- **Doctorado en Ciencias Naturales e Ingeniería**, Universidad Autónoma Metropolitana. En curso.
- **Maestría en Ciencias de la Computación**, Universidad Autónoma Metropolitana (2021–2024).
- **Maestría en Cambio Climático y Biodiversidad**, Universidad Rosario Castellanos (2022–2024; mención honorífica según perfil proporcionado).
- **Ingeniería en Computación**, Universidad Autónoma Metropolitana (2015–2021).
- **Diplomado en competencias interdisciplinarias con inteligencia artificial**, Universidad Nacional Autónoma de México (2024–2025).

## Experiencia docente y profesional

Consulta la sección [Docencia](/docencia/) para conocer las instituciones y áreas de trabajo.

## Áreas de especialización

Inteligencia artificial · Ciencia de datos · Ingeniería de software · Neurociencia computacional · Sostenibilidad ambiental.

## Producción académica

{% assign publicaciones_ordenadas = site.publications | sort: 'date' | reverse %}
{% for post in publicaciones_ordenadas %}
- [{{ post.title }}]({{ post.url | relative_url }}) ({{ post.date | date: '%Y' }}). {% if post.venue %}*{{ post.venue }}*.{% endif %}
{% endfor %}

## Perfiles

[GitHub](https://github.com/EdwinBryanSalasLopez) · [LinkedIn](https://www.linkedin.com/in/edwin-salas)
