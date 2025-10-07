# 🎨 Flexbox Frontend Academy: Maquetación con HTML y CSS

¡Bienvenido al repositorio **Flexbox Frontend Academy**! Este proyecto es un recurso educativo diseñado para aprender técnicas de maquetación web modernas utilizando **HTML5** y **CSS3** con un enfoque en **Flexbox** y diseño responsivo. 🚀

---

## 📚 Propósito y alcance

Este repositorio sirve como un tutorial práctico para dominar:

- Implementación de diseños CSS Flexbox con HTML semántico.
- Creación de layouts responsivos usando media queries.
- Aplicación de sistemas de diseño visual consistentes.
- Integración de animaciones CSS y bibliotecas externas (nivel avanzado).

Todos los ejercicios siguen un patrón arquitectónico consistente, permitiendo comparar implementaciones y comprender la progresión del aprendizaje.

---

## 🗂 Estructura del repositorio

El repositorio está organizado por niveles de dificultad:

| Nivel | Directorio | Ejercicios | Enfoque de aprendizaje |
|-------|------------|------------|-----------------------|
| Nivel 1 | `Nivel1/` | 3 | Diseño básico de Flexbox y fundamentos responsivos |
| Nivel 2 | `Nivel2/` | 2 | Refinamiento de componentes y layouts completos |
| Nivel 3 | `Nivel3/` | 1 | Animaciones, iconos externos y pulido final |

Cada ejercicio sigue la misma estructura de archivos:

index.html

css/

└─ style.css

images/

---


---

## 🏗 Patrón de estructura HTML

Todos los ejercicios incluyen estas secciones principales:

- `header` (barra de navegación)
- `main` (contenido principal y artículos)
- `aside` (barra lateral)
- `footer` (pie de página)

---

## 🎨 Sistema de colores

| Color | Código | Uso |
|-------|--------|-----|
| Negro | #000 | Contenedores estructurales |
| Gris oscuro | #565656 | Contenedores secundarios |
| Naranja | #ff4500 | Secciones de navegación |
| Naranja intenso | #e78011 | Encabezado principal |
| Amarillo | #eaea36 | Imagen de encabezado y pie de página |
| Azul | #3b3bbf | Artículos principales |
| Azul claro | #7676e8 | Artículo destacado |
| Rojo | #e71111 | Barra lateral |
| Amarillo brillante | #ffff00 | Artículos barra lateral |
| Verde lima | #eaf302 | Indicador de media queries |

> El verde lima se usa como fondo de depuración para los puntos de interrupción responsivos. 🌿

---

## 📐 Relación de Flexbox

**Barra de navegación (`nav`)**:  
- `.logo`: flex 1  
- `.menu_nav`: flex 6  
- `.rrss`: flex 1  
- Relación total: **1:6:1**

**Contenido principal (`main`)**:  
- `.section_main`: flex 2  
- `aside`: flex 1  
- Relación total: **2:1**

---

## 🖥 Media Queries

- Tableta: 601–768px  
- Móvil: ≤600px  
> Cambia el color de fondo a verde lima para indicar activación de media queries.

---

## ✨ Evolución de características

| Característica | E1 | E2 | E3 | E4 | E5 | E6 |
|----------------|----|----|----|----|----|----|
| Flexbox básico | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Estructura 3 secciones | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Navegación 1:6:1 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Contenido principal 2:1 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Media query tablet | — | ✓ | ✓ | ✓ | ✓ | ✓ |
| Media query móvil | — | — | ✓ | ✓ | ✓ | ✓ |
| Fondo de depuración verde | — | ✓ | ✓ | ✓ | ✓ | ✓ |
| Animaciones CSS | — | — | — | — | — | ✓ |
| Iconos Font Awesome | — | — | — | — | — | ✓ |
| Contenido real e imágenes | — | — | — | — | ✓ | ✓ |

---

## 🛠 Tecnologías utilizadas

- **HTML5**: Estructura semántica (`header`, `nav`, `main`, `aside`, `footer`, `article`)  
- **CSS3**: Flexbox, media queries, animaciones  
- **Animaciones**: Keyframes CSS (nivel avanzado)  
- **Iconos**: Font Awesome (nivel avanzado)  

> No se utilizan frameworks, JavaScript, preprocesadores ni herramientas de compilación. Los ejercicios se abren directamente en el navegador. 🌐

---

## 🚀 Progresión educativa

El repositorio permite un aprendizaje incremental a través de seis ejercicios, con una base consistente que se va enriqueciendo en cada nivel:

1. Nivel 1: Fundamentos de Flexbox y diseño responsivo.  
2. Nivel 2: Refinamiento y layouts más complejos.  
3. Nivel 3: Animaciones CSS y componentes finales pulidos.  

---

## 📌 Referencia rápida de clases CSS

| Componente | Clase CSS | Flexbox/Rol |
|------------|-----------|-------------|
| Contenedor de logotipos | `.logo` | flex 1 |
| Menú de navegación | `.menu_nav` | flex 6 |
| Redes sociales | `.rrss` | flex 1 |
| Sección héroe | `.section_header` | contenedor |
| Contenido principal | `.section_main` | flex 2 |
| Barra lateral | `aside` | flex 1 |
| Artículos principales | `.art1` - `.art4` | flex 1 |
| Artículo destacado | `.art5` | ancho completo |
| Artículos barra lateral | `.art_aside1` - `.art_aside2` | bloque |
| Pie de página | `.footer_content` | bloque |

---

## 📂 Navegación de la documentación

- Patrones arquitectónicos: `Patrones arquitectónicos comunes`  
- Implementación Flexbox: `Sistema de diseño CSS Flexbox`  
- Diseño responsivo: `Estrategia de Diseño Responsivo`  
- Ejercicios: `Nivel 1`, `Nivel 2`, `Nivel 3`  
- Animaciones e iconos: `Ejercicio 6: Animaciones e Iconos`  

---
