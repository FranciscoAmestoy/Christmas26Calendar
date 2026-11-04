# 🔊 Placeholders de Audio — Día 05: El Faro de la Aurora Boreal (Cajas de Fusibles)

Todos los archivos `.mp3` en esta carpeta son inicialmente **archivos de texto (`.txt` renombrados a `.mp3`)** que sirven como *placeholders* para cada efecto de sonido del minijuego.

Mientras un archivo sea un placeholder de texto, el motor de audio del juego utiliza automáticamente su **sintetizador procedural (Web Audio API)**. Cuando reemplaces cualquiera por un `.mp3` real con el mismo nombre, se reproducirá tu archivo automáticamente.

## Lista completa de efectos (10 archivos):
1. `bgm_day05.mp3` — Música ambiental del Faro de la Aurora en bucle.
2. `start_game.mp3` — Apertura de la primera caja de fusibles.
3. `find_fuse.mp3` — Encontrar un fusible oculto e insertarlo en el tablero.
4. `wire_start.mp3` — Tocar un terminal para comenzar a tender un cable.
5. `wire_step.mp3` — Avanzar el cable celda por celda.
6. `wire_connect.mp3` — Conexión exitosa e iluminación de un circuito de color.
7. `wire_cross_error.mp3` — Chispazo al intentar cruzar o pisar otro cable.
8. `wire_clear.mp3` — Desconectar o limpiar cables.
9. `box_powerup.mp3` — Energía completa en una Caja de Fusibles y paso al siguiente nivel.
10. `victory.mp3` — Fanfarria al encender el Faro de la Aurora Boreal (Nivel 3 completado).
