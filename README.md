# 🏎️ Invitaciones Digitales — JR Digital Solutions

Repositorio centralizado para invitaciones interactivas de alta gama.

## 🚀 Proyectos Activos

### 1. Neythan Hernández Ramirez (4 Años)
Invitación temática de **Carreras / Piston Cup**.
- **URL:** [https://jrodri22.github.io/Invitacion/neythan/](https://jrodri22.github.io/Invitacion/neythan/)
- **Características:** Semáforo interactivo, auto-scroll cinematográfico, música sincronizada y diseño anti-AI-generic.

### 2. Sharon Rodríguez (1 Año)
Invitación temática **Coquette / Lazos / Baby Girl**.
- **URL:** [https://jrodri22.github.io/Invitacion/sharon/](https://jrodri22.github.io/Invitacion/sharon/)
- **Características:** Estética delicada, animaciones suaves y RSVP integrado.

---

## 🛠️ Stack Tecnológico (Estándar)

- **Framework:** React 18+ / Vite
- **Lenguaje:** TypeScript
- **Estilos:** Tailwind CSS
- **Animaciones:** GSAP (GreenSock Animation Platform)
- **Despliegue:** GitHub Pages (Subcarpetas por proyecto)

## ⚙️ Guía de Configuración

Para cada proyecto, todo el contenido editable se encuentra en:
`src/config/invitation.ts`

| Dato | Campo | Descripción |
|---|---|---|
| **Datos Básicos** | `name`, `age`, `date`, `time` | Información principal del cumpleañero y evento. |
| **Ubicación** | `locationName`, `address`, `mapsUrl` | Detalles del lugar y enlaces a Google Maps. |
| **RSVP** | `rsvp.whatsappNumber` | Número de teléfono para recibir confirmaciones. |
| **Multimedia** | `photos`, `music.youtubeVideoId` | Galería de imágenes y música de fondo. |
| **Textos** | `texts.*` | Todos los mensajes personalizados de la invitación. |

## 🚀 Flujo de Despliegue (Deployment)

Para agregar una nueva invitación o actualizar una existente:

1. **Build:** Ejecutar `npm run build` en la carpeta del proyecto.
2. **Ruta:** Configurar `base: '/Invitacion/nombre-proyecto/'` en `vite.config.ts`.
3. **Subida:** Copiar el contenido de la carpeta `dist/` a la subcarpeta correspondiente en este repositorio:
   `Invitacion/nombre-proyecto/`
4. **Push:** Hacer commit y push a la rama `main`.

---
*Desarrollado por Jorge Rodríguez · JR Digital Solutions 🇨🇷*