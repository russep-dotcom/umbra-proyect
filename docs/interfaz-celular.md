# INTERFAZ CELULAR (exclusivo móvil, Tap here: max-width 640px / pointer coarse)

Todo lo de esta lista vive SOLO en celular. No se toca desde computador y viceversa.
Aplica a las 2 páginas: normal (portada + cajón) y editor.

## Portada (index.html)
- Menú hamburguesa ☰ con panel `#controles` (música y ajustes viven adentro).
- Botón de música flotante ♪ con etiqueta MÚSICA + aviso "ENCIENDE EL SONIDO AQUÍ ↓" fijo arriba de él.
- Botón de ajustes (engranaje) con etiqueta AJUSTES debajo.
- Zoom fijo: `maximum-scale=1.0`, `user-scalable=no`, `touch-action: pan-x pan-y`, freno a `gesturestart` y Ctrl+rueda.
- Linterna que persigue con retardo: glitch al tocar + fundido lento al soltar (`fantasma-off`), deriva sola en quietud.
- Brasas `subir-movil`: 8 puntos (3–10px, 9–26s) que llegan hasta el logo y se desvanecen ahí.
- Luna recogida (190px aprox).

## Cajón (archivo.html)
- Panel de ajustes encima del botón (`bottom:130px`, botón arriba SIEMPRE) + cierre con clic fuera y Escape.
- Sin botón rectangular de viento: solo nota ♪ flotante + etiqueta MÚSICA.
- Aviso de sonido reposicionado arriba de la nota.
- Rango de velocidad y fade de brasas: igual que portada móvil.
- Aviso de update con `mensaje_movil`.

## Editor (pendientes/editor.html)
- Fondo degradado + luna de sangre mejorada (220px, anillo orbital) + sello morado reforzado.
- Título en Creepster; fundido puerta→panel al entrar.
- Nota ♪ flotante; ajustes flotantes; pie visible.
- Tablero: pantalla completa ⛶/✕, puntos al elegir tarjeta, tap para elegir, borde 14px táctil, `board-tip` oculto.
- Recuadros y textos centrados; puntos solo en tarjeta elegida.

## REGLA
Si algo de aquí se vuelve igual en computador, se MUEVE al híbrido.
Si algo del híbrido se vuelve distinto, se SACA a este archivo.
