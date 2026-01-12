# 📚 Práctica Unidad 1. Planificación de una interfaz gráfica - Sitio Web de Librería

## 🎯 Objetivo
Completar el diseño visual y prototipo interactivo del sitio web de tu librería Versión desktop, en Figma, aplicando el Design System que ya has creado.

---

## 📋 Contexto del Proyecto

**Proyecto:** Diseña el sitio web para una librería moderna con personalidad que ofrezca artículos de la temática que tu decidas; por ejemplo:
Ciencia y Tecnología,
Ficción y Fantasía,
Cómics y Novela Gráfica,
Deportes y Aventura,
Futurismo y Ciencia Ficción,
Literatura Juvenil y Young Adult,
Misterio y Thriller,
Viajes y Culturas del Mundo,
Arte, Diseño y Creatividad,
Desarrollo Personal y Psicología,
Historia Alternativa y Ucronías,
Ecología y Naturaleza,
Filosofía y Pensamiento Crítico,
Literatura LGBT+ y Diversidad,
Emprendimiento e Innovación ...

**Lo que ya tienes:**
- ✅ Design System en Figma (colores, fuentes, grids, iconos, botones)

**Lo que vas a crear en esta práctica:**
1. Design System (ya hecho)
2. Wireframes (estructura)
3. Mockups (diseño visual)
4. Prototipo interactivo

---

## 📦 Entregables

### 1️⃣ DESIGN SYSTEM (ya hecho)

**Herramienta:** Figma 

**Contenido:**
Desing System completo que incluya:
- Paleta de colores (primarios, secundarios, neutrales). Crea estilos de color en Figma
- Tipografías (familias, tamaños, pesos). Crea estilos de texto en Figma
- Sistema de grid (desktop, tablet, smartphone). Crea estilos de layout en Figma.
- Botones ( default, hover, active, disabled) con variantes (state,iconos)
- Iconos (set de iconos usados en la web, sociales, navegación..) con variantes (tamaños, colores,tipos)

**Tips:**
- Asegúrate de que tu Design System esté bien organizado en Figma
---

### 2️⃣ WIREFRAMES - Estructura

**Fidelidad:** Media (escala de grises)

Crea **2 wireframes** en Figma:

#### A) PÁGINA PRINCIPAL / LANDING PAGE

**Estructura de arriba a abajo:**

1. **CABECERA (Header)**
   - Izquierda: Nombre de la librería
   - Derecha: Logo de la librería

2. **BARRA DE NAVEGACIÓN (Nav)**
   - Izquierda: Buscador
   - Derecha: Menú → "Tu librería" | "Compra On-line" | "Contacto"

3. **ÁREA DE CONTENIDO (Main)**
   Dividida en 4 secciones:
   
   **Sección 1: Tu librería**
   - Hero section con presentación de la marca
   - Texto de bienvenida
   - Imagen destacada o ilustración
   
   **Sección 2: Libros y Artículos**
   - Descripción del tipo de libros que vendes
   - Grid de 3-4 libros destacados
   - Cada libro: imagen + título o descripción + precio
   
   **Sección 4: Buscador de Tiendas**
   - Campo de búsqueda por ubicación
   - Mapa placeholder o ilustración
   - Lista de tiendas físicas

4. **PIE DE PÁGINA (Footer)**
   - Redes sociales (iconos)
   - Enlaces: Política de datos | Cookies
   - Copyright con tu nombre

---

#### B) PÁGINA COMPRAR ONLINE

**Estructura:**

1. **CABECERA** (igual que página principal)

2. **BARRA DE NAVEGACIÓN** (igual que página principal)

3. **ÁREA DE CONTENIDO** - Layout de 2 columnas:

   **COLUMNA IZQUIERDA (Sidebar - 25% ancho)**
   - Título: "Categorías" o "Filtrar por"
   - Checkbox/Radio buttons:
     - ☐ Todos los productos
     - ☐ Libros
     - ☐ Tazas
     - ☐ Bolsas
     - ☐ Otros
   
   **COLUMNA DERECHA (Contenido principal - 75% ancho)**
   - Grid de productos (3-4 columnas)
   - Cada tarjeta de producto contiene:
     - Imagen del producto (rectángulo con X)
     - Nombre del producto (línea)
     - Descripción breve (2-3 líneas)
     - Precio (texto destacado)
     - Botón "Añadir al carrito" o "Comprar"

4. **PIE DE PÁGINA** (igual que página principal)

**Elementos en wireframe:**
   - ¿Qué NO incluye un Wireframe?
      ❌ Colores finales
      ❌ Imágenes reales
      ❌ Tipografías específicas
      ❌ Iconografía detallada
      ❌ Textos definitivos (usa líneas para simular párrafos)
   - ¿Qué SÍ incluye un Wireframe?
      ✅ Estructura de la página (header, main, aside, footer)
      ✅ Jerarquía de contenidos (títulos, subtítulos, párrafos)
      ✅ Ubicación de elementos (botones, formularios, imágenes)
      ✅ Tamaño relativo de los elementos
      ✅ Zonas interactivas (enlaces, botones, campos)
      ✅ Sistema de navegación (menús, enlaces...)
      ✅ Grid y alineaciones básicas
      ✅ Todo en escala de grises (#000000, #666666, #CCCCCC, #FFFFFF)

---

### 3️⃣ MOCKUPS - Diseño Visual.

**Fidelidad:** Alta (diseño final)

**Proceso:**
1. Duplica tus wireframes
2. Aplica tu Design System completo

#### A) MOCKUP PÁGINA PRINCIPAL

Transforma tu wireframe aplicando:

**Colores:**
- Aplica tu paleta de colores del Design System
- Define colores para: fondo, textos, botones, secciones

**Tipografías:**
- Usa las fuentes definidas en tu Design System
- H1, H2, H3 para títulos
- Body text para párrafos
- Tamaños y pesos consistentes

**Imágenes:**
- Sustituye placeholders por imágenes reales o de calidad:
  - Unsplash (fotos)
  - Storyset (ilustraciones)
  - Imágenes de libros/productos reales
- Optimiza el tamaño y calidad

**Iconos:**
- Usa los iconos de tu Design System
- Aplícalos en navegación, búsqueda, redes sociales

**Botones:**
- Usa los componentes de botones del Design System

**Espaciado:**
- Aplica el sistema de espaciado (múltiplos de 8px)
- Usa Auto Layout para elementos repetitivos

---

#### B) MOCKUP PÁGINA COMPRAR ONLINE

Aplica el mismo proceso al wireframe de compra online:

**Diseño de Tarjeta de Producto:**
- Crea un componente reutilizable
- Incluye:
  - Imagen del producto (aspecto ratio consistente)
  - Badge si está en oferta/nuevo
  - Nombre del producto (tipografía H4)
  - Descripción (body text pequeño)
  - Precio (destacado, bold)
  - Botón de acción
  - Sombra sutil (del Design System)

**Filtros laterales:**
- Estilo consistente con el resto
- Estados: seleccionado/no seleccionado
- Iconos si es necesario

**Hover States:**
- Define cómo se ven las tarjetas en hover (opcional)
- Efecto en botones

---

### 4️⃣ PROTOTIPO INTERACTIVO

**Herramienta:** Modo Prototype de Figma

**Interacciones a crear:**

#### Navegación Principal:
1. **Desde Página Principal:**
   - Click en "Compra On-line" → ir a Comprar Online
   - Click en "Tu librería" → volver a Página Principal.
   - Scroll down en la página → navegación fluida entre secciones.
   - Scroll horizontal en el grid de artículos → ver más artículos (si aplica).

2. **Desde Comprar Online:**
   - Opiones del menú, igual que en Página Principal:
   - Click en categorías del sidebar → (opcional) cambiar vista de productos
   - Click en tarjeta producto → (opcional) vista detalle del producto

3. **Botones interactivos:**
   - Hover en botones → cambio de estado
   - Click en "Añadir al carrito" → feedback visual

**Tips:**
- Asegúrate de que la navegación del menú funcione.
- Añade lo que puedas de todo lo sugerido, pero prioriza lo esencial.

---

## ✅ Checklist de Entrega

Antes de entregar, verifica:

### Wireframes:
- [ ] 2 páginas completas (Home + Comprar Online)
- [ ] Estructura clara en escala de grises
- [ ] Todos los elementos mencionados están presentes
- [ ] Se respeta la jerarquía visual
- [ ] Usa el grid del Design System

### Mockups:
- [ ] 2 páginas con diseño visual completo
- [ ] Aplica correctamente el Design System
- [ ] Colores, tipografías e iconos consistentes
- [ ] Imágenes de calidad (no placeholders)
- [ ] Componentes reutilizables creados
- [ ] Espaciados consistentes
- [ ] Se ve profesional

### Prototipo:
- [ ] Navegación principal funciona
- [ ] Menú conecta con secciones/páginas
- [ ] Transiciones suaves

### General:
- [ ] Archivo Figma bien organizado (páginas con nombres claros)
- [ ] Capas con nombres descriptivos
- [ ] Design System está vinculado
- [ ] Estilos creados y usados.
---

## 🎨 Recursos Recomendados

**Imágenes:**
- [Unsplash](https://unsplash.com) - Fotos de calidad
- [Pexels](https://pexels.com) - Fotos gratis
- Para libros: buscar portadas reales o usar Amazon


**Ilustraciones:**
- [Storyset](https://storyset.com) - Ilustraciones personalizables
- [unDraw](https://undraw.co) - Ilustraciones SVG

**Iconos:**
- Plugin Iconify en Figma
- [Font Awesome](https://fontawesome.com)
- [Heroicons](https://heroicons.com)
- Recomendados durante la creación del Design System.

**Inspiración:**
- [Dribbble](https://dribbble.com) - busca "bookstore website"
- [Behance](https://behance.net) - proyectos de librerías
- Librerías reales: La Central, Casa del Libro, Strand Books

---

## 📊 Criterios de Evaluación

| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Wireframes** | 20% | Estructura correcta, jerarquía, todos los elementos presentes |
| **Mockups - Diseño Visual y Design System** | 40% | Aplicación del Design System, coherencia, calidad estética |
| **Mockups - Componentes** | 10% | Componentes reutilizables, organización |
| **Prototipo** | 20% | Navegación funcional, interacciones, fluidez, scroll, modals ... |
| **Presentación General** | 10% | Organización del archivo, naming, profesionalidad, trabajo completo |


---

## 💡 Consejos Finales

1. **Trabaja de forma iterativa:** No intentes hacer todo perfecto desde el principio
2. **Usa componentes:** Crea componentes para elementos que se repiten (botones, tarjetas de producto, etc.)
3. **Pide feedback:** Muestra tu trabajo a compañeros antes de entregar
4. **Testea tu prototipo:** Navega por él como si fueras un usuario real
5. **Mantén la consistencia:** Usa siempre los mismos espaciados, colores y tipografías de tu Design System
6. **Documenta decisiones:** Si tomas decisiones de diseño importantes, anótalas

---

## 📤 Formato de Entrega

**Entrega:**
- Explorar la opción de compartir en Figma para ver cuantas páginas permite compartir el plan gratuito por proyecto o draft.
---
