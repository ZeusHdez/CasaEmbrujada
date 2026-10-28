# La Caja Embrujada

Juego de preguntas para jugar toda la clase en la pizarra digital o el proyector (3.º de primaria). La clase está atrapada en una casa embrujada: en cada ventana hay una asignatura (Matemáticas, Inglés, Conocimiento del medio y Lengua). Al pulsar una ventana se abre su pregunta en grande; si la aciertan, consiguen una llave. Con todas las llaves se abre la puerta.

## Cómo jugar

Abre `index.html` en el navegador (o la versión de GitHub Pages) y pulsa «Pantalla completa» para proyectarlo. No necesita instalación ni conexión.

## Editar las preguntas

El banco de preguntas está en `index.html`, en `window.CATEGORIAS`. Cada pregunta es:

```js
["Pregunta", "RESPUESTA CORRECTA", "falsa 1", "falsa 2", "falsa 3"]
```

La respuesta correcta va siempre la primera; el juego baraja las opciones.

## Música

- **🎵 Música** pone una melodía de miedo original que genera el propio navegador (no necesita internet).
- **📂 Tu canción** permite elegir un archivo de audio del ordenador (por ejemplo un MP3) para que suene en bucle en lugar de la melodía. El archivo no se sube a ningún sitio; solo suena en ese navegador.
