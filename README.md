[README.md](https://github.com/user-attachments/files/34544446/README.md)
# Ainhi# Zenery · Fútbol 7

App web para entrenadoras y entrenadores de fútbol 7. Funciona en el móvil y se puede instalar en la pantalla de inicio.

## Qué incluye
- **Inicio:** próximo partido, próximo entreno, balance de la temporada y goleadores.
- **Partidos:** próximos y jugados. Se pueden añadir ya jugados, con resultado.
- **Directo:** cronómetro, marcador, goles con goleadora y asistencia, tarjetas, descanso y 2.ª parte. Al terminar se guarda el resultado y se suman las estadísticas.
- **Entrenos:** horarios (con repetición semanal) y pasar lista.
- **Plantilla:** jugadoras con dorsal y posición, estadísticas y % de asistencia.
- **Pizarra:** campo de fútbol 7 con formaciones 2-3-1, 3-2-1 y 2-2-2, pasos y reproducción animada.

## Publicarla en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `zenery`).
2. Sube todos los archivos de esta carpeta (**Add file → Upload files**) y pulsa *Commit changes*.
3. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
4. En uno o dos minutos tendrás la web en `https://TU-USUARIO.github.io/zenery/`.

## Instalarla en el móvil
- **Android (Chrome):** menú ⋮ → *Instalar app* o *Añadir a pantalla de inicio*.
- **iPhone (Safari):** botón Compartir → *Añadir a pantalla de inicio*.

## Datos
Todo se guarda en el navegador del propio móvil (`localStorage`). No hay cuentas ni servidor, y los datos no se ven desde otro dispositivo. Si se borran los datos del navegador, se pierden.

## Estructura
```
index.html      # toda la app (HTML, CSS y JavaScript)
manifest.json   # para instalarla como app
icon.svg, icon-192.png, icon-512.png
```

## Próximos pasos
- Backend (Supabase) para cuentas, datos en la nube y directo compartido en tiempo real.
