# Ejercicio 2: Cajas con Box Model

## 🎯 Objetivo

Comprender el **modelo de caja** de CSS creando y calculando las dimensiones reales de elementos con diferentes configuraciones de `box-sizing`, padding, border y margin.

## 📋 Instrucciones

Se te proporciona un archivo `plantilla_base.html` con tres cajas (`<div>`) sin estilos.

Tu tarea es:
1. Aplicar estilos CSS específicos a cada caja según las especificaciones
2. Calcular las dimensiones reales que ocupará cada caja
3. Verificar tus cálculos usando DevTools del navegador

## 📐 Especificaciones de las Cajas

### **Caja 1: Content-box (modo por defecto)**
```css
width: 300px;
padding: 20px;
border: 5px solid #333;
background-color: #e3f2fd;
box-sizing: content-box;
```

**Pregunta:** ¿Cuál es el ancho total real de esta caja?

**Cálculo:** _____ px

---

### **Caja 2: Border-box (modo recomendado)**
```css
width: 300px;
padding: 20px;
border: 5px solid #333;
background-color: #fff3e0;
box-sizing: border-box;
```

**Pregunta:** ¿Cuál es el ancho total real de esta caja?

**Cálculo:** _____ px

---

### **Caja 3: Centrada horizontalmente**
```css
width: 400px;
padding: 30px;
border: 3px solid #4caf50;
background-color: #f1f8e9;
box-sizing: border-box;
margin: 0 auto;
```

**Pregunta:** ¿Qué hace `margin: 0 auto;`?

**Respuesta:** _____________________

---

## ✅ Requisitos

1. **Crear un archivo CSS externo** llamado `estilos2.css`
2. **Vincular el CSS** al archivo HTML
3. **Aplicar los estilos** especificados a cada caja
4. **Añadir un título `<h2>`** antes de cada caja explicando su configuración
5. **Completar los cálculos** en comentarios CSS
6. **Verificar con DevTools** que tus cálculos son correctos
7. **Validar** el CSS en W3C Validator

## 📝 Estructura esperada del CSS

```css
/* =========================
   EJERCICIO 2: BOX MODEL
   Nombre: [Tu nombre]
   =========================*/

/* RESETEO BÁSICO */
* {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    padding: 2rem;
    background-color: #f5f5f5;
}

/* CAJA 1: Content-box */
/* Cálculo del ancho total:
   Contenido: 300px
   Padding izquierdo: ___px
   Padding derecho: ___px
   Border izquierdo: ___px
   Border derecho: ___px
   TOTAL: ___px
*/
.caja1 {
    /* Añadir estilos aquí */
}

/* CAJA 2: Border-box */
/* ... */

/* CAJA 3: Centrada */
/* ... */
```

## 🎨 Criterios de Evaluación

| Criterio | Puntos |
|----------|--------|
| CSS externo correctamente vinculado | 1 |
| Estilos de Caja 1 correctos | 2 |
| Estilos de Caja 2 correctos | 2 |
| Estilos de Caja 3 correctos (incluye centrado) | 2 |
| Cálculos correctos en comentarios | 2 |
| Títulos descriptivos antes de cada caja | 0.5 |
| Validación W3C CSS sin errores | 0.5 |
| **TOTAL** | **10 puntos** |

## 📤 Entrega

**Archivos a entregar:**
- `Apellido_Nombre_Ejercicio2.html`
- `estilos.css`

**Formato:** Carpeta comprimida (.zip)

## 💡 Pistas

### Cálculo con `content-box`:
```
Ancho total = width + padding-left + padding-right + border-left + border-right
```

### Cálculo con `border-box`:
```
Ancho total = width (el padding y border están incluidos)
Ancho del contenido = width - (padding + border de ambos lados)
```

### Centrado horizontal:
```css
margin: 0 auto;
```
- `0` = margen vertical (arriba y abajo)
- `auto` = margen horizontal (izquierda y derecha se calculan automáticamente)
- El navegador divide el espacio disponible equitativamente

## 🔍 Verificación con DevTools

1. Abre tu página en el navegador
2. Presiona `F12` para abrir DevTools
3. Selecciona la pestaña **"Elements"** o **"Inspector"**
4. Haz clic en una de las cajas
5. En el panel derecho, busca la sección **"Computed"** o **"Diseño"**
6. Verás un diagrama visual del modelo de caja con todas las medidas

## 🎓 Conceptos Clave a Recordar

### **`box-sizing: content-box` (por defecto)**
- El `width` y `height` se aplican SOLO al contenido
- El padding y border se SUMAN al tamaño total
- Hace que los cálculos sean menos intuitivos

### **`box-sizing: border-box` (recomendado)**
- El `width` y `height` incluyen contenido, padding y border
- El tamaño especificado es el tamaño final real
- Hace que los cálculos sean más predecibles

### **Buena práctica moderna:**
```css
* {
    box-sizing: border-box;
}
```

## ❓ Preguntas de Reflexión

Responde estas preguntas en un comentario al final de tu CSS:

1. ¿Qué diferencia hay entre usar `margin` y `padding` para crear espacio?
2. ¿Por qué `border-box` es más fácil de trabajar que `content-box`?
3. ¿Qué pasa si intentas centrar un elemento sin especificar su `width`?

## 🔗 Referencias

- [MDN: El modelo de caja](https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model)
- [MDN: box-sizing](https://developer.mozilla.org/es/docs/Web/CSS/box-sizing)
- [CSS-Tricks: Box Sizing](https://css-tricks.com/box-sizing/)

---

¡Recuerda: El modelo de caja es fundamental para todo el diseño CSS! 📦
