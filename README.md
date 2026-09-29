# Nexo — Plantilla de sitio institucional

Plantilla multipágina desarrollada con Astro y Tailwind CSS para crear sitios institucionales rápidos, claros y fácilmente personalizables.

Este proyecto representa uno de los productos digitales ofrecidos: una base lista para adaptar a empresas, profesionales y negocios que necesitan una presencia web moderna, responsive y orientada a generar consultas.

## Características

- Arquitectura basada en componentes reutilizables de Astro.
- Diseño responsive con Tailwind CSS.
- Página principal con presentación, servicios, newsletter y contacto.
- Página independiente de contacto.
- Página de puntos de venta con integración opcional de Google Maps.
- Servicios y locales gestionados mediante archivos JSON.
- Integración con WhatsApp y Formspree mediante variables de entorno.
- Generación estática para obtener sitios rápidos y simples de desplegar.

## Tecnologías

- Astro
- Tailwind CSS
- JavaScript del lado del cliente
- Google Maps API
- Formspree

## Estructura

- `src/pages/`: páginas y rutas del sitio.
- `src/components/`: componentes reutilizables de la interfaz.
- `src/data/`: información editable de servicios y puntos de venta.
- `src/styles/`: estilos globales y configuración visual.

## Configuración

Crear un archivo `.env` en la raíz del proyecto:

```env
LOCAL_GOOGLE_MAPS_API_KEY=tu_api_key
LOCAL_WHATSAPP_NUMBER=5492210000000
LOCAL_FORMSPREE_ENDPOINT=https://formspree.io/f/tu_endpoint
```

Las integraciones externas son opcionales. Si no se configura la API de Google Maps, el sitio mostrará un mensaje alternativo en la sección de puntos de venta.

## Uso

```bash
npm install
npm run dev
npm run build
npm run preview
```

La plantilla está orientada a ofrecer sitios institucionales rápidos, claros y fácilmente personalizables mediante componentes, datos JSON y clases utilitarias de Tailwind.
