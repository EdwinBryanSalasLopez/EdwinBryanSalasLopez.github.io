---
layout: single
permalink: /
title: "Edwin Bryan Salas López | Investigador en Inteligencia Artificial y Ciencia de Datos"
excerpt: "Perfil académico de Edwin Bryan Salas López: inteligencia artificial, ciencia de datos, ingeniería de software y sostenibilidad ambiental."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

# Edwin Bryan Salas López

**Profesor investigador | Estudiante de doctorado en Ciencias Naturales e Ingeniería**  
**Universidad Autónoma Metropolitana, Unidad Lerma**

Soy ingeniero en computación y cuento con formación de maestría en Ciencias de la Computación y en Cambio Climático y Biodiversidad. Mi trabajo conecta la inteligencia artificial, la ciencia de datos, la ingeniería de software y las ciencias ambientales, con especial interés en aplicaciones interdisciplinarias para la sostenibilidad.

## Líneas de interés

- **Inteligencia artificial y aprendizaje automático:** desarrollo y estudio de métodos computacionales aplicados a problemas de investigación.
- **Ciencia de datos:** análisis, modelado e interpretación de información compleja.
- **Sostenibilidad y conciencia ambiental:** aplicaciones de la tecnología para el estudio y la comunicación de retos ambientales.
- **Neurociencia computacional e interfaces planta-computadora:** investigación interdisciplinaria que conecta señales y sistemas inteligentes.

## Investigación y trayectoria

Mi formación combina informática, inteligencia artificial y estudios ambientales. He participado en investigaciones relacionadas con el reconocimiento de emociones, la clasificación de señales eléctricas de plantas y la reflexión educativa sobre bioética y cambio climático.

**[Consultar líneas de investigación](/investigacion/)** · **[Ver publicaciones científicas](/publications/)** · **[Experiencia docente](/docencia/)**

## Publicaciones recientes

{% assign publicaciones_ordenadas = site.publications | sort: 'date' | reverse %}
{% for articulo in publicaciones_ordenadas limit:3 %}
- **[{{ articulo.title }}]({{ articulo.url | relative_url }})** ({{ articulo.date | date: '%Y' }}){% if articulo.venue %} — *{{ articulo.venue }}*{% endif %}
{% endfor %}

## Enlaces profesionales

- [LinkedIn](https://www.linkedin.com/in/edwin-salas)
- [GitHub](https://github.com/EdwinBryanSalasLopez)

Para colaboraciones académicas, puedes contactar conmigo mediante mis perfiles profesionales.
