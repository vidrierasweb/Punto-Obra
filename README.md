# PUNTO OBRA | Demo web

Sitio web demostrativo para un corralón de materiales de construcción, creado como proyecto de portfolio de **[Vidrieras Web](https://github.com/vidrierasweb)**.

La propuesta combina una estética industrial —grafito, tonos claros y naranja de seguridad— con un catálogo interactivo y una forma sencilla de preparar solicitudes de presupuesto.

> **Importante:** Punto Obra es una demo. Los productos, precios, imágenes y datos comerciales son ilustrativos; no representan una oferta comercial real.

## Funcionalidades

- Diseño responsive para computadoras, tablets y celulares.
- Navegación adaptable con menú móvil.
- Sección de categorías de materiales.
- Catálogo con búsqueda, filtro por categoría y orden alfabético.
- Fichas de productos con unidad de venta y precio ilustrativo o consulta de precio.
- Lista de presupuesto: agregar productos, modificar cantidades y quitar artículos.
- Formulario de consulta que prepara el pedido para enviarlo por WhatsApp.
- Secciones de servicios, presentación del negocio, preguntas frecuentes y contacto.
- Datos de contacto y enlaces configurables desde un único objeto.
- Animaciones sutiles, estados de foco visibles y soporte para preferencias de movimiento reducido.

## Tecnologías

- HTML5
- CSS3
- JavaScript vanilla
- Sin frameworks ni backend
- Preparado para publicarse como sitio estático con GitHub Pages

## Publicar con GitHub Pages

1. Confirmá que el archivo principal se llame `index.html` y esté en la raíz del repositorio.
2. Entrá a **Settings → Pages**.
3. En **Build and deployment**, seleccioná **Deploy from a branch**.
4. Elegí la rama `main` y la carpeta `/(root)`, y guardá.
5. Cuando GitHub termine de publicar el sitio, la URL esperada es:

   `https://vidrierasweb.github.io/Punto-Obra/`

La URL estará disponible una vez que GitHub Pages quede habilitado y complete el despliegue.

## Personalización

Abrí `index.html` y buscá el bloque `CONFIG` dentro del `<script>`. Allí podés configurar:

- `nombre`: nombre del negocio.
- `whatsapp`: número con código de país, solo dígitos. Ejemplo de formato: `5491122334455`.
- `telefono`: teléfono visible.
- `instagram`: URL completa del perfil.
- `direccion` y `horarios`: datos del local.
- `maps`: enlace de Google Maps.
- `vidrieras` y `vidriorasContacto`: enlaces de Vidrieras Web.

Los enlaces de contacto que no estén configurados se ocultan o desactivan según el componente. Antes de usar la web con un negocio real, completá los datos y verificá todos los enlaces.

### Editar categorías y productos

- `CATEGORIAS`: nombres, descripciones e imágenes de las categorías.
- `PRODUCTOS`: catálogo, descripción, unidad de venta, categoría, imagen y precio.
- Un precio numérico se muestra como **ilustrativo**. Si el precio es `null`, se muestra **Consultar precio**.
- Reemplazá las imágenes de ejemplo por imágenes propias o con licencia adecuada para el uso previsto.

## Probar antes de compartir

- Buscar productos y filtrar por categoría.
- Agregar artículos a la lista, cambiar cantidades y eliminarlos.
- Completar nombre y localidad.
- Configurar un número de WhatsApp de prueba y comprobar el mensaje generado.
- Revisar el menú y el diseño en pantalla chica.
- Confirmar que dirección, horarios, redes y mapa correspondan al negocio real.

## Créditos

Proyecto de demostración realizado por **[Vidrieras Web](https://github.com/vidrierasweb)** para mostrar cómo una presencia web puede ayudar a presentar productos y recibir consultas.
