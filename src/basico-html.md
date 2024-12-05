# Basico HTML

En este capítulo mostraremos algunos ejemplos básicos HTML.

No te preocupes si usamos etiquetas que todavía no has aprendido.

---

## Documentos HTML

Todos los documentos HTML deben comenzar con una declaración tipo de documento: `<!DOCTYPE html>`.  
El documento HTML en sí comienza con `<html>` y termina con `</html>`  
La parte visible del documento HTML está entre `<body>` y `</body>`.  

**Ejemplo**

```html
<!DOCTYPE html>
<html>
<body>

<h1>Mi primer encabezado</h1>
<p>Mi primer párrafo.</p>

</body>
</html>
```
<button style="padding: 15px; background-color: #05a86e; border: none; border-radius: 5px; cursor: pointer;">
    <a href="https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic_document" style="color: white; text-decoration: none;" target="_blank">Prueba tú mismo</a>
</button>

--- 

## La declaración <!DOCTYPE>

La declaración `<!DOCTYPE>` representa el tipo de documento y ayuda a los navegadores a mostrar las páginas web correctamente.  
Sólo debe aparecer una vez, en la parte superior de la página (antes de cualquier etiqueta HTML).  
La declaración `<!DOCTYPE>` no es *case sensitive*.  
La declaración `<!DOCTYPE>` para HTML5 es:  

```html
<!DOCTYPE html>
```

---

## Encabezados HTML

Los encabezados HTML se definen con las etiquetas `<h1>` a `<h6>`.  
`<h1>` define el encabezado más importante. `<h6>` define el encabezado menos importante:

**Ejemplo**

```html
<h1>Este es encabezado 1</h1>
<h2>Este es encabezado 2</h2>
<h3>Este es encabezado 3</h3>
```

<button style="padding: 15px; background-color: #05a86e; border: none; border-radius: 5px; cursor: pointer;">
    <a href="https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic_headings" style="color: white; text-decoration: none;" target="_blank">Prueba tú mismo</a>
</button>

--- 

## Párrafos HTML

Los párrafos HTML se definen con la etiqueta `<p>`:

**Ejemplo**
```html
<p>Este es un párrafo.</p>
<p>Este es otro párrafo.</p>
```
<button style="padding: 15px; background-color: #05a86e; border: none; border-radius: 5px; cursor: pointer;">
    <a href="https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic_paragraphs" style="color: white; text-decoration: none;" target="_blank">Prueba tú mismo</a>
</button>

--- 

## Enlaces HTML

Los enlaces HTML se definen con la etiqueta `<a>`:

**Ejemplo**
```html
<a href="https://www.w3schools.com">Este es un enlace</a>
```
<button style="padding: 15px; background-color: #05a86e; border: none; border-radius: 5px; cursor: pointer;">
    <a href="https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic_link" style="color: white; text-decoration: none;" target="_blank">Prueba tú mismo</a>
</button>

El destino del enlace se especifica en el atributo `href`:

Los atributos se utilizan para proporcionar información adicional sobre los elementos HTML.

Aprenderás más sobre atributos en capítulos posteriores.

---

## Imágenes HTML

Las imágenes HTML se definen con la etiqueta `<img>`.

El archivo de origen (src), el texto alternativo (alt), el ancho y la altura se proporcionan como atributos:

**Ejemplo**
```html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```
<button style="padding: 15px; background-color: #05a86e; border: none; border-radius: 5px; cursor: pointer;">
    <a href="https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic_img" style="color: white; text-decoration: none;" target="_blank">Prueba tú mismo</a>
</button>

--- 

## ¿Cómo ver el código fuente HTML?

¿Alguna vez has visto una página web y te has preguntado "Oye, ¿cómo lo hicieron?"

### Ver código fuente HTML:

Presiona las teclas `CTRL` + `U` en una página HTML o haz clic derecho en la página y seleccione "Ver código fuente de la página". Se abrirá una nueva pestaña que contiene el código fuente HTML de la página.

### Inspeccionar un elemento HTML:

Haz clic derecho en un elemento (o en un área en blanco) y elige "Inspeccionar" para ver de qué están compuestos los elementos (verás tanto el HTML como el CSS). También puedes editar el HTML o el CSS sobre la marcha en el panel Elementos o Estilos que se abre.
