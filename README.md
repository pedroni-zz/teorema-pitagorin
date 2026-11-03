# Applet Educativo: Teorema de Pitágoras (Disección de Perigal)

Aplicación interactiva desarrollada en **HTML5, SVG y JavaScript puro** (sin dependencias externas) diseñada para estudiantes de educación secundaria y superior. Su objetivo es demostrar visual e intuitivamente el Teorema de Pitágoras ($a^2 + b^2 = c^2$) mediante la disección geométrica de Perigal.

## 🎯 Características Pedagógicas
- **Manipulación Activa:** Permite arrastrar, rotar y acomodar las 5 piezas geométricas de los catetos ($a^2$ y $b^2$) dentro del cuadrado de la hipotenusa ($c^2$).
- **Rotación de Alta Precisión:** Incluye controles de ajuste fino por grado (`-1°`, `+1°`), rotación rápida (`-15°`, `+15°`) y barra deslizante (`0°` a `360°`).
- **Sistema Poka-Yoke:** Validación estricta que exige al menos un **99.9% de cobertura y precisión** en el acomodo.
  - Mensaje de éxito: *"Pitágoras está orgulloso de ti"*.
  - Mensaje de error: *"Respuesta incorrecta"*.
- **Dinámica en Tiempo Real:** Los deslizadores permiten modificar las longitudes de los catetos $a$ y $b$, recalculando automáticamente el área de la hipotenusa y el tamaño de las piezas.

## 🚀 Uso e Instalación
No requiere instalación ni librerías adicionales. 
1. Clona o descarga este repositorio.
2. Abre el archivo **`index.html`** en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).

---
*Desarrollado como recurso didáctico interactivo.*