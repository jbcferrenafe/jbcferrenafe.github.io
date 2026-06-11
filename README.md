# Página web JBC - Jóvenes Bodas de Caná (Ferreñafe)

## Estructura de archivos

```
JBC/
├── index.html          (Inicio)
├── nosotros.html        (Quiénes somos, misión, visión, valores)
├── actividades.html     (Reunión semanal, tipos de actividad, próximos eventos)
├── galeria.html         (Galería de fotos)
├── estilo-base.css      (Estilos compartidos: navbar, footer, botones, colores)
├── estilo-inicio.css
├── estilo-nosotros.css
├── estilo-actividades.css
├── estilo-galeria.css
└── img/                  <-- AQUÍ DEBES COLOCAR TUS IMÁGENES
```

## Imágenes que debes agregar en la carpeta /img

Reemplaza estos nombres por tus propias fotos (o cambia el nombre dentro
del HTML por el de tu archivo). Mientras no agregues las imágenes, el
diseño se verá igual pero con espacios en blanco/rotos donde van las fotos.

| Archivo a colocar           | Dónde se usa                              |
|------------------------------|--------------------------------------------|
| logo-jbc.png                 | Logo en navbar y footer (todas las páginas) |
| fondo-jbc.png                | Fondo decorativo de la página de Inicio     |
| jbc-hero.jpg                 | Foto principal del Inicio (hero)            |
| jbc-actividad.jpg             | Foto de la sección "Únete a nosotros"      |
| jbc-comunidad.jpg             | Foto de la comunidad en "Nosotros"          |
| actividad-formacion.jpg       | Tarjeta "Encuentros de formación"           |
| actividad-retiro.jpg          | Tarjeta "Retiros y vigilias"                |
| actividad-servicio.jpg        | Tarjeta "Misiones y servicio"               |
| actividad-celebracion.jpg     | Tarjeta "Celebraciones y paseos"            |
| galeria-01.jpg a galeria-08.jpg | Las 8 fotos de la página Galería          |

## Datos de contacto a personalizar

Busca y reemplaza en todos los archivos HTML:
- `https://wa.me/51900000000` → tu número real de WhatsApp con código de país
  (ej: 51987654321, sin "+" ni espacios).
- `https://www.facebook.com/` → el link a tu página de Facebook.
- `https://www.instagram.com/` → el link a tu cuenta de Instagram.

En `actividades.html`, completa los datos reales de:
- Día y hora de la reunión semanal.
- Lugar (parroquia / local).
- Fechas de los próximos eventos (donde dice "--" y "---").

## Colores usados (puedes ajustarlos en estilo-base.css, sección :root)

- Azul Caná (María): `#2c4a7c`
- Rojo vino (vino nuevo de las bodas): `#8b1e3f`
- Blanco cálido (fondo): `#faf8f5`
- Dorado (detalles): `#cfa15c`

## Cómo abrirlo en VS Code

1. Descomprime la carpeta JBC.
2. Ábrela en VS Code (`Archivo > Abrir carpeta`).
3. Coloca tus imágenes dentro de la carpeta `img/`.
4. Haz clic derecho en `index.html` y selecciona "Open with Live Server"
   (o simplemente ábrelo en el navegador) para ver el resultado.
