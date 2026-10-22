# TuxGuitar Web

Un solo archivo (`index.html`). Usa alphaTab desde jsDelivr para leer .gp3/.gp4/.gp5/.gpx/.gp, mostrar la partitura y la tablatura, y reproducir con soundfont.

## Publicarlo para usarlo desde cualquier dispositivo (gratis)

Cualquiera de estas opciones sirve, solo hay que subir `index.html`:

- **Netlify Drop**: entra en app.netlify.com/drop y arrastra la carpeta. Te da un enlace.
- **GitHub Pages**: crea un repositorio, sube `index.html`, y en Settings > Pages elige la rama principal.
- **Cloudflare Pages / Vercel**: crea un proyecto estático y sube el archivo.

Ábrelo con HTTPS (las tres opciones lo dan), porque el audio y el almacenamiento local lo requieren.

## Uso

1. Elige o suelta un archivo Guitar Pro.
2. Reproducir / Pausar (barra espaciadora).
3. Tempo: el control muestra los BPM reales (BPM original por el porcentaje).
4. Bucle: arrastra sobre la partitura para seleccionar un fragmento, o escribe compases y pulsa «Fijar». «Todo» quita el bucle.
5. El mástil resalta las notas que suenan en la pista elegida.
6. Los archivos recientes quedan guardados solo en ese navegador.

## Sobre descargar tablaturas de internet

Ultimate-Guitar y otros sitios no permiten que una página web descargue sus archivos desde el navegador (bloqueo CORS), y los Guitar Pro de Ultimate-Guitar requieren cuenta. Por eso el flujo es: descargas el archivo desde el sitio y lo subes aquí. El campo de enlace solo funciona con servidores que permitan CORS.
