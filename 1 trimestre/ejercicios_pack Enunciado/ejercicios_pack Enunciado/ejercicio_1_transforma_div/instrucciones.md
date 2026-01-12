# Ejercicio 1: Transforma el DIV

## 🎯 Objetivo

Convertir una estructura HTML basada en `<div>` genéricos a una estructura **semántica HTML5** utilizando las etiquetas apropiadas.


## 📋 Instrucciones

Se te proporciona un archivo `plantilla_base.html` con una estructura HTML antigua que utiliza elementos `<div>` con clases descriptivas.

Tu tarea es **reestructurar el código** reemplazando los `<div>` por las etiquetas semánticas HTML5 apropiadas.

## 🔍 Etiquetas semánticas que debes usar

- `<header>` - Para la cabecera del sitio
- `<nav>` - Para el menú de navegación
- `<main>` - Para el contenido principal
- `<article>` - Para contenido independiente (posts, noticias)
- `<section>` - Para agrupar contenido temático relacionado
- `<aside>` - Para contenido secundario/tangencial
- `<footer>` - Para el pie de página

## ✅ Requisitos

1. **Reemplazar todos los `<div>` estructurales** por etiquetas semánticas apropiadas
2. **Mantener el contenido exactamente igual** (solo cambia las etiquetas)
3. **El HTML debe ser válido** según W3C Validator
4. **Añadir comentarios HTML** explicando brevemente por qué elegiste cada etiqueta

## 📝 Ejemplo de conversión

### ❌ Antes (NO semántico):
```html
<div class="cabecera">
  <h1>Mi Sitio Web</h1>
</div>
```

### ✅ Después (Semántico):
```html
<!-- Cabecera principal del sitio -->
<header>
  <h1>Mi Sitio Web</h1>
</header>
```

## 🎨 Criterios de Evaluación

| Criterio | Puntos |
|----------|--------|
| Uso correcto de `<header>` | 1 |
| Uso correcto de `<nav>` | 1 |
| Uso correcto de `<main>` | 1 |
| Uso correcto de `<article>` | 2 |
| Uso correcto de `<aside>` | 1 |
| Uso correcto de `<footer>` | 1 |
| Comentarios explicativos | 2 |
| Validación W3C sin errores | 1 |
| **TOTAL** | **10 puntos** |

## 📤 Entrega

**Nombre del archivo:** `Apellido_Nombre_Ejercicio1.html`

**Formato:** Archivo HTML único

**Validación:** Debe pasar la validación en https://validator.w3.org/

## 💡 Pistas

1. La navegación principal siempre va en `<nav>`
2. `<main>` debe aparecer **una sola vez** en el documento
3. Un `<article>` debe poder "vivir solo" (contenido autosuficiente)
4. `<aside>` es para información complementaria o secundaria
5. Puedes anidar etiquetas semánticas (ej: `<nav>` dentro de `<header>`)

## ❓ Preguntas frecuentes

**P: ¿Debo eliminar TODOS los `<div>`?**
R: No. Solo los `<div>` estructurales. Los `<div>` que se usan solo para aplicar estilos pueden quedarse.

**P: ¿Puedo usar `<section>` dentro de `<article>`?**
R: Sí, perfectamente válido si tu artículo tiene secciones temáticas.

**P: ¿El `<nav>` va dentro o fuera del `<header>`?**
R: Ambas opciones son válidas. Depende del diseño. En este ejercicio, colócalo dentro del `<header>`.

## 🔗 Referencias

- [MDN: Elementos de sección HTML5](https://developer.mozilla.org/es/docs/Web/HTML/Element#secci%C3%B3n_de_contenido)
- [HTML5 Doctor: Flowchart](http://html5doctor.com/downloads/h5d-sectioning-flowchart.pdf)

---

¡Buena suerte! Recuerda que la semántica no cambia cómo se ve la página, pero sí cómo se entiende. 🚀
