# 🏦 Pensiona-T · Landing Page

> Landing page profesional para agencia de asesoría de pensiones IMSS en México. Desarrollada en React con enfoque en accesibilidad, confianza y conversión para adultos mayores (55–65 años) y sus familias.

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=flat&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-✓-3B6BBA?style=flat)

---

## 🌐 Demo en vivo

👉 **[Ver sitio desplegado](https://pensionart.mx/)**


---

## 🎯 Contexto del proyecto

**Cliente:** Pensiona-T IMSS — Agencia de asesoría de pensiones en San Nicolás de los Garza, N.L.

**Objetivo:** Diseñar y desarrollar una landing page que transmita confianza y profesionalismo para un público adulto mayor y sus hijos, con conversión directa vía WhatsApp.

**Reto de diseño:** El público principal tiene entre 55 y 65 años, por lo que se priorizaron tipografía grande, alto contraste y flujo de información claro sobre recursos puramente decorativos.

---

## ✨ Secciones de la página

- **Header sticky** con logo de alta resolución y botón CTA "Agenda tu Cita"
- **Hero section** con título principal, subtítulo de especialidad IMSS, CTA de WhatsApp y fotografía real
- **Sección "¿Quiénes somos?"** con descripción institucional del equipo
- **Sección de beneficios** en 3 columnas (Cálculo Preciso, Trámites sin complicaciones, Atención Personalizada) con íconos animados
- **Footer completo** con dirección, teléfono, WhatsApp, redes sociales (Facebook, Instagram, TikTok) y Google Maps embebido
- **Botón flotante de WhatsApp** (sticky FAB) con animación pulse
- **Diseño totalmente responsive** para móvil, tablet y escritorio

---

## 🎨 Paleta de colores

| Color | Hex | Uso |
|---|---|---|
| Azul principal | `#3B6BBA` | Botones, CTAs, detalles interactivos |
| Rojo Tinto | `#6D2A2A` | Títulos, énfasis de marca |
| Oro/Oliva | `#9A8A42` | Íconos, acentos decorativos |
| Fondo | `#FFFFFF` | Máxima legibilidad |
| Footer | `#0F172A` (slate-900) | Contraste nocturno |

---

## 🛠️ Tecnologías utilizadas

- **React 18** — Componente funcional principal (`App.jsx`)
- **Vite 5** — Bundler y servidor de desarrollo
- **Tailwind CSS v4** — Estilos utilitarios, responsive design
- **Lucide React** — Librería de íconos (Calendar, MessageCircle, Users, etc.)
- **Google Maps Embed API** — Mapa interactivo en el footer
- **Unsplash** — Fotografía del hero (adulto mayor hispano)

---

## 📁 Estructura del repositorio

```
pensionat-landing-page/
├── index.html              # Entry point de la app React
├── logo.png                # Logo oficial de Pensiona-T (1600×747 px, PNG)
├── assets/
│   ├── index-[hash].css    # Estilos compilados (Tailwind + componentes)
│   └── index-[hash].js     # Bundle de React compilado (Vite)
└── README.md
```

> **Nota:** Este repositorio contiene el **build de producción** generado por Vite.
> El código fuente original (`.jsx`, `tailwind.config`) no se incluye por confidencialidad del cliente.

---

## 🚀 Ver localmente

No requiere instalación. Al ser un build estático de Vite:

```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/pensionat-landing-page.git
cd pensionat-landing-page

# Opción 1: Abre directo en el navegador
open index.html

# Opción 2: Usa un servidor local (recomendado para evitar problemas de CORS)
npx serve .
# Luego visita http://localhost:3000
```

---

## ⚙️ Decisiones técnicas

| Decisión | Justificación |
|---|---|
| **React + Vite** | Desarrollo rápido, componentes reutilizables, build optimizado |
| **Tailwind CSS v4** | Estilos inline sin CSS custom, purga automática, responsive trivial |
| **WhatsApp como CTA principal** | Canal de mayor tasa de conversión para el nicho de adultos mayores en México |
| **Google Maps Embed** | Confianza inmediata en el negocio físico al mostrar ubicación verificada |
| **Logo en alta resolución** | 1600×747 px asegura nitidez en pantallas retina |
| **Tipografía `font-extrabold` grande** | Accesibilidad para adultos mayores con problemas de visión |

---

## 📱 Responsive Design

| Dispositivo | Comportamiento |
|---|---|
| **Móvil** (`< md`) | Layout en una columna, botón WhatsApp oculto en nav, hero apilado |
| **Tablet** (`md`) | Grid 2 columnas en hero, beneficios en 3 cols |
| **Desktop** (`lg+`) | Layout completo, logo extra grande en header |

---

## 👤 Autor

**Humberto Alejandro Vargas Sanchez**  
Estudiante de Ingeniería en Tecnologías Computacionales · UDEM  
Freelance Frontend Developer

[![GitHub](https://img.shields.io/badge/GitHub-tu--usuario-181717?style=flat&logo=github)](https://github.com/Betito016)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tu--perfil-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/humberto-alejandro-vargas-s%C3%A1nchez-6aa07b20b/)

---

## 📄 Licencia

Desarrollado como proyecto freelance para Pensiona-T IMSS.  
El código se comparte con fines de portafolio. El logo y los activos visuales son propiedad de Pensiona-T IMSS.
