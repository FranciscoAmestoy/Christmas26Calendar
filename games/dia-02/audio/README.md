# 🔊 Placeholders de Audio — Día 02: Cartas a Santa Claus (Acróstico)

Todos los archivos `.mp3` en esta carpeta son inicialmente **archivos de texto (`.txt` renombrados a `.mp3`)** que sirven como *placeholders* para cada efecto de sonido del minijuego.

Mientras un archivo sea un placeholder de texto, el motor de audio del juego utiliza automáticamente su **sintetizador procedural (Web Audio API)** (incluyendo el sonido de rasgueo de pluma sobre pergamino en tiempo real). Cuando reemplaces cualquiera de estos archivos por un `.mp3` real con el mismo nombre, se reproducirá tu archivo automáticamente.

## Lista completa de efectos (10 archivos):
1. `bgm_day02.mp3` — Música de fondo en bucle (cajita musical / escritorio navideño).
2. `start_game.mp3` — Desplegar la carta en blanco sobre el escritorio.
3. `write_letter.mp3` — Trazo de pluma escribiendo una letra en cursiva.
4. `erase_letter.mp3` — Borrar una letra de una casilla.
5. `select_row.mp3` — Cambiar de casilla o renglón en la carta.
6. `word_complete.mp3` — Completar correctamente una palabra horizontal del acróstico.
7. `wrong_word.mp3` — Aviso cuando una fila completada tiene letras incorrectas.
8. `use_hint.mp3` — Usar el tintero mágico para revelar una letra con la pluma.
9. `stamp_seal.mp3` — Estampar el sello de lacre rojo al terminar el acróstico.
10. `victory.mp3` — Fanfarria de victoria al enviar la carta a Santa Claus.
