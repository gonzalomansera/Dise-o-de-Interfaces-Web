# 🎯 Proyecto Final: Tarjeta de Presentación Personal

## 📖 Descripción

Crear una página web personal tipo "tarjeta de presentación" que incluya información sobre ti, tus habilidades y un formulario de contacto. El proyecto integra todos los conceptos vistos hasta ahora: **HTML5 semántico**, **modelo de caja CSS**, **selectores avanzados** y **formularios con validación**.


## 🎯 Objetivos de Aprendizaje

Al completar este proyecto demostrarás que sabes:

- ✅ Estructurar un documento HTML5 con etiquetas semánticas
- ✅ Aplicar el modelo de caja para controlar dimensiones y espaciado
- ✅ Usar diferentes tipos de selectores CSS
- ✅ Crear formularios con validación nativa HTML5
- ✅ Estilizar formularios con pseudo-clases CSS
- ✅ Centrar elementos horizontalmente
- ✅ Validar código con W3C Validator

---

## 📋 Especificaciones Técnicas

### **1. Estructura HTML5 Obligatoria**

Tu página DEBE contener estos elementos semánticos:

#### `<header>`
- Tu nombre (en `<h1>`)
- Tu profesión o título (en `<p>` o `<h2>`)
- Foto de perfil
- Usa `<figure>` y `<figcaption>` para la foto

#### `<nav>`
- Enlaces a las diferentes secciones de tu página
- Mínimo 3 enlaces: #sobre-mi, #habilidades, #contacto
- Puede estar dentro o fuera del `<header>`

#### `<main>`
Contiene 3 secciones:

**1. `<section id="sobre-mi">`**
- Título con `<h2>`
- Párrafos con información sobre ti (mínimo 2 párrafos)
- Puede ser información real o ficticia

**2. `<section id="habilidades">`**
- Título con `<h2>`
- Lista `<ul>` con al menos 5 habilidades
- Ejemplo: HTML, CSS, JavaScript, Trabajo en equipo, etc.

**3. `<section id="contacto">`**
- Título con `<h2>`
- Formulario de contacto (ver especificaciones abajo)

#### `<footer>`
- Copyright con el año actual
- Enlaces a redes sociales (mínimo 2)
- Pueden ser enlaces ficticios (#)

---

### **2. Formulario de Contacto**

El formulario DEBE incluir:

| Campo | Type | Atributos |
|-------|------|-----------|
| **Nombre** | text | required, placeholder |
| **Email** | email | required, placeholder |
| **Asunto** | text | required |
| **Mensaje** | textarea | required, rows="5" |
| **Botón enviar** | submit | - |

**Todos los campos son obligatorios.**

---

### **3. Requisitos CSS**

#### **Archivo CSS externo obligatorio**
- Nombre: `estilos.css`
- Vinculado con `<link>`

#### **Aplicar `box-sizing: border-box` globalmente**
```css
* {
    box-sizing: border-box;
}
```

#### **Contenedor principal centrado**
```css
body {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
}
```

#### **Selectores que DEBES usar** (mínimo 5 tipos diferentes):
- ✅ Selector de etiqueta (ej: `body`, `h1`)
- ✅ Selector de clase (ej: `.habilidad`)
- ✅ Selector de ID (ej: `#sobre-mi`)
- ✅ Selector descendente (ej: `nav a`)
- ✅ Pseudo-clase (ej: `a:hover`, `input:focus`)

#### **Estilos mínimos requeridos:**

1. **Tipografía:**
   - Fuente sans-serif para todo el documento
   - Tamaños de fuente diferenciados (h1, h2, p)

2. **Colores:**
   - Color de fondo del body
   - Color de fondo del header
   - Color de los títulos
   - Esquema de colores coherente

3. **Espaciado:**
   - Padding en secciones
   - Margin entre elementos
   - Al menos un elemento centrado con `margin: 0 auto;`

4. **Formulario:**
   - Inputs con padding, border, border-radius
   - Pseudo-clases: `:focus`, `:valid`, `:invalid`
   - Botón con estilos y `:hover`
   - Width al 100% en inputs

5. **Foto de perfil:**
   - Border-radius para hacerla circular: `border-radius: 50%;`
   - Tamaño definido (ej: 150px x 150px)

---

## 🎨 Diseño Visual (Sugerencias)

### **Paleta de colores recomendada:**

Puedes usar esta o crear la tuya propia:

```css
/* Ejemplo de paleta moderna */
:root {
    --color-primario: #2563eb;
    --color-secundario: #7c3aed;
    --color-fondo: #f8fafc;
    --color-texto: #1e293b;
    --color-exito: #10b981;
}
```

### **Layout sugerido:**

```
┌─────────────────────────────┐
│        HEADER               │
│   [Foto] Nombre             │
│   Profesión                 │
│   [Nav: Inicio|Skills|...]  │
└─────────────────────────────┘
┌─────────────────────────────┐
│   SOBRE MÍ                  │
│   Párrafo 1...              │
│   Párrafo 2...              │
└─────────────────────────────┘
┌─────────────────────────────┐
│   HABILIDADES               │
│   • HTML5                   │
│   • CSS3                    │
│   • ...                     │
└─────────────────────────────┘
┌─────────────────────────────┐
│   CONTACTO                  │
│   [Formulario]              │
└─────────────────────────────┘
┌─────────────────────────────┐
│        FOOTER               │
│   © 2025 | GitHub | LinkedIn│
└─────────────────────────────┘
```

---

## ✅ Checklist de Entrega

Antes de entregar, verifica:

### **HTML:**
- [ ] Usa `<!DOCTYPE html>`
- [ ] Incluye `<meta charset="UTF-8">`
- [ ] Todas las etiquetas semánticas están presentes
- [ ] `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` usados correctamente
- [ ] Formulario completo con todos los campos
- [ ] Labels asociados con inputs (atributo `for`)
- [ ] Pasa validación W3C HTML sin errores

### **CSS:**
- [ ] Archivo externo `estilos.css` vinculado
- [ ] Usa `box-sizing: border-box`
- [ ] Mínimo 5 tipos de selectores diferentes
- [ ] Contenedor principal centrado
- [ ] Formulario estilizado con pseudo-clases
- [ ] Esquema de colores coherente
- [ ] Pasa validación W3C CSS sin errores

### **Presentación:**
- [ ] La página se ve bien visualmente
- [ ] No hay texto ilegible
- [ ] Los enlaces funcionan (aunque sean #)
- [ ] El formulario muestra validación visual

---

## 📤 Formato de Entrega

### **Archivos requeridos:**
```
Apellido_Nombre_ProyectoFinal/
├── index.html
├── estilos.css
└── (opcional) foto.jpg o foto.png
```

### **Entrega:**
- Carpeta comprimida (.zip)
- Nombre: `Apellido_Nombre_ProyectoFinal.zip`

---

## 🎓 Evaluación (70% de la nota final)

Ver archivo `rubrica_evaluacion.md` para detalles completos.

**Resumen de puntos:**
- HTML semántico correcto: 20%
- CSS aplicado (selectores, modelo de caja): 25%
- Formulario funcional con validación: 15%
- Validación W3C (HTML + CSS): 10%

---

## 💡 Consejos

### **HTML:**
1. Empieza con la estructura básica (html, head, body)
2. Crea todos los elementos semánticos vacíos primero
3. Luego rellena el contenido de cada sección
4. Deja el formulario para el final
5. Valida el HTML antes de terminar la sesión

### **CSS:**
1. Vincula el CSS y aplica estilos básicos primero (colores, fuentes)
2. Luego trabaja sección por sección
3. Aplica el modelo de caja (padding, margin, border)
4. Estiliza el formulario con pseudo-clases
5. Ajusta detalles finales

### **Finalización:**
1. Valida HTML y CSS - corrige errores
2. Revisa que todo se vea bien
3. Prepara tu presentación (2-3 minutos)
4. Explica 1 desafío que tuviste

---

## 🚫 Errores Comunes a Evitar

- ❌ Olvidar vincular el CSS
- ❌ No usar etiquetas semánticas (usar solo `<div>`)
- ❌ No añadir `required` a los campos del formulario
- ❌ Olvidar el atributo `for` en los `<label>`
- ❌ No validar el código en W3C
- ❌ Usar solo selectores de etiqueta (falta variedad)
- ❌ No aplicar pseudo-clases al formulario

---

## 📚 Recursos de Consulta

- Documento de repaso proporcionado
- MDN Web Docs
- W3C Validators
- DevTools del navegador (F12)

---

¡Este proyecto es tu oportunidad para demostrar todo lo que has aprendido! 💪

**¿Tienes dudas? Pregunta al profesor durante las sesiones de trabajo.**
