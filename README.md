# La Caja Embrujada

Juego de preguntas para 3.º de primaria: estás atrapado en una sala embrujada y tienes que conseguir una llave por asignatura (Matemáticas, Inglés, Conocimiento del medio y Lengua) respondiendo bien para abrir la puerta.

## Cómo jugar

Abre `index.html` en el navegador. No necesita instalación ni conexión.

## Editar las preguntas

El banco de preguntas está en `index.html`, en `window.CATEGORIAS`. Cada pregunta es:

```js
["Pregunta", "RESPUESTA CORRECTA", "falsa 1", "falsa 2", "falsa 3"]
```

La respuesta correcta va siempre la primera; el juego baraja las opciones.
