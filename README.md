# Durably Site

Sitio estático mínimo para cumplir los requisitos de publicación en App Store (marketing, soporte y política de privacidad).

## Estructura

- `index.html`: página principal con descripción y beneficios clave.
- `support.html`: contacto, preguntas frecuentes y estado del lanzamiento.
- `privacy.html`: política de privacidad en español e inglés.
- `styles.css`: estilos compartidos.

## Despliegue en GitHub Pages

1. Clona el repositorio `durably-site` recién creado:
   ```bash
   git clone git@github.com:<tu-usuario>/durably-site.git
   cd durably-site
   ```
2. Copia el contenido de `web/durably-site/` dentro del repositorio:
   ```bash
   cp -R ../Durably/web/durably-site/* .
   ```
   Ajusta la ruta de origen si tu clon local está en otra carpeta.
3. Confirma que la estructura final contenga `index.html`, `support.html`, `privacy.html`, `styles.css` y (opcionalmente) este `README.md`.
4. Realiza commit y push:
   ```bash
   git add .
   git commit -m "Add initial Durably static site"
   git push origin main
   ```
5. En GitHub, ve a *Settings → Pages*, selecciona:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
6. Guarda los cambios. GitHub generará la URL pública (`https://<tu-usuario>.github.io/durably-site/`) en unos minutos.

## Siguientes pasos opcionales

- Sustituir el formulario de suscripción por integración real (Beehiiv, Mailchimp, etc.).
- Añadir etiquetas Open Graph y favicon.
- Traducir `index.html` y `support.html` al inglés si lo requiere el plan de marketing.
