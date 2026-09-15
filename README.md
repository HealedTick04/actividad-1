# 📚 Actividad 1: HTML, CSS, JavaScript y Bootstrap

Repositorio de prácticas introductorias de **desarrollo web**, realizadas como parte de la actividad de Programación Web. El proyecto contiene diferentes ejercicios para comprender la estructura de una página HTML, el uso de estilos CSS, los enlaces, las imágenes, las tablas y la organización semántica del contenido.

🌐 **Sitio publicado con GitHub Pages:**
https://healedtick04.github.io/actividad-1/

---

## 🎯 Objetivo del proyecto

El objetivo principal es desarrollar una colección de páginas web sencillas que permitan practicar los fundamentos del desarrollo frontend:

* Crear documentos HTML desde cero.
* Utilizar etiquetas de títulos, párrafos y texto.
* Agregar enlaces internos y externos.
* Insertar imágenes en una página web.
* Aplicar estilos CSS internos y externos.
* Utilizar etiquetas semánticas de HTML5.
* Crear listas ordenadas y desordenadas.
* Construir tablas para representar información.
* Organizar diferentes ejercicios mediante un menú principal.
* Publicar un sitio web estático utilizando GitHub Pages.

---

## 🛠️ Tecnologías utilizadas

| Tecnología       | Uso                                                         |
| ---------------- | ----------------------------------------------------------- |
| **HTML5**        | Estructura y contenido de las páginas web.                  |
| **CSS3**         | Diseño, colores, estilos y presentación visual.             |
| **JavaScript**   | Tecnología contemplada para prácticas interactivas futuras. |
| **Bootstrap**    | Framework contemplado para mejorar el diseño responsive.    |
| **Git**          | Control de versiones del proyecto.                          |
| **GitHub**       | Almacenamiento y publicación del repositorio.               |
| **GitHub Pages** | Hospedaje gratuito del sitio web estático.                  |

---

## 📁 Organización del proyecto

El archivo `index.html` se encuentra en la raíz del proyecto y funciona como menú principal para acceder a las diferentes prácticas.

Una estructura aproximada del proyecto es:

```text
actividad-1/
│
├── index.html
├── practica 1.html
├── practica 2.html
├── practica 3.html
├── practica 4.html
├── practica 5.html
├── practica 6.html
├── practica 7.html
├── practica 8.html
├── practica 11.html
├── practica 12.html
│
├── img/
│   ├── logo.png
│   └── FjRrc9TWAAAO9yj.jpg
│
└── css/
    └── practica 8.css
```

> La estructura puede variar dependiendo de la ubicación final de las imágenes, hojas de estilos y demás archivos del proyecto.

---

## 🧭 Menú principal

El archivo `index.html` permite acceder a las prácticas mediante enlaces relativos. Esto facilita la navegación entre las páginas y permite que los enlaces funcionen correctamente tanto de manera local como en GitHub Pages.

Ejemplo de enlace utilizado:

```html
<a href="./practica%201.html">
    Práctica 1
</a>
```

El código `%20` representa un espacio en una dirección URL.

---

# 📝 Descripción de las prácticas

## 🔹 Práctica 1: Párrafos y contenido básico

Esta práctica presenta una página HTML sencilla que contiene un párrafo de texto.

### Conceptos practicados

* Estructura básica de HTML.
* Declaración `<!DOCTYPE html>`.
* Etiquetas `<html>`, `<head>` y `<body>`.
* Uso de la etiqueta `<p>` para crear párrafos.
* Configuración del idioma y la codificación de caracteres.

### Ejemplo de contenido

```html
<p>Poder Peruano, Ah la corrupción</p>
```

---

## 🔹 Práctica 2: Jerarquía de títulos

La segunda práctica muestra los seis niveles de encabezados disponibles en HTML, desde `<h1>` hasta `<h6>`.

### Conceptos practicados

* Títulos principales y secundarios.
* Jerarquía semántica del contenido.
* Uso de párrafos.
* Organización de secciones dentro de una página.

### Etiquetas utilizadas

```html
<h1>Título principal</h1>
<h2>Secciones principales</h2>
<h3>Subsecciones</h3>
<h4>Sub-subsecciones</h4>
<h5>Contenido anidado</h5>
<h6>Encabezado de menor nivel</h6>
```

Esta práctica permite comprender cómo estructurar correctamente el contenido de una página.

---

## 🔹 Práctica 3: Enlaces HTML y estilos internos

Esta práctica incorpora enlaces hacia páginas externas y enlaces internos entre ejercicios.

### Conceptos practicados

* Uso de la etiqueta `<a>`.
* Enlaces externos.
* Enlaces internos.
* Atributo `target`.
* Aplicación de CSS dentro de la etiqueta `<style>`.
* Cambio del color de fondo de la página.

### Ejemplos de enlaces

```html
<a href="https://www.google.com" target="_blank">
    Google
</a>
```

```html
<a href="practica%201.html">
    Regresar a la práctica 1
</a>
```

El atributo `target="_blank"` abre el enlace en una nueva pestaña, mientras que `target="_self"` lo abre en la pestaña actual.

---

## 🔹 Práctica 4: Imágenes y atributos HTML

La cuarta práctica muestra cómo insertar una imagen dentro de una página web.

### Conceptos practicados

* Uso de la etiqueta `<img>`.
* Rutas relativas hacia imágenes.
* Atributo `src`.
* Atributo `alt`.
* Control del tamaño de una imagen mediante `width` y `height`.
* Aplicación de estilos directamente en el atributo `style`.

### Ejemplo

```html
<img
    src="img/FjRrc9TWAAAO9yj.jpg"
    alt="Imagen de Perú"
    width="500"
    height="300"
>
```

El atributo `alt` proporciona un texto alternativo que mejora la accesibilidad y permite describir la imagen cuando no puede cargarse.

---

## 🔹 Práctica 5: Blog personal

Esta práctica simula la estructura básica de un blog personal. Incluye títulos, párrafos, texto resaltado, texto en cursiva, saltos de línea, imágenes y un enlace externo.

### Conceptos practicados

* Creación de contenido textual.
* Uso de `<strong>` para destacar texto importante.
* Uso de `<em>` para dar énfasis.
* Uso de `<br>` para insertar saltos de línea.
* Inserción de imágenes.
* Enlaces hacia GitHub.
* Organización de contenido mediante párrafos.

### Etiquetas destacadas

```html
<strong>Texto importante</strong>
```

```html
<em>Texto enfatizado</em>
```

```html
<br>
```

Esta práctica combina varios elementos básicos de HTML en una sola página.

---

## 🔹 Práctica 6: Estructura semántica de una página

La sexta práctica utiliza etiquetas semánticas de HTML5 para dividir una página en diferentes partes.

### Secciones utilizadas

* `<header>`: encabezado de la página.
* `<section>`: contenido principal de una sección.
* `<footer>`: pie de página.

### Ejemplo de estructura

```html
<header>
    <h1>My Web</h1>
</header>

<section>
    <p>Contenido principal.</p>
</section>

<footer>
    <p>© 2023 My Web. All rights reserved.</p>
</footer>
```

El uso de etiquetas semánticas mejora la organización del documento, la accesibilidad y la comprensión de la estructura de la página.

---

## 🔹 Práctica 7: Listas de ingredientes e instrucciones

Esta práctica presenta una receta de tacos al pastor utilizando listas HTML.

### Conceptos practicados

* Listas desordenadas con `<ul>`.
* Listas ordenadas con `<ol>`.
* Elementos de lista con `<li>`.
* Listas anidadas.
* Organización de información mediante pasos e ingredientes.

### Lista desordenada

Se utiliza para mostrar los ingredientes:

```html
<ul>
    <li>Carne de cerdo</li>
    <li>Achiote</li>
    <li>Piña</li>
    <li>Tortillas de maíz</li>
</ul>
```

### Lista ordenada

Se utiliza para mostrar las instrucciones de preparación:

```html
<ol>
    <li>Preparar y marinar la carne.</li>
    <li>Asar la carne.</li>
    <li>Cortar la piña.</li>
    <li>Calentar las tortillas.</li>
    <li>Servir los tacos.</li>
</ol>
```

---

## 🔹 Práctica 8: Tabla de horario y CSS externo

La octava práctica representa un horario de clases mediante una tabla HTML y una hoja de estilos CSS externa.

### Conceptos practicados

* Creación de tablas con `<table>`.
* Encabezados de tabla con `<thead>`.
* Cuerpo de tabla con `<tbody>`.
* Filas con `<tr>`.
* Celdas de encabezado con `<th>`.
* Celdas normales con `<td>`.
* Enlace de una hoja de estilos externa.
* Organización de información en filas y columnas.

### Ejemplo de enlace CSS

```html
<link rel="stylesheet" href="css/practica%208.css">
```

### Estructura de la tabla

La tabla contiene:

* Horarios.
* Días de la semana.
* Materias de Ingeniería de Software.
* Diferentes bloques de clases.

El uso de CSS externo permite separar la estructura HTML del diseño visual, facilitando el mantenimiento del proyecto.

---

# 🚀 Publicación con GitHub Pages

El proyecto fue publicado mediante **GitHub Pages**, utilizando:

* Repositorio público: `actividad-1`
* Rama de publicación: `main`
* Carpeta de publicación: `/`
* Archivo principal: `index.html`

Esto permite acceder al proyecto desde cualquier navegador mediante la siguiente dirección:

🌐 https://healedtick04.github.io/actividad-1/

---

## 👨‍💻 Autor

**HealedTick04**

Proyecto académico desarrollado para practicar los fundamentos de HTML, CSS, JavaScript y publicación web con GitHub Pages.
