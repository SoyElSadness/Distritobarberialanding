# Distrito Barbería

Sitio estático de Distrito Barbería. La página principal y las pantallas del flujo de reserva están en `DistritoBarberialanding/`; no se requiere Node.js, un proceso de compilación ni un servidor backend.

## Publicación en GitHub Pages

El workflow de GitHub Actions en `.github/workflows/pages.yml` publica el sitio automáticamente al hacer push a `main` y también se puede ejecutar manualmente desde **Actions**. En el repositorio, selecciona **Settings → Pages → Build and deployment → GitHub Actions** como origen.

La URL raíz redirige a la página principal conservando las rutas relativas, tanto en un dominio personalizado como en la URL de proyecto de GitHub Pages. Las páginas de reserva siguen disponibles en sus carpetas originales.

## Reservas

El formulario de la página principal prepara la solicitud y la abre en WhatsApp; GitHub Pages solo aloja archivos estáticos y no guarda citas ni envía mensajes por sí mismo. Tailwind, las fuentes y algunas imágenes se cargan desde servicios externos, por lo que requieren conexión a internet.

Para probar la página localmente, abre `DistritoBarberialanding/distrito_barber_a_landing_page_animada_microinteracciones/Main.html` en un navegador.
