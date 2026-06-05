# 🚀 Guía: Subir Pensiona-T a GitHub y activar GitHub Pages

## Lo que tienes

Este proyecto es un **build de producción de React + Vite**.
Eso significa que ya está compilado y listo — no necesitas instalar nada ni ejecutar `npm run build`.
Solo subes los archivos y GitHub Pages los sirve directamente.

---

## Paso 1 — Crear el repositorio en GitHub

1. Ve a **github.com** e inicia sesión
2. Clic en **"New repository"** (botón verde o ícono `+`)
3. Configura:
   - **Repository name:** `pensionat-landing-page`
   - **Description:** `Landing page React para agencia de asesoría de pensiones IMSS · Vite + Tailwind CSS`
   - Selecciona **Public** ← importante para GitHub Pages gratis
   - NO marques "Add a README" (ya tienes uno)
4. Clic en **"Create repository"**

---

## Paso 2 — Preparar tus archivos

Asegúrate de tener esta estructura exacta en tu computadora:

```
pensionat-landing-page/
├── index.html
├── logo.png
├── assets/
│   ├── index-B6oLtTRO.css
│   └── index-CJa2pQru.js
├── README.md
├── .gitignore
└── SETUP_GUIDE.md  ← puedes borrar este después
```

---

## Paso 3 — Subir los archivos a GitHub

### Opción A — Desde el navegador (sin terminal, más fácil)

1. En tu repo recién creado, clic en **"uploading an existing file"**
2. **Arrastra toda la carpeta** a la ventana
   > ⚠️ Arrastra los archivos **uno por uno o todos juntos**, incluyendo la carpeta `assets/`
3. Escribe el mensaje: `feat: add Pensiona-T landing page (React + Vite build)`
4. Clic en **"Commit changes"**

### Opción B — Con Git (terminal)

```bash
cd pensionat-landing-page

git init
git remote add origin https://github.com/TU-USUARIO/pensionat-landing-page.git

git add .
git commit -m "feat: add Pensiona-T landing page (React + Vite build)"

git branch -M main
git push -u origin main
```

---

## Paso 4 — Activar GitHub Pages

1. En tu repo → pestaña **Settings**
2. Menú izquierdo → **Pages**
3. En "Source" → **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Clic en **Save**
6. Espera 1-3 minutos y recarga

✅ Tu sitio estará en:
**`https://TU-USUARIO.github.io/pensionat-landing-page`**

---

## Paso 5 — Actualizar el README con tu link real

Abre `README.md` y reemplaza:
```
https://tu-usuario.github.io/pensionat-landing-page
```
Por tu URL real (con tu usuario de GitHub).

Haz commit del cambio:
```bash
git add README.md
git commit -m "docs: update live site URL in README"
git push
```

---

## Cómo describir esto en tu CV

```
──────────────────────────────────────────────────────────
Proyectos Freelance
──────────────────────────────────────────────────────────
Landing Page · Pensiona-T IMSS                      2025
React 18 · Vite 5 · Tailwind CSS v4

Diseño y desarrollo de landing page para agencia de
asesoría de pensiones. Enfoque en accesibilidad para
adulto mayor, conversión vía WhatsApp y responsive
design completo.

🔗 github.com/TU-USUARIO/pensionat-landing-page
🌐 TU-USUARIO.github.io/pensionat-landing-page
──────────────────────────────────────────────────────────
```

---

## Tips para que tu perfil destaque

- 📌 **Pinea el repo** en tu perfil de GitHub (Settings → Customize profile → Pin repositories)
- 📸 El README ya tiene el badge con el link en vivo — asegúrate de actualizarlo
- 🔗 Incluye **ambos links** en tu CV: el de GitHub (para ver código) y el sitio en vivo (para el impacto visual)
- 💬 En entrevistas menciona las decisiones técnicas: por qué React, por qué Tailwind, por qué WhatsApp como CTA
