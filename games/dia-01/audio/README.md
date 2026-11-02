# 🔊 Placeholders de Audio — Día 01: ¡Adiós Halloween, Hola Navidad!

Todos los archivos `.mp3` en esta carpeta son inicialmente **archivos de texto (`.txt` renombrados a `.mp3`)** que sirven como *placeholders* documentados para cada efecto de sonido del minijuego.

Mientras un archivo sea un placeholder de texto, el motor de audio del juego detecta automáticamente que no es binario MP3 y ejecuta en tiempo real un **sintetizador procedural (Web Audio API)**. En cuanto reemplaces cualquiera de estos archivos por un `.mp3` real con el mismo nombre, el juego reproducirá tu archivo de audio automáticamente.

## Lista completa de efectos (16 archivos):
1. `bgm_day01.mp3` — Música de fondo en bucle.
2. `start_game.mp3` — Iniciar o reiniciar la partida.
3. `click_deco.mp3` — Clic sobre una decoración de Halloween encontrada.
4. `pack_box.mp3` — La decoración entra y se guarda en la caja de cartón.
5. `miss_click.mp3` — Clic en zona vacía del escenario.
6. `spawn_ghost.mp3` — Aparición del Fantasma (`👻`).
7. `spawn_vampire.mp3` — Aparición del Vampiro (`🧛`).
8. `spawn_skeleton.mp3` — Aparición del Esqueleto (`💀`).
9. `spawn_zombie.mp3` — Aparición del Zombie (`🧟`).
10. `monster_hit.mp3` — Golpe/clic rápido sobre el monstruo activo.
11. `timer_tick.mp3` — Tic-tac de cuenta regresiva en los últimos segundos.
12. `monster_banish.mp3` — Monstruo derrotado y encerrado a tiempo.
13. `lose_life.mp3` — Tiempo agotado (10s) y pérdida de 1 vida.
14. `room_clear.mp3` — Habitación despejada por completo.
15. `victory.mp3` — Victoria al limpiar las 5 habitaciones.
16. `game_over.mp3` — Derrota al quedarse sin vidas.
