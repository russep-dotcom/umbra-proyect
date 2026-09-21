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
- Tablero: pantalla completa ⛶/✕, puntos al elegir tarjeta, `board-tip` oculto, aviso «TOCA LA A Y LUEGO EL TABLERO».
- Herramienta de texto estilo excalidraw (botón A en la barra, no existe en computador): la A es el interruptor (morada = toco y escribo, gris = no pasa nada) y solo se apaga con la A; A y luego tablero para escribir solo la barrita, sin recuadro ni ✕; cada toque escribe en el dedo (la vacía anterior desaparece, la escrita se queda);
- Mini-menú de texto abajo (`#estilo-pop`: A−/A+, FUENTE, COLOR) con paneles arriba (`#sub-fuente` con NORMAL/MÁQUINA/TERROR; `#sub-color` con familias, TONOS por familia y CÓDIGO hex): abre con la A y al tocar texto escrito (lo re-selecciona y aplica), sin margen jamás en celular; lo elegido aplica al texto y se hereda al siguiente; al abrir el teclado los paneles se cierran y la base se deja tapar; tocar sus botones no mata la pendiente. NORMAL hereda la página y MÁQUINA es Courier New (toda la página ya es Special Elite, por eso se veían iguales).
- Umbral de toque 14px; foco en toque + clic + cuadro siguiente sin mover la página; purga de vacías al entrar; la rayita nace bajo el dedo (auto-corrección) y se revela con movimiento mínimo si el teclado desplaza.
- Puntos de agarre grandes (28px) para recuadros; el tamaño de letra sale del mini-menú (10–64px, viaja entre aparatos).
- Recuadros y textos centrados; puntos solo en tarjeta elegida.

## REGLA
Si algo de aquí se vuelve igual en computador, se MUEVE al híbrido.
Si algo del híbrido se vuelve distinto, se SACA a este archivo.
