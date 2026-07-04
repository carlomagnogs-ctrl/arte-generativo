# Arte Generativo

Una app web de una sola página que genera arte generativo interactivo usando `<canvas>` y JavaScript puro. Sin dependencias ni build step: se abre directo en el navegador.

## Uso

Abrí [index.html](index.html) en un navegador (doble clic o `start index.html` en Windows).

- Mové el mouse (o el dedo en pantallas táctiles) sobre el lienzo para dibujar.
- Si no interactuás, la app dibuja sola con un patrón animado.

## Controles

| Control | Descripción |
|---|---|
| Color (matiz) | Tono base de las partículas (0-360°) |
| Velocidad | Qué tan rápido se mueven las partículas |
| Tamaño | Radio base de cada partícula |
| Simetría (espejos) | Cantidad de reflejos radiales alrededor del centro |
| Estela (persistencia) | Cuánto tarda en desvanecerse el rastro dejado |

Botones:

- 🎲 **Aleatorio** — randomiza todos los controles.
- 🧹 **Limpiar** — borra el lienzo y las partículas activas.
- ⏸ **Pausar** — pausa/reanuda la animación.
- 💾 **Guardar PNG** — descarga el lienzo actual como imagen PNG.
