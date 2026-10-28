# La Caja Embrujada

Juego de preguntas para jugar toda la clase en la pizarra digital o el proyector (3.º de primaria). La clase está atrapada en una casa embrujada: en cada ventana hay una asignatura (Matemáticas, Inglés, Conocimiento del medio y Lengua). Al pulsar una ventana se abre su pregunta en grande; si la aciertan, consiguen una llave. Con todas las llaves se abre la puerta y la clase escapa.

## Cómo jugar

Abre la versión de GitHub Pages (https://zeushdez.github.io/CasaEmbrujada/) y pulsa «Pantalla completa» para proyectarlo.

Si abres `index.html` con doble clic desde el ordenador, el navegador no deja leer `preguntas.json` solo: el juego te pedirá que elijas el archivo `preguntas.json` (está en la misma carpeta) y después funciona igual.

## Editar las preguntas

Todas las preguntas están en **`preguntas.json`**. Cada pregunta ocupa una línea:

```json
{ "pregunta": "¿Cuánto es 6 × 7?", "correcta": "42", "incorrectas": ["36", "48", "49"] },
```

- `correcta` es la respuesta buena; `incorrectas` son las falsas (de 1 a 5). El juego baraja las opciones.
- Para añadir una pregunta, copia una línea y cámbiala. Todas las líneas llevan una coma al final **menos la última** de cada lista.
- Usa siempre comillas dobles `"`. Si necesitas comillas dentro del texto, usa las tipográficas (“ ”).
- Cada categoría tiene `nombre`, `icono` (un emoji), `color` (por ejemplo `"#ffb84d"`) y su lista de `preguntas`. Puedes añadir o quitar categorías: habrá una ventana y una llave por cada una.
- Para quitar una asignatura sin borrar sus preguntas, pon `"activa": false`. Para que vuelva a salir, cámbialo a `"activa": true`. (Ahora mismo Inglés está desactivado.)

Si el archivo tiene un error (una coma o una comilla de más o de menos), el juego lo avisa en la pantalla de inicio y dice dónde está. También puedes comprobarlo pegándolo en https://jsonlint.com.

## Música y efectos

- **🎵 Música** pone una melodía de miedo original que genera el propio navegador (no necesita internet).
- **📂 Tu canción** permite elegir un archivo de audio del ordenador (por ejemplo un MP3) para que suene en bucle en lugar de la melodía. El archivo no se sube a ningún sitio.
- **🔇 Sin efectos / 🔊 Con efectos** activa los sonidos de acierto, fallo, truenos y la puerta.
