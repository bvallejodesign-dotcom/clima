# Weather Frontend – Módulo 3

## Descripción de la aplicación

Weather Frontend es una aplicación web de clima desarrollada como proyecto académico.
La app permite visualizar información climática de distintos **lugares (ciudades nacionales e internacionales)** mediante una interfaz clara y responsiva.

La aplicación cuenta con:
- Una vista **Home**, donde se muestran distintas ciudades organizadas en cards con información básica del clima (temperatura, estado, icono).
- Una vista **Detalle**, donde se presenta información ampliada del lugar seleccionado, junto a un pronóstico semanal simulado.

En esta iteración (Módulo 3), el foco está puesto en **mejorar la interfaz visual, la organización de estilos y la mantenibilidad del CSS**, manteniendo la funcionalidad base lograda en el módulo anterior.

---

## Metodología de estilos

Para la organización de estilos se utiliza la metodología **BEM (Block, Element, Modifier)**.

Esta metodología permite:
- Nombres de clases claros y predecibles.
- Separación lógica entre componentes.
- Mejor escalabilidad y mantenimiento del código CSS/SASS.

Ejemplos de clases utilizadas:
- `.weather-app`, `.weather-app__header`, `.weather-app__home`
- `.place-card`, `.place-card__name`, `.place-card__temp`
- `.place-card--sunny`, `.place-card--rainy` (modificadores)

---

## Estructura SASS

Los estilos se desarrollan utilizando **SASS**, organizados en parciales para mejorar la modularidad y reutilización del código.

Estructura principal:

