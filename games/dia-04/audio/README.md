# 🔊 Placeholders de Audio — Día 04: El Expreso rumbo al Polo Norte

Todos los archivos `.mp3` en esta carpeta son inicialmente **archivos de texto (`.txt` renombrados a `.mp3`)** que sirven como *placeholders* para cada efecto de sonido del minijuego.

Mientras un archivo sea un placeholder de texto, el motor de audio del juego utiliza automáticamente su **sintetizador procedural (Web Audio API)** (incluyendo el ritmo de locomotora a vapor, silbato del tren, cambios de carril, saltos y deslizamientos). Cuando reemplaces cualquiera por un `.mp3` real con el mismo nombre, se reproducirá tu archivo automáticamente.

## Lista completa de efectos (11 archivos):
1. `bgm_day04.mp3` — Música de fondo en bucle (ritmo de tren expreso navideño).
2. `start_train.mp3` — Silbato de vapor al arrancar la carrera.
3. `lane_shift.mp3` — Desplazamiento lateral entre los 3 carriles del pasillo.
4. `jump.mp3` — Salto sobre valijas y baúles bajos.
5. `slide_duck.mp3` — Deslizamiento por debajo de barreras y guirnaldas altas.
6. `collect_ticket.mp3` — Recolectar un Boleto Dorado en el pasillo.
7. `collect_cocoa.mp3` — Recolectar una Taza de Chocolate Caliente (bonificación).
8. `crash_obstacle.mp3` — Impacto contra un obstáculo (-1 vida).
9. `wagon_clear.mp3` — Cruzar de un vagón al siguiente.
10. `victory.mp3` — Llegada triunfal a la locomotora en el Polo Norte.
11. `game_over.mp3` — Derrota al perder las 3 vidas.
