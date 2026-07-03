# Email marketing · Modelos de caso de estudio (Heroturfs)

Plantillas de email (nurturing) para presentar **proyectos / casos de estudio** de Heroturfs.
Fijo 600 px, sin media queries (se encoge bien en Gmail móvil). Tipografía Oswald + Roboto, marca `#E3332B` / `#323F49`.

## Modelos

- **[caso-armada-cartagena.html](caso-armada-cartagena.html)** — Base de la Armada Española (Cartagena).
  Estructura: hero + franja · cifras · **galería** (con enlace «Ver proyecto») · reto / solución / resultado · ficha del proyecto + botón · escudo a sangre + cita · vídeo (enlaza al reel de Instagram) · bloque de asesoría · footer oficial.

Imágenes en [`heroturfs-armada-assets/`](heroturfs-armada-assets).

## Cómo usarlo en Klaviyo

1. Pega el HTML completo en un **bloque HTML nuevo** en Klaviyo.
2. Sustituye el enlace de baja por el tag real: `{% unsubscribe 'Cancelar suscripción' %}`.
3. **Imágenes:** para el envío real conviene subir las fotos a **Archivos de Shopify** y reemplazar las rutas relativas `heroturfs-armada-assets/...` por las URLs del CDN (así cargan seguro en el cliente de correo).

## Datos reales incluidos

WhatsApp `+34 865 450 295` · Footer: `+34 96 540 38 02` · `info@heroturfs.com` · `www.heroturfs.es` · Instagram/Pinterest oficiales.
