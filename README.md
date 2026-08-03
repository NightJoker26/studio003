# Studio 003 — Sitio web

Retratos al óleo personalizados. Sitio de una sola página, sin dependencias ni servidor: solo `index.html`.

## 📁 Qué hay en la carpeta

```
studio003/
├─ index.html      ← el sitio completo (no necesita nada más)
├─ galeria/        ← aquí van las fotos de tus trabajos
│   └─ LEEME.txt   ← instrucciones para agregar fotos
└─ README.md       ← este archivo
```

## 🖼️ Agregar fotos a la galería (lo más fácil)

Sube tus imágenes a la carpeta **`galeria/`** con nombres numerados:

```
1.jpg   2.jpg   3.jpg   4.jpg   ...
```

La página las muestra solas, en orden. No dejes huecos en la numeración.
Sirven `.jpg`, `.jpeg`, `.png` y `.webp`. (Más detalles en `galeria/LEEME.txt`.)

## 📸 Cambiar tu usuario de Instagram

Abre `index.html` y busca (Ctrl/Cmd + F) esta dirección:

```
https://instagram.com/studio003
```

Aparece **2 veces** (el botón de cotización y el footer). Reemplaza `studio003` por tu usuario real en ambas.

## 🚀 Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `studio003`).
2. Sube **el contenido** de esta carpeta al repo (que `index.html` quede en la raíz, no dentro de otra subcarpeta).
3. En el repo ve a **Settings → Pages**.
4. En **Branch** elige `main` y la carpeta `/ (root)`, y guarda.
5. Espera ~1 minuto. Tu sitio quedará en:
   `https://TU-USUARIO.github.io/studio003/`

Cada vez que subas una foto nueva a `galeria/`, se actualizará sola en el sitio.

## ✏️ Editar textos o precios

Todo el contenido está en `index.html`, en español y bien señalizado.
Los precios y tamaños están en la sección **Cotización** (busca `Q300` o `30 × 40`).
