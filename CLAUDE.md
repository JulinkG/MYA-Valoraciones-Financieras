# MYA Valoraciones Financieras — sitio web

Sitio de una sola página para el despacho de consultoría financiera MYA Valoraciones Financieras (Oaxaca, México). Todo el contenido está en español.

## Publicación
- Repositorio: github.com/JulinkG/MYA-Valoraciones-Financieras (rama `main`).
- Hosting: GitHub Pages desde `main` / root → https://julinkg.github.io/MYA-Valoraciones-Financieras/
- Cualquier push a `main` se publica solo en 1–2 minutos. `.nojekyll` evita que GitHub procese los archivos.

## Archivos
- `index.html`: sitio completo (HTML + CSS + JS en un solo archivo, sin dependencias de build).
- `privacidad.html`: aviso de privacidad integral (LFPDPPP vigente desde 2025), enlazado desde el pie y desde el formulario.

## Decisiones de contenido
- **No** incluir información personal de los socios (nombres, semblanzas, fotos). Lo pidió el cliente.
- Contacto: correos julianmenachavez@gmail.com y paris.eaac@gmail.com; teléfono y WhatsApp de Esteban: +52 951 276 3038.
- Sin precios publicados: tras el diagnóstico se envía propuesta con precio cerrado.
- Primera sesión de diagnóstico (45 min) sin costo.
- No inventar cifras, clientes ni testimonios.

## Formulario
- Envía vía FormSubmit (AJAX) a `https://formsubmit.co/ajax/julianmenachavez@gmail.com`. Copia a paris.eaac@gmail.com con el campo oculto `_cc`. Requiere activación única desde el correo.
- Campos: Nombre, Empresa, email, Teléfono, Servicio (radio), Mensaje; honeypot `_honey`.

## Sistema de diseño (estilo editorial monocromo con un solo acento)
- Colores: tinta #0c0a08, fondo hueso #f4f2f0, tarjetas #ffffff, bordes #e5e7eb, texto secundario #6d6c6b, paneles oscuros #1a1919, acento amarillo #e4f222 **solo** en botones de acción y estados activos.
- Tipografía: IBM Plex Sans (sustituto de lausanne) en peso 400 únicamente; jerarquía por tamaño (64/48/40/28/24/20/16), `font-feature-settings: "ss01"`. Etiquetas pequeñas en mayúsculas a 10px con tracking positivo.
- Radios: botones y etiquetas 6px, inputs 10px, tarjetas de fondo 12px, tarjetas 16px. Sin sombras: la elevación se hace con bordes de 1px.
- Todo alineado a la izquierda, ancho máximo 1200px, sin ilustraciones ni fotos de stock.
- Debe funcionar en celular (breakpoint 760px).
