# Etiquetador de hablantes — Podcast Ale & Evo

Herramienta de un solo archivo para preparar la transcripción del bruto antes de pedirle
el mapa de montaje al proyecto de Claude.

**Abrir:** https://USUARIO.github.io/REPO/

## Qué hace

1. Cargas la transcripción del bruto: `.json` (lo mejor: Premiere exporta con timecode por
   palabra), `.srt` o `.txt`.
2. Cargas el video o el audio del capítulo.
3. Le das play y vas marcando mientras oyes:
   - `A` / `E` — aquí empieza Ale / Evo. La marca manda hasta la siguiente.
   - Clic en la palabra donde entra la otra + `A`/`E` — parte la línea ahí y marca.
   - Doble clic en una palabra — corregir lo que la transcripción entendió mal.
   - `R` `T` `C` `F` `P` `Q` — momentos: risa, tensión, confesión, frase citable,
     consejo práctico, interpelación a la audiencia.
4. Descargas dos archivos del mismo trabajo:
   - `cap-N-marcado.txt` → se lo subes al proyecto de Claude para que arme el mapa.
   - `cap-N-hablantes.xml` → se importa en Premiere: tira de colores mango (Ale) / rosa (Evo)
     más un marcador en cada momento.

## Nada se sube a internet

El video y la transcripción los abre el navegador desde tu disco. No hay servidor ni base de
datos. Nunca metas un `.txt` ni un `.mp4` de un capítulo en este repositorio.

Guarda una copia automática en el navegador y te la ofrece si recargas la misma transcripción,
pero la copia que te llevas de verdad es el botón **Guardar avance**.

## Colores

Ale = mango, Evo = rosa. Las mismas etiquetas que en Premiere.

## Si actualizas el archivo

GitHub Pages cachea. Después de subir una versión nueva, abre con `Cmd+Shift+R` o vas a
seguir viendo la vieja sin darte cuenta.
