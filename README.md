# Gros Xake Taldea · Propuesta de rediseño web

Propuesta **no oficial** de rediseño de la web de Gros Xake Taldea, club de ajedrez de Donosti fundado en 1991. Los contenidos se tomaron de [grosxake.com](https://www.grosxake.com/) el 18/11/2026; la información válida es la que publica el club.

## Qué incluye

- Web de una sola página, bilingüe (castellano y euskera), con secciones de Club, Legado, Escuela, Torneos, Equipos, Noticias, Juego del caballo y Contacto.
- Tipografía Manrope (títulos) e Inter (texto), con tamaños fluidos.
- Intro 3D en escritorio; en móvil se muestra un caballo estático para que cargue más rápido.
- Formularios de consulta, inscripción a clases y alta de socio en la página de contacto.

## Formularios

Los formularios envían los datos por correo a través de [FormSubmit](https://formsubmit.co/):

- Consultas → `contacto@grosxake.com`
- Inscripción a clases y alta de socio → `xakegros@telefonica.net`

El primer envío a cada dirección manda un correo de activación que alguien del club tiene que confirmar. Por seguridad, la ficha no pide el número de cuenta bancaria.

## Estructura

```
index.html      página completa (estilos y textos incluidos)
js/app.js       navegación, idiomas, calendario, formularios y juego
js/scene.js     escena 3D de la portada (Three.js)
```

La página no se indexa en buscadores (`noindex`) para no confundirse con la web oficial.
