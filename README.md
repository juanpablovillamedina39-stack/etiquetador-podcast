# Etiquetador de hablantes — Podcast Ale & Evo

Herramienta de un solo archivo para marcar quién habla en la transcripción del bruto,
antes de pedirle el mapa de montaje al proyecto de Claude.

**Abrir:** https://USUARIO.github.io/REPO/

## Qué hace

1. Cargas la transcripción del bruto (`.srt` o `.txt` con timecodes).
2. Cargas el video o el audio del capítulo.
3. Le das play y marcas con `A` (Ale) y `E` (Evo) cada vez que cambia la voz.
   La marca manda hasta la siguiente.
4. Descargas dos archivos del mismo trabajo:
   - `cap-N-marcado.txt` → se lo subes al proyecto de Claude para que arme el mapa.
   - `cap-N-hablantes.xml` → se importa en Premiere: tira de colores mango (Ale) / rosa (Evo).

## Nada se sube a internet

El video y la transcripción los abre el navegador desde tu disco. No hay servidor, no hay
base de datos, no se guarda nada en ningún lado. Si cierras la pestaña sin darle
**Guardar avance**, el marcado se pierde: usa ese botón cada tanto.

## Colores

Ale = mango, Evo = rosa. Las mismas etiquetas que en Premiere.

## Si actualizas el archivo

GitHub Pages cachea. Después de subir una versión nueva, abre con `Cmd+Shift+R` para
forzar la recarga, o no vas a ver los cambios.
