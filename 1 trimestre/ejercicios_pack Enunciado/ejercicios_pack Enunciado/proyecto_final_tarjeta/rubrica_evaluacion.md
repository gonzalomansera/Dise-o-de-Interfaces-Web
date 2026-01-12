# 📊 Rúbrica de Evaluación - Proyecto Final

## Tarjeta de Presentación Personal

**Valor total:** 70% de la calificación del módulo  
**Puntuación máxima:** 70 puntos

---

## 1️⃣ HTML Semántico Correcto (20 puntos)

### Estructura básica (4 puntos)
| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Excelente** | 4 | Documento HTML5 completo con DOCTYPE, charset UTF-8, viewport y title apropiado |
| **Bueno** | 3 | Estructura completa pero falta algún meta tag |
| **Suficiente** | 2 | Estructura básica presente pero incompleta |
| **Insuficiente** | 0-1 | Falta DOCTYPE o elementos esenciales |

### Etiquetas semánticas (12 puntos)
| Elemento | Puntos | Criterios |
|----------|--------|-----------|
| `<header>` | 2 | Presente y usado correctamente con contenido apropiado |
| `<nav>` | 2 | Presente con enlaces funcionales a las secciones |
| `<main>` | 2 | Presente y contiene el contenido principal |
| `<section>` (×3) | 3 | Tres secciones correctamente etiquetadas (sobre-mi, habilidades, contacto) |
| `<footer>` | 2 | Presente con copyright y enlaces |
| `<figure>` | 1 | Usado para la foto de perfil con `<figcaption>` (opcional pero valorado) |

### Formulario HTML5 (4 puntos)
| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Completo** | 4 | Todos los campos presentes (nombre, email, asunto, mensaje, botón) con atributos correctos |
| **Casi completo** | 3 | Falta 1 campo o algunos atributos |
| **Incompleto** | 1-2 | Faltan varios campos o atributos importantes |
| **No funcional** | 0 | Formulario ausente o no funcional |

**Desglose detallado del formulario:**
- ✅ Campos: nombre, email, asunto, mensaje (1 punto)
- ✅ Atributo `required` en todos (1 punto)
- ✅ `type="email"` en email (0.5 puntos)
- ✅ Labels con `for` correctos (1 punto)
- ✅ Placeholders informativos (0.5 puntos)

---

## 2️⃣ CSS Aplicado: Selectores y Modelo de Caja (25 puntos)

### Vinculación y estructura CSS (3 puntos)
| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Correcto** | 3 | Archivo CSS externo correctamente vinculado, organizado con comentarios |
| **Aceptable** | 2 | Vinculado correctamente pero desorganizado |
| **Deficiente** | 1 | CSS inline o en `<style>` (no externo) |
| **Ausente** | 0 | No hay CSS o no está vinculado |

### Selectores CSS (5 puntos)
| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Excelente** | 5 | Usa 5+ tipos diferentes: etiqueta, clase, ID, descendente, pseudo-clase |
| **Bueno** | 4 | Usa 4 tipos diferentes |
| **Suficiente** | 3 | Usa 3 tipos diferentes |
| **Insuficiente** | 0-2 | Usa solo 1-2 tipos de selectores |

**Checklist de selectores:**
- ☐ Selector de etiqueta (ej: `body`, `h1`)
- ☐ Selector de clase (ej: `.habilidad`)
- ☐ Selector de ID (ej: `#sobre-mi`)
- ☐ Selector descendente (ej: `nav a`)
- ☐ Pseudo-clase (ej: `:hover`, `:focus`)

### Modelo de Caja (7 puntos)
| Aspecto | Puntos | Criterios |
|---------|--------|-----------|
| `box-sizing: border-box` | 1 | Aplicado globalmente con `*` |
| Padding en secciones | 2 | Todas las secciones tienen padding apropiado |
| Margin entre elementos | 2 | Espaciado vertical coherente entre secciones |
| Centrado con `margin: auto` | 2 | Al menos el contenedor principal está centrado |

### Tipografía y colores (5 puntos)
| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Excelente** | 5 | Esquema de colores coherente, fuentes legibles, jerarquía visual clara |
| **Bueno** | 4 | Colores y fuentes apropiados, algún detalle menor |
| **Suficiente** | 3 | Básico pero funcional |
| **Insuficiente** | 0-2 | Colores no coherentes, texto ilegible |

**Debe incluir:**
- ✅ Color de fondo del body
- ✅ Color de fondo del header
- ✅ Colores de títulos diferentes al texto normal
- ✅ Fuente sans-serif legible

### Estilos avanzados (5 puntos)
| Aspecto | Puntos | Criterios |
|---------|--------|-----------|
| Foto de perfil circular | 1 | `border-radius: 50%` aplicado |
| Enlaces con `:hover` | 1 | Cambio visual al pasar el ratón |
| Layout ordenado | 2 | Secciones bien distribuidas y alineadas |
| Detalles visuales | 1 | Border-radius, box-shadow u otros detalles |

---

## 3️⃣ Formulario con Validación (15 puntos)

### Validación HTML5 nativa (5 puntos)
| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Completo** | 5 | Todos los campos con `required`, type correcto (email), funcionan nativamente |
| **Casi completo** | 4 | Funciona pero falta algún atributo de validación |
| **Básico** | 2-3 | Validación presente pero incompleta |
| **Ausente** | 0-1 | No hay validación o no funciona |

### Estilos con pseudo-clases (10 puntos)
| Pseudo-clase | Puntos | Criterio |
|--------------|--------|----------|
| `:focus` | 2 | Cambio visual claro cuando el campo está activo |
| `:valid` | 3 | Borde verde o fondo verde claro en campos válidos |
| `:invalid` | 3 | Borde rojo o fondo rojo claro en campos inválidos |
| `:required` o `:optional` | 1 | Diferenciación visual (opcional, pero valorado) |
| Botón con `:hover` | 1 | Cambio de color al pasar el ratón |

**Estilos mínimos requeridos en inputs:**
- ✅ Padding (mínimo 10px)
- ✅ Border definido
- ✅ Border-radius
- ✅ Width: 100% o ancho definido
- ✅ Transiciones suaves (opcional pero valorado)

---

## 4️⃣ Validación W3C (10 puntos)

### Validación HTML (5 puntos)
| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Sin errores** | 5 | Pasa validación W3C HTML sin ningún error |
| **Errores menores** | 3-4 | 1-3 errores o warnings menores |
| **Errores moderados** | 1-2 | 4-10 errores |
| **No válido** | 0 | Más de 10 errores o no validado |

### Validación CSS (5 puntos)
| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Sin errores** | 5 | Pasa validación W3C CSS sin ningún error |
| **Errores menores** | 3-4 | 1-3 errores o warnings menores |
| **Errores moderados** | 1-2 | 4-10 errores |
| **No válido** | 0 | Más de 10 errores o no validado |

**Nota:** Algunos warnings pueden ser aceptables (ej: vendor prefixes, propiedades experimentales).

---

## 📋 Resumen de Puntuación

| Sección | Puntos |
|---------|--------|
| 1. HTML Semántico Correcto | 20 |
| 2. CSS Aplicado (Selectores y Modelo de Caja) | 25 |
| 3. Formulario con Validación | 15 |
| 4. Validación W3C | 10 |
| **TOTAL** | **70 puntos** |

---

## 🎯 Escala de Calificación

| Puntos | Calificación | Descripción |
|--------|--------------|-------------|
| 63-70 | **Sobresaliente** (9-10) | Excelente trabajo, todos los requisitos cumplidos con calidad |
| 56-62 | **Notable** (7-8) | Buen trabajo, cumple la mayoría de requisitos |
| 49-55 | **Bien** (6-7) | Trabajo aceptable, cumple requisitos básicos |
| 35-48 | **Suficiente** (5-6) | Trabajo mínimo, falta pulir varios aspectos |
| 0-34 | **Insuficiente** (<5) | No cumple los requisitos mínimos |

---

## ✅ Requisitos Mínimos para APROBAR (35 puntos)

**Debes conseguir AL MENOS:**
- HTML con estructura semántica básica (10 puntos)
- CSS vinculado con estilos básicos aplicados (12 puntos)
- Formulario presente y funcional (8 puntos)
- Validación HTML y CSS con errores menores aceptables (5 puntos)

---

## 💡 Consejos para Maximizar tu Puntuación

### Para conseguir Sobresaliente (9-10):
✅ Código limpio y organizado con comentarios
✅ Todas las etiquetas semánticas usadas correctamente
✅ Variedad de selectores CSS (5+ tipos)
✅ Formulario con validación visual perfecta
✅ Sin errores en validadores W3C
✅ Detalles visuales cuidados (transiciones, hover effects)
✅ Responsive básico (opcional pero muy valorado)

### Errores que te bajarán la nota:
❌ HTML o CSS no validado
❌ No usar etiquetas semánticas (solo `<div>`)
❌ CSS no vinculado o inline
❌ Formulario sin validación
❌ No aplicar pseudo-clases al formulario
❌ Selectores repetitivos (solo usar uno o dos tipos)
❌ Falta de `box-sizing: border-box`

---

## 📝 Notas Adicionales

### **Plagio:**
El trabajo debe ser individual. Se pueden consultar recursos online, pero el código debe ser escrito por el alumno. Copiar código completo de otros compañeros o de Internet resultará en una calificación de 0.

### **Entrega fuera de plazo:**
- 1 día de retraso: -10% de la nota
- 2 días de retraso: -20% de la nota
- Más de 2 días: No se acepta sin justificación

### **Presentación oral (no puntuable pero obligatoria):**
Cada alumno debe explicar brevemente:
1. Qué ha creado (30 segundos)
2. Un desafío que tuvo y cómo lo resolvió (1 minuto)
3. Una parte del código de la que está orgulloso (1 minuto)

---

## 📧 Dudas

Si tienes dudas sobre la rúbrica o la evaluación, pregunta al profesor **antes** de la fecha de entrega.

---

**¡Mucha suerte con tu proyecto!** 🚀
