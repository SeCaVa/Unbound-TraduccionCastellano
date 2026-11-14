# Pokémon Unbound — Traducción al castellano

**English speakers:** [read this README in English](#english).

Traducción no oficial al castellano (España) de **Pokémon Unbound**, el hack de Pokémon Rojo Fuego creado por
**Skeli** y su equipo. Una región nueva, Borrius, con su propia historia, Pokémon de todas las generaciones,
megaevoluciones, formas regionales, misiones secundarias y varios modos de dificultad.

La traducción está hecha sobre la **versión 2.1.1.1** del hack.

> **Versión 1.04.** Dos parches: con **ZA Megas** o sin él (Unbound oficial). 56 frases de combate que se salían de la caja ahora caben, el rótulo «Battle!» de los jefes está en castellano y los iconos de estado de la barra de vida (ENV, PAR, DOR, CON, QUE) y su etiqueta «PS» ya no salen en inglés.
> Desde la 1.03: En el Registro de misiones vuelve a verse «Restantes: N» en las misiones con contador y los consejos ya no se salen de la caja.
> Desde la 1.02: El Montañero del Gran Desierto vuelve a hablar cuando le hablas otra vez tras darte la megapiedra y el teclado de contraseñas pone «Contraseña» sin cortarse.
> Desde la 0.993: Descripciones de movimientos que se salían de la ficha, «Ladrón» y otros nombres de movimiento en diálogos, unos 25 textos que seguían en inglés y un fallo de sonido en una escena con ZA.
> Desde la 0.992: arreglado «Entrenador» con protagonista chico.
> Desde la 0.991: Incluye **ZA Megas**, el parche de fans de Alphapenguin42 con las megaevoluciones de Leyendas Pokémon: Z-A, ya traducido: 41 megapiedras con su nombre oficial, sus habilidades nuevas y los diálogos de quienes las dan. Además: símbolo «N°», «Nv. recomendado» traducido, descripción completa de la Baya Rimoya y de otras 22 bayas, y descripciones de misiones que ya no pierden texto.
> Desde la 0.99: Arreglada la Cueva del Valle 1F (teselas rotas alrededor de la sala) y la ventana de datos del movimiento (tecla L) sin textos cortados.
> Desde la 0.97: Arreglado el botón «(B) Atrás».
> Desde la 0.96: Arreglado un cuelgue en combates salvajes (mensaje del arcoíris), los diálogos de Ace y
> Log sobre la Pokédex vuelven a verse bien, 14 entradas de la Pokédex con su texto oficial y «(B) Atrás».
> Desde la 0.95: gritos y exclamaciones con su «¡». Desde la 0.94: reloj del menú en 24 horas y fecha en formato día/mes/año, unos 50 diálogos que
> seguían en inglés ya traducidos, descripciones de movimientos Dinamax que ya no se cortan, nombres de zona que
> caben en el mapa, «Agua» en el DexNav y «completar» la Pokédex. Desde la 0.93: registro de misiones en castellano,
> «Alcantarillas» en el mapa y «Tema salvaje» completo. Desde la 0.92: rótulos de la ficha centrados,
> «Movimientos» y «SELECT Mover» corregidos, «¡Captúralo para más información!» completo y botones de la Caja de
> trajes en castellano. Incluye todo lo de la 0.91: gráficos en castellano (iconos de tipo con HADA, ficha, «PS», «MO», DexNav), Pokédex en metros y kilos, y
> textos largos acortados para que no cuelguen el juego.
> Sigue siendo una beta: puede quedar alguna errata o algún texto que se sale del cuadro. Cualquier aviso se agradece mucho.

> Este repositorio solo contiene el parche de la traducción.
> **No incluye ninguna ROM.** Necesitas tu propia copia de Pokémon FireRed (USA).

---

## Cómo jugar

1. Consigue una ROM de **Pokémon - FireRed Version (USA)**, revisión 1.0.
   - CRC32: `DD88761C`
   - La revisión 1.1 no sirve: si al encender sale «Presents» bajo el logo de GAME FREAK, es la 1.1 y el juego
     se quedará en blanco o se colgará. Rom Patcher JS enseña el CRC32 de tu ROM antes de parchear.
2. Elige uno de los dos parches de la [última versión](https://github.com/SeCaVa/Unbound-TraduccionCastellano/releases/latest) y aplícalo directamente
   a esa ROM con [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) (desde el navegador) o con Floating IPS (Flips):
   - `Unbound_ES_v1.04.bps`: con **ZA Megas**, el parche de fans de Alphapenguin42 con las megaevoluciones de
     Leyendas Pokémon: Z-A. ROM resultante: **CRC32 `7CD7F1B0`**.
   - `Unbound_ES_v1.04_sinZA.bps`: Pokémon Unbound oficial, sin ZA Megas. ROM resultante: **CRC32 `1DC26F6C`**.

   ZA Megas no es una actualización oficial de Skeli. Si algún día sale una versión oficial nueva, una partida con
   megapiedras de ZA podría no pasar tal cual a ella. Si prefieres no arriesgarte, usa el parche sin ZA.
3. Juega con cualquier emulador de GBA (mGBA recomendado).

Desde la v0.3 el parche se aplica **directamente sobre FireRed (USA)**: ya no hace falta el parche inglés de Pokémon Unbound 2.1.1.1 (lleva el hack incluido).

---

## Qué está traducido

- **Diálogos** de los mapas: historia principal, misiones secundarias y postgame.
- **Menús y combate**: mensajes de combate, menús, PC, Pokédex, ficha del Pokémon, ficha de entrenador, tiendas y
  las opciones propias del hack.
- **Nombres**: Pokémon, movimientos, habilidades, objetos, tipos, naturalezas, lugares y clases de entrenador.
- Donde existe un nombre o texto oficial, se usa el oficial en español: el de **Pokémon Rojo Fuego** y, para todo
  lo que el hack añade de generaciones posteriores, los nombres oficiales actuales.
- **Descripciones** de movimientos, habilidades y objetos, y entradas de la Pokédex.
- **Protagonista chico o chica**: los diálogos concuerdan en género con el personaje elegido.
- Mensajes de subida y bajada de estadísticas como en los juegos en español ("¡El Ataque de X subió mucho!").

- **Combate**: los Pokémon rivales y salvajes se distinguen como en los juegos en español ("¡Pidgey salvaje usó
  Placaje!") y las clases de entrenador tienen forma masculina y femenina (Experto/Experta, Científico/Científica…).
- **Pantalla de título y rótulos dibujados** en castellano ("PULSA START", "SELECT Mover", "START Orden", "FICHA ENTRENADOR", "MEDALLAS").
- **Chat Fácil** con las palabras oficiales de Pokémon Rojo Fuego.

Los **créditos finales** se dejan en inglés.

### Errores
Si encuentras algo en inglés, un texto que se sale del cuadro o una errata, rellena el [formulario de fallos](https://github.com/SeCaVa/Unbound-TraduccionCastellano/issues/new?template=fallo.yml).
Pide versión, emulador, zona y captura, y así puedo arreglarlo sin preguntarte nada más.

---

## Créditos

### Pokémon Unbound (hack original)
**Pokémon Unbound** es obra de **Skeli** y de quienes le ayudaron a hacerlo.
Todo el mérito del juego es suyo. Esta traducción solo cambia el idioma.

### ZA Megas
[**ZA Megas**](https://codeberg.org/Alphapenguin42/unbound-za-megas) es un parche de fans de **Alphapenguin42**
que añade a Pokémon Unbound las megaevoluciones de Leyendas Pokémon: Z-A. Todo el mérito de ese añadido es suyo;
aquí solo va integrado y traducido.

El hack usa **Complete FireRed Upgrade (CFRU)** y **Dynamic Pokémon Expansion (DPE)**, de Skeli789 y sus
colaboradores.

Pokémon Rojo Fuego: © Nintendo / Creatures Inc. / GAME FREAK inc.

### Traducción al castellano
- Traducción: **SeCaVa**.
- Nombres y textos oficiales de Pokémon Rojo Fuego en español: © Nintendo / Creatures Inc. / GAME FREAK inc.

☕ Si quieres apoyar mi trabajo como traductor, puedes hacerlo en [Ko-fi](https://ko-fi.com/secava),
[Patreon](https://www.patreon.com/secava) o [GitHub Sponsors](https://github.com/sponsors/SeCaVa). Es totalmente
voluntario: la traducción es y seguirá siendo gratis. Y si te gusta el juego, apoya también a Skeli, su autor.

### Aviso
Proyecto de fans sin ánimo de lucro, no afiliado a Nintendo, The Pokémon Company, Creatures ni GAME FREAK.
Pokémon es una marca registrada de Nintendo, Creatures Inc. y GAME FREAK inc. No se distribuye ninguna ROM:
usa solo copias de juegos que poseas legalmente.

---

## English

Unofficial **Spanish (Spain) translation** of **Pokémon Unbound**, the Pokémon FireRed hack made by **Skeli** and
team: a brand-new region, Borrius, with its own story, Pokémon from every generation, Mega Evolutions, regional
forms, side quests and several difficulty modes.

The translation is based on **version 2.1.1.1** of the hack.

> **Version 1.04.** Two patches: with **ZA Megas** or without it (official Unbound). 56 battle lines that overflowed the text box now fit, the boss «Battle!» label is in Spanish, and the health-bar status icons (ENV, PAR, DOR, CON, QUE) and their «PS» label no longer show in English.
> Since 1.03: The quest log shows «Restantes: N» again on quests with a counter, and its tips no longer overflow the box.
> Since 1.02: The Great Desert Ruin Maniac talks again when you speak to him after he gives you the Mega Stone, and the password keyboard title now reads «Contraseña» without being cut off.
> Since 0.993: Move descriptions overflowing the summary screen, «Ladrón» and other move names in dialogue, about 25 texts still in English and a sound bug in one scene with ZA.
> Since 0.992: fixed «Entrenador» with a male protagonist.
> Since 0.991: Includes **ZA Megas**, Alphapenguin42's fan patch with the Mega Evolutions from Pokémon Legends: Z-A, now translated: 41 Mega Stones with their official names, their new Abilities and the dialogue of the people who give them. Also: «N°» number sign, «Nv. recomendado» translated, full descriptions for 23 Berries, and quest descriptions that no longer lose text.
> Since 0.99: Valley Cave 1F fixed (broken tiles around the room) and the move info window (L button) without cut-off text.
> Since 0.97: Fixed the «(B) Atrás» button.
> Since 0.96: Fixed a hang in wild battles (rainbow message), Ace and Log's Pokédex dialogues display
> correctly again, 14 Pokédex entries with their official text and «(B) Atrás».
> Since 0.95: shouts with their opening «¡». Since 0.94: 24-hour clock and day/month/year dates, about 50 dialogues that were still in English now
> translated, Dynamax move descriptions no longer cut off, area names that fit on the map, «Agua» in the DexNav and
> «completar» for the Pokédex. Since 0.93: quest log in Spanish, «Alcantarillas» on the map and the full «Tema
> salvaje» description. Since 0.92: summary screen labels centred, «Movimientos» and
> «SELECT Mover» fixed, the full «¡Captúralo para más información!» and the Outfit Box buttons in Spanish.
> Includes everything from 0.91: graphics
> in Spanish (type icons with Fairy, summary screen, «PS», «MO», DexNav), Pokédex in metres and kilograms, and long
> texts shortened so they cannot crash the game.
> It is still a beta: there may be some typos or overflowing text. Any report is very welcome.

> This repository only contains the translation patch.
> **It does not include any ROM.** You need your own copy of Pokémon FireRed (USA).

### How to play

1. Get a ROM of **Pokémon - FireRed Version (USA)**, revision 1.0.
   - CRC32: `DD88761C`
   - Revision 1.1 won't work: if "Presents" shows under the GAME FREAK logo when you boot it, it's 1.1 and the
     game will show a white screen or crash. Rom Patcher JS shows your ROM's CRC32 before patching.
2. Pick one of the two patches from the [latest release](https://github.com/SeCaVa/Unbound-TraduccionCastellano/releases/latest) and apply it directly
   to that ROM with [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) (in the browser) or with Floating IPS (Flips):
   - `Unbound_ES_v1.04.bps`: with **ZA Megas**, Alphapenguin42's fan patch with the Mega Evolutions from Pokémon
     Legends: Z-A. Resulting ROM: **CRC32 `7CD7F1B0`**.
   - `Unbound_ES_v1.04_sinZA.bps`: official Pokémon Unbound, without ZA Megas. Resulting ROM: **CRC32 `1DC26F6C`**.

   ZA Megas is not an official update by Skeli. If a new official version comes out, a save with ZA Mega Stones
   might not carry over as is. If you'd rather not risk it, use the patch without ZA.
3. Play it on any GBA emulator (mGBA recommended).

Since v0.3 the patch applies **directly to FireRed (USA)**: the English Pokémon Unbound 2.1.1.1 patch is no longer needed (the hack is included).

### What is translated

- **Dialogue** on the maps: main story, side quests and postgame.
- **Menus and battles**: battle messages, menus, PC, Pokédex, Pokémon summary, Trainer Card, shops and the hack's
  own options.
- **Names**: Pokémon, moves, abilities, items, types, natures, places and Trainer classes, using the official
  Spanish names wherever they exist.
- **Descriptions** of moves, abilities and items, and Pokédex entries.
- **Boy or girl protagonist**: the dialogue agrees in gender with the chosen character.
- Stat change messages worded like in the Spanish games.

- **Battles**: opposing and wild Pokémon are told apart like in the Spanish games, and Trainer classes have male
  and female forms.
- **Title screen and drawn labels** in Spanish.
- **Easy Chat** uses the official Spanish FireRed words.

The ending credits are left in English.

If you find something still in English, text overflowing its box or a typo, please fill in the [bug report form](https://github.com/SeCaVa/Unbound-TraduccionCastellano/issues/new?template=fallo.yml).
It asks for the version, emulator, location and a screenshot.

### Credits

**Pokémon Unbound** (original hack) is the work of **Skeli** and the people who helped make it. All the credit for
the game goes to them; this translation only changes the language.

[**ZA Megas**](https://codeberg.org/Alphapenguin42/unbound-za-megas) is a fan patch by **Alphapenguin42** that adds the
Mega Evolutions from Pokémon Legends: Z-A to Pokémon Unbound. All the credit for it goes to them; here it is only
integrated and translated.

The hack uses **Complete FireRed Upgrade (CFRU)** and **Dynamic Pokémon Expansion (DPE)**, by Skeli789 and
contributors.

**Spanish translation**
- Translation: **SeCaVa**.
- Official names and texts from the Spanish Pokémon FireRed: © Nintendo / Creatures Inc. / GAME FREAK inc.

☕ If you'd like to support my work as a translator, you can do so on [Ko-fi](https://ko-fi.com/secava),
[Patreon](https://www.patreon.com/secava) or [GitHub Sponsors](https://github.com/sponsors/SeCaVa). It's completely
optional: the translation is and will always be free. And if you enjoy the game, please support Skeli, its author,
too.

**Disclaimer**

Non-profit fan project, not affiliated with Nintendo, The Pokémon Company, Creatures or GAME FREAK. Pokémon is a
registered trademark of Nintendo, Creatures Inc. and GAME FREAK inc. No ROM is distributed: only use copies of games
you legally own.
