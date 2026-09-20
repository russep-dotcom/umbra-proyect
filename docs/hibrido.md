# HÍBRIDO (compartido: igual en celular y computador)

Solo entra aquí lo IDÉNTICO en ambas pantallas. Si algo se vuelve distinto,
se SACA a `interfaz-celular.md` o `interfaz-computador.md` (así no se repite
lo del tablero, donde se mezcló todo).

## Estructura y navegación
- Portada → cajón de archivos → registro/entidad (+ sala de evidencias).
- Bienvenida: sale una sola vez en la vida (`umbra_bienvenida_vista`).
- Versionado triple: código + pie + `version.json` (hoy v4.35).
- Aviso de update: chequeo al cargar (3s) + cada 20s + al volver/foco; una vez
  por versión cada 24h (`umbra_update_avistado`); esconde aviso rancio al volver
  atrás; campana que repite al primer toque si nació dormida.

## Pantallas de carga (rotación cada 2 normales + 1 desconexión)
- Portal (ojo JARVIS + susurro + barra + %): murmullo + latido con armónico.
- Logo/vigilante: almas por categoría (ALFA almas, DELTA/BETA/GAMMA fallas).
- Suave de regreso + `vuelta.wav`.
- Desconexión (SEÑAL PERDIDA + `glitch-alfa.wav`).

## Ajustes (mismo panel, valores compartidos)
- 10 volúmenes propios: música, viento, portal, ALFA, DELTA, BETA, GAMMA/OMEGA,
  vuelta, desconexión, clic. Claves `umbra_vol_*` con migración de gustos viejos.
- Controles morados dibujados a mano; lista con scroll sin barra visible.
- Sin sombrear textos en toda UMBRA (solo campos con foco).

## Registros publicados
- Expediente combinado: color de clasificación + dossier + sello + cinta
  EVIDENCIA + hueco de foto. Textos escapados.

## Editor privado (sin versión pública, no enlazado)
- Puerta con clave + intro + portal/suave/crash + INTERFAZ y PUBLICAR.
- Exportar/importar registros entre aparatos (merge sin duplicados).
- Cara UMBRA con detalles morados; linterna con color de tarjeta.
- Tablero: el % de zoom lleva aire a la derecha para que el botón ⛶/✕ no lo tape (50px normal, 60px en pantalla completa).
- Update propio con clave `editor` en `version.json` (mensajes por pantalla, aviso una vez por versión cada 24h, botón salta a `?v=` fresco): los cambios del editor suben `editor`, nunca `version`.

## REGLA DE ORO
Lo compartido vive aquí. Lo distinto vive en su archivo. Al cambiar algo,
revisar si sigue siendo igual en ambas: si no, moverlo.
