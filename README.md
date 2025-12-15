# 🍋 El clásico Lemon Pie - Ejercicio de Maquetado HTML

## 📋 Objetivo

Una de las principales tareas de un desarrollador Front End es estructurar interfaces a partir de un wireframe o una imagen. El desafío será reconocer las diferentes etiquetas que podrían conformar el maquetado y comenzar a estructurar un archivo hasta obtener un resultado visual similar a la referencia.

¡Buena suerte! 😎👍✨

## 🎯 Desafío

Utilizando el figma de referencia proporcionado, tu tarea será:

1. **Reconocer** cuáles podrían ser los diferentes elementos o etiquetas que corresponden a ese resultado visual.
2. **Trasladar** aquello que ideaste utilizando etiquetas HTML.

> **Importante:** El proceso de reconocer las diferentes etiquetas o elementos puede ser por fuera del código. Es decir, puedes tomar nota en papel, escribir por encima de la imagen si la imprimes, o simplemente utilizar algún software para poder escribir o dibujar sobre la imagen.

## 🔧 Configuración del Repositorio

Antes de comenzar a trabajar, necesitas obtener una copia del repositorio en tu cuenta de GitHub y luego clonarlo en tu computadora.

### Paso 1: Hacer Fork del Repositorio

1. Ve al repositorio del ejercicio: [Ejercitacion-Maquetado-SImple](https://github.com/FabioDrizZt/Ejercitacion-Maquetado-SImple/fork)
2. Haz clic en el botón **"Fork"** que se encuentra en la esquina superior derecha de la página
3. Selecciona tu cuenta de GitHub como destino del fork
4. Espera a que GitHub cree la copia del repositorio en tu cuenta

> **¿Qué es un Fork?** Un fork es una copia del repositorio original en tu propia cuenta de GitHub. Esto te permite trabajar en tu propia versión sin afectar el repositorio original.

### Paso 2: Clonar el Repositorio

Una vez que tengas el fork en tu cuenta, clónalo en tu computadora:

1. Ve a tu repositorio forkeado (debería estar en `https://github.com/TU-USUARIO/Ejercitacion-Maquetado-SImple`)
2. Haz clic en el botón verde **"Code"** (Código)
3. Copia la URL que aparece (puede ser HTTPS o SSH)
4. Abre tu terminal o Git Bash en la ubicación donde quieres guardar el proyecto
5. Ejecuta el siguiente comando (reemplaza `TU-USUARIO` con tu nombre de usuario de GitHub):

```bash
git clone https://github.com/TU-USUARIO/Ejercitacion-Maquetado-SImple.git
```

6. Navega a la carpeta del proyecto:

```bash
cd Ejercitacion-Maquetado-SImple
```

### 💡 Tips para Git (Primera vez)

Si es tu primera vez usando Git y GitHub:

- **Git:** Es un sistema de control de versiones que te permite guardar el historial de cambios en tu código
- **GitHub:** Es una plataforma web que aloja repositorios Git
- **Fork:** Crear una copia de un repositorio en tu cuenta
- **Clone:** Descargar una copia del repositorio a tu computadora local
- **Terminal/Git Bash:** Herramienta de línea de comandos donde ejecutas los comandos de Git

> **Nota:** Si no tienes Git instalado, puedes descargarlo desde [git-scm.com](https://git-scm.com/). También puedes usar GitHub Desktop como alternativa gráfica.

## 🎨 Diseño de Referencia en Figma

Para este ejercicio, debes trabajar con el diseño de referencia disponible en Figma. **De aquí debes copiar todo el contenido textual** que irá dentro de las etiquetas HTML.

🔗 **Enlace al diseño:** [Ver diseño en Figma](https://www.figma.com/design/hJDopoGCaEEcIO3pNuEhXQ/Introducci%C3%B3n-a-HTML?node-id=0-1&p=f&t=o8jMPzehNMRJ5RTq-0)

### 💻 Tips para usar Figma (Primera vez)

Si es tu primera vez usando Figma, aquí tienes algunos consejos útiles:

1. **Acceso al diseño:**

   - Haz clic en el enlace de arriba para abrir el diseño
   - No necesitas crear una cuenta para ver el diseño (aunque puedes hacerlo si quieres)
   - El diseño se abrirá directamente en tu navegador

2. **Navegación básica:**

   - **Zoom:** Usa la rueda del mouse o `Ctrl +` / `Ctrl -` (Windows)
   - **Mover el canvas:** Mantén presionado el espacio y arrastra, o usa las barras de desplazamiento
   - **Seleccionar elementos:** Haz clic sobre cualquier texto o elemento para seleccionarlo

3. **Copiar texto del diseño:**

   - Haz clic sobre cualquier texto que quieras copiar
   - En el panel derecho, verás las propiedades del texto
   - Puedes seleccionar el texto directamente haciendo doble clic o arrastrando sobre él
   - Usa `Ctrl + C` (Windows) para copiar
   - Pega el texto en tu archivo HTML con `Ctrl + V`

4. **Ver detalles del diseño:**

   - Usa el panel izquierdo para navegar entre las diferentes capas (layers)
   - El panel derecho muestra las propiedades de los elementos seleccionados
   - Puedes ver información sobre tipografías, tamaños, colores, etc.

5. **Herramientas útiles:**

   - **Hand tool (Mano):** Presiona `H` para moverte por el canvas fácilmente
   - **Frame tool (Marco):** Presiona `F` si necesitas crear marcos (no necesario para este ejercicio)
   - **Text tool (Texto):** Presiona `T` para crear texto (no necesario, solo estás copiando)

6. **Consejos importantes:**
   - ⚠️ **Solo copia el texto**, no necesitas replicar los estilos visuales (colores, fuentes, tamaños)
   - 📋 Copia exactamente el texto tal como aparece en el diseño
   - 🔍 Acércate (zoom in) si necesitas ver mejor algún detalle
   - 📝 Puedes tener Figma abierto en una pestaña y tu editor de código en otra para trabajar más cómodamente

> **Nota:** En este ejercicio solo necesitas copiar el contenido textual. Los estilos visuales (CSS) los verás en clases posteriores.

## 📁 Estructura del Proyecto

Una vez que hayas clonado el repositorio, deberías tener la siguiente estructura:

```
Ejercitacion-Maquetado-SImple/
│
├── .vscode/
├── .prettierrc.js
├── README.md
└── index.html (debes crear este archivo)
```

> **Nota:** El archivo `index.html` no viene incluido en el repositorio. Deberás crearlo siguiendo los pasos del ejercicio.

## 🚀 Pasos para Completar el Ejercicio

### Paso 1: Crear el archivo HTML base

1. Crea un nuevo archivo llamado `index.html` en la raíz de tu proyecto.
2. Establece la estructura básica de un documento HTML5:
   - `<!DOCTYPE html>`
   - Etiqueta `<html>` con el atributo `lang="es-AR"`
   - Sección `<head>` con:
     - Meta charset UTF-8
     - Meta viewport para responsive design
     - Título de la página: "El clásico Lemon Pie"
   - Sección `<body>`

### Paso 2: Analizar el diseño en Figma

Antes de escribir código, abre el diseño en Figma y analiza la estructura visual. Identifica:

- **Encabezado (Header):** ¿Qué elementos contiene? (Logo, línea separadora, título principal)
- **Contenido principal (Main):** ¿Qué secciones tiene? (Ingredientes, Instrucciones)
- **Pie de página (Footer):** ¿Qué información contiene?

### Paso 3: Estructurar el contenido

#### 3.1 Encabezado (`<header>`)

- Un párrafo con el texto "Logo"
- Una línea horizontal (`<hr>`)
- Un título principal (`<h1>`) centrado: "El clásico Lemon Pie"
- Un párrafo descriptivo sobre el lemon pie

#### 3.2 Contenido principal (`<main>`)

**Sección de Ingredientes (`<section id="ingredients">`):**

- Tres artículos (`<article>`) para:
  - Ingredientes para la masa
  - Ingredientes para la crema
  - Ingredientes para el merengue
- Cada artículo debe tener:
  - Un subtítulo (`<h2>`)
  - Un párrafo (`<p>`) con los ingredientes

**Sección de Instrucciones (`<section id="instrucciones">`):**

- Un subtítulo (`<h2>`) "Instrucciones"
- Varios párrafos (`<p>`) con cada paso de la receta

#### 3.3 Pie de página (`<footer>`)

- Una línea horizontal (`<hr>`)
- Un párrafo centrado con el texto "Todos los derechos reservados."

### Paso 4: Etiquetas HTML a utilizar

Asegúrate de utilizar las siguientes etiquetas semánticas:

- `<header>` - Para el encabezado
- `<main>` - Para el contenido principal
- `<section>` - Para agrupar contenido relacionado
- `<article>` - Para cada grupo de ingredientes
- `<footer>` - Para el pie de página
- `<h1>`, `<h2>` - Para títulos y subtítulos
- `<p>` - Para párrafos
- `<hr>` - Para líneas horizontales

### Paso 5: Atributos importantes

- `lang="es-AR"` en la etiqueta `<html>`
- `id="ingredients"` en la sección de ingredientes
- `id="instrucciones"` en la sección de instrucciones
- `align="center"` en los elementos que necesiten estar centrados

## ✅ Checklist de Verificación

Antes de considerar tu ejercicio completo, verifica que:

- [ ] El archivo HTML tiene la estructura básica correcta
- [ ] Utilizas etiquetas semánticas (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- [ ] El título principal está centrado
- [ ] Hay una línea horizontal después del logo y antes del footer
- [ ] Los ingredientes están organizados en tres artículos separados
- [ ] Las instrucciones están en párrafos separados
- [ ] El footer tiene el texto centrado
- [ ] El documento tiene el atributo `lang="es-AR"`
- [ ] El título de la página es "El clásico Lemon Pie"

## 💡 Consejos

1. **Trabaja con Figma abierto:** Mantén el diseño de Figma abierto en una pestaña mientras escribes tu código para copiar el contenido textual fácilmente
2. **Planifica antes de codificar:** Dibuja o anota la estructura antes de escribir el HTML
3. **Copia el texto exacto:** Asegúrate de copiar el texto tal como aparece en Figma, respetando mayúsculas, minúsculas y puntuación
4. **Usa indentación:** Mantén tu código organizado con indentación consistente
5. **Comentarios útiles:** Usa comentarios HTML (`<!-- -->`) para marcar las secciones principales
6. **Valida tu código:** Abre el archivo en un navegador para verificar que se vea correctamente
7. **Revisa la semántica:** Asegúrate de usar las etiquetas correctas para cada tipo de contenido

## 📚 Recursos Adicionales

- [MDN Web Docs - HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [Etiquetas semánticas de HTML5 - LenguajeHTML.com](https://lenguajehtml.com/html/semantica/que-son/) - Guía completa sobre las etiquetas semánticas de HTML5 y su importancia
- [Encabezados y secciones - web.dev](https://web.dev/learn/html/headings-and-sections?hl=es-419) - Aprende cómo organizar tus páginas con elementos semánticos de sección y encabezados

---

**¡Éxito con tu ejercicio!** 🎉
