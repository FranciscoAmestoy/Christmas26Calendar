# 🔊 Placeholders de Audio — Día 03: ¡Apuros en el Correo!

Todos los archivos `.mp3` en esta carpeta son inicialmente **archivos de texto (`.txt` renombrados a `.mp3`)** que sirven como *placeholders* para cada efecto de sonido del minijuego.

Mientras un archivo sea un placeholder de texto, el motor de audio del juego utiliza automáticamente su **sintetizador procedural (Web Audio API)**. En cuanto reemplaces cualquiera de estos archivos por un `.mp3` real con el mismo nombre, el juego reproducirá tu archivo automáticamente.

## Lista completa de efectos (11 archivos):
1. `bgm_day03.mp3` — Música de fondo estilo arcade / Cooking Fever en bucle.
2. `start_game.mp3` — Campanilla de mostrador al comenzar el turno.
3. `letter_spawn.mp3` — Llegada de una nueva carta a la mesa de trabajo.
4. `pickup_letter.mp3` — Agarrar (drag) una carta de la mesa.
5. `drop_correct.mp3` — Clasificar una carta en la caja correcta (+reinicio de barra de 7s).
6. `drop_wrong.mp3` — Soltar una carta en una caja del color incorrecto (-1 vida).
7. `timer_warning.mp3` — Tic-tac de alerta en los últimos segundos de la barra de 7s.
8. `timeout_life.mp3` — Agotar los 7 segundos sin clasificar una carta (-1 vida).
9. `rush_wave.mp3` — Aviso de hora pico postal.
10. `victory.mp3` — Fanfarria al completar el turno del Día 03.
11. `game_over.mp3` — Sonido de derrota al perder las 3 vidas.
