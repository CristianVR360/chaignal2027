# Parcelas Chaignal - Sitio Web

Sitio web oficial de **Parcelas Chaignal** (Malalhue, Región de Los Ríos).

Este sitio es una landing page estática moderna (HTML, CSS y JavaScript nativo) con el Masterplan 360 incrustado directamente desde la plataforma externa Astra 360.

## Master Plan 360

El master plan se gestiona y sirve de forma centralizada en:
[https://masterplan.astra360.cl/projects/parcelas-chaignal/index.html](https://masterplan.astra360.cl/projects/parcelas-chaignal/index.html)

## Estructura del Proyecto

```text
├── index.html              # Landing page principal
├── css/
│   └── styles.css          # Estilos del sitio web
├── assets/
│   ├── Brochure-Parcelas-Chaignal.pdf
│   ├── actividades/        # Imágenes de actividades
│   └── atractivos/         # Imágenes de atractivos turísticos
├── img/
│   ├── logo/               # Logotipos oficiales
│   ├── portfolio/          # Fotografías del proyecto y héroe
│   ├── svg/                # Iconos vectoriales
│   ├── thumbVideo/         # Miniatura para la sección de video
│   └── favicon.png         # Favicon del sitio
├── package.json            # Configuración del proyecto estático
└── README.md
```

## Visualización y Desarrollo Local

No se requiere `npm install` ni instalación de dependencias en `node_modules`.

Para abrir localmente:
- Puedes abrir directamente `index.html` en cualquier navegador web, o
- Puedes iniciar un servidor local rápido ejecutando:
  ```bash
  npm start
  ```
  *(o `npx serve .`)*
