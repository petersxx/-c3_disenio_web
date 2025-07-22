# Tarea Extra 1: Fundamentos de HTML

## ¿Qué es HTML y cuál es su función principal en el desarrollo web?

HTML (HyperText Markup Language) es el lenguaje de marcado que se utiliza para estructurar y presentar contenido en la web. No es un lenguaje de programación, sino un lenguaje que permite definir elementos como títulos, párrafos, imágenes, enlaces, tablas, formularios, etc. Su función principal es darle estructura a una página web para que los navegadores puedan interpretarla y mostrarla al usuario.

### Ejemplos de etiquetas básicas:

- `<h1>`: Define un encabezado principal (nivel 1).
- `<p>`: Representa un párrafo de texto.
- `<a>`: Crea un enlace a otra página o recurso.

---

## ¿Cuál es la estructura mínima de un documento HTML válido?

Un documento HTML válido debe contener una estructura básica que permita a los navegadores entender y renderizar correctamente el contenido.

### Ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi primera página</title>
</head>
<body>
  <h1>¡Hola mundo!</h1>
  <p>Este es mi primer documento HTML.</p>
</body>
</html>
```

---

## ¿Qué diferencia hay entre una etiqueta de bloque y una etiqueta en línea (inline)?

- **Etiquetas de bloque**: Ocupan todo el ancho disponible del contenedor. Siempre comienzan en una nueva línea. Sirven para estructurar grandes secciones del contenido.
- **Etiquetas en línea (inline)**: Solo ocupan el espacio necesario según su contenido. No comienzan en una nueva línea y se usan dentro de otras etiquetas para modificar partes específicas del texto.

### Ejemplos:

- **Bloque**: `<div>`, `<p>`
- **En línea**: `<span>`, `<a>`

---

## ¿Qué son los atributos en HTML y para qué se utilizan?

Los atributos proporcionan información adicional sobre los elementos HTML. Se escriben dentro de la etiqueta de apertura y modifican el comportamiento o la apariencia del elemento.

### Ejemplos:

- Usando `href` para enlaces:

```html
<a href="https://www.google.com">Ir a Google</a>
```

- Usando `alt` para imágenes:

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

---

## ¿Qué diferencia hay entre las etiquetas `<div>` y `<span>` y cuándo deberías usar cada una?

- `<div>` es una **etiqueta de bloque** usada para agrupar contenido en secciones o bloques más grandes. Ideal para estructurar el diseño general de la página (por ejemplo: encabezados, pies de página, columnas).
- `<span>` es una **etiqueta en línea**, útil para aplicar estilo o funcionalidad a partes específicas del texto sin interrumpir el flujo del contenido.

### Ejemplo práctico:

```html
<div style="background-color: lightblue; padding: 10px;">
  <h2>Perfil de usuario</h2>
  <p>Nombre: <span style="color: blue;">Pedro Melgarejo</span></p>
</div>
```

En este ejemplo, el `<div>` agrupa toda la sección del perfil, mientras que `<span>` se usa solo para cambiar el color del nombre dentro de un párrafo.

---

**Archivo creado por Pedro Melgarejo — Julio 2025**
