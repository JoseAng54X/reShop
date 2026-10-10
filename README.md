<div align="center">

# reShop HB Store

<p align="center">
  <img src="https://raw.githubusercontent.com/JoseAng54X/reShop/main/catalog_chunks/banner.png" alt="reShop Banner" width="100%" style="border-radius: 12px; margin-bottom: 20px;">
</p>

### **An 🏴‍☠️ Store Webpage for N1NT$ND@ SW1+CH.**

*Explore a Massive Catalog Of Games, +8000 Games That U can download with a torrent, without ads.*

---

[![GitHub Stars](https://img.shields.io/github/stars/JoseAng54X/reShop?style=for-the-badge&logo=github&color=FF5722)](https://github.com/JoseAng54X/reShop/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/JoseAng54X/reShop?style=for-the-badge&logo=github&color=orange)](https://github.com/JoseAng54X/reShop/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)

</div>

---

> [!NOTE]
> **reShop** is an web client, We use an catalog fetched from @langegen/switch_games, We dont Own Those Copies.

---

## ¿Why Without Ads?

# In reshop we Dont Want to earn Money distributing not that Legal Copies of You Know

We made it Fully Free besarse of Fear of Getting deleted by Some _SW1TC+ G4M$S_

# It uses Torrent, If the Page Got deleted, you can download The json on langeges repo and Start Download searching an magnet.

We Are Making an Fully _C++ HomeBrew App_ to Connect the web with your console :}.

---

## Some Cool Things About this:

> [!TIP]
> You Can Connect reShop to an External ```Json Catalog``` and The page would Load it if it have this structure:

```{
  "title": "Cool game [NSZ/NSP/XCI]",
  "size": "442.3 MB",
  "magnet": "magnet:?xt=urn:btih:1718E610...",
  "topic_id": :03939393",
  "url": "https://coolgameurl.com/2727...",
  "year": "2025, February",
  "genre": "Action, Role-Playing, Beatemup",
  "developer": "CoolDeveloper",
  "publisher": "CoolPublisher",
  "image_format": ".NSZ/NSP/XCI",
  "interface_lang": "[RUS / ENG / Multi 10]",
  "voice_lang": "English",
  "performance": "(FW 2.5.0 / Atmosphere 1.11.2)",
  "multiplayer": "No",
  "cover": "https://i7.imageban.ru/out/...",
  "screenshots": ["https://i128.fastpic.org/thumb/..."],
  "description": "Place a thing there...",
  "title_id": "01003CB02246E000"
}
```
---

## 🛠️ Vista Previa de la Interfaz

<details>
<summary>📸 <b>Haz clic aquí para desplegar las capturas de pantalla de la aplicación</b></summary>

<br>

| Catálogo Principal (Light Mode) | Ficha de Detalle / Magnet |
| :---: | :---: |
| <img src="https://images.unsplash.com/photo-1550745165-9bc0b252726f?w=600&auto=format&fit=crop&q=80" width="100%" style="border-radius:8px;"> | <img src="https://images.unsplash.com/photo-1612287230202-1ff1d85d1bdf?w=600&auto=format&fit=crop&q=80" width="100%" style="border-radius:8px;"> |

| Navegación Móvil | Gestión & Ajustes |
| :---: | :---: |
| <img src="https://images.unsplash.com/photo-1526738549149-8e07eca6c147?w=600&auto=format&fit=crop&q=80" width="100%" style="border-radius:8px;"> | <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?w=600&auto=format&fit=crop&q=80" width="100%" style="border-radius:8px;"> |

</details>

---

## 🚀 Inicio Rápido

> [!IMPORTANT]
> No requiere instalación de Node.js, compilación de paquetes ni servidores backend activos. **Es 100% estático.**

### Opción 1: Ejecución Directa

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/JoseAng54X/reShop.git
   cd reShop
   ```
2. **Abre el archivo:**
   Simplemente haz doble clic en `reshop_store.html` para abrirlo en Chrome, Firefox, Edge o Safari.

### Opción 2: Servidor Local (Recomendado para evitar bloqueos CORS)

> [!WARNING]
> Algunos navegadores pueden restringir la lectura de archivos JSON locales (`file://`). Se recomienda usar un servidor HTTP liviano:

```bash
# Usando npx (Node.js)
npx serve .

# O usando Python 3
python -m http.server 8000
```

Navega a `http://localhost:8000/reshop_store.html` ¡y listo!

---

## ⚙️ Estructura del Manifiesto JSON (`manifest.json`)

Para adaptar tus propios catálogos a reShop, tu archivo `manifest.json` debe seguir esta estructura:

```json
{
  "total_items": 12500,
  "chunks": [
    { "file": "chunk_1.json", "items": 200 },
    { "file": "chunk_2.json", "items": 200 },
    { "file": "chunk_3.json", "items": 200 }
  ]
}
```

> [!CAUTION]
> Asegúrate de habilitar los encabezados **CORS** (`Access-Control-Allow-Origin: *`) si alojas los archivos JSON en un servidor o CDN externo.

---

## 🧰 Tecnologías y Librerías

| Tecnología | Descripción | Uso en el Proyecto |
| :--- | :--- | :--- |
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white) | **HTML5 Semántico** | Estrategia de maquetación limpia en un solo archivo. |
| ![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white) | **Tailwind CSS (CDN)** | Utilidades de estilo responsive, animaciones y temas. |
| ![JS](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) | **JavaScript ES6+** | Peticiones asíncronas (`fetch`), paginación y manejo de estado. |
| ![FontAwesome](https://img.shields.io/badge/-FontAwesome-528DD7?logo=fontawesome&logoColor=white) | **FontAwesome 6** | Iconografía vectorizada para componentes de la UI. |
| ![Google Fonts](https://img.shields.io/badge/-Google_Fonts-4285F4?logo=google&logoColor=white) | **Urbanist & Roboto** | Tipografías modernas para lectura y diseño de logotipos. |

---

## 🤝 Contribuciones e Ideas

¡Las contribuciones son lo que hacen a la comunidad de código abierto un lugar increíble para aprender, inspirar y crear! Cualquier contribución que hagas será **muy apreciada**.

1. Haz un **Fork** del proyecto.
2. Crea tu Rama de Feature (`git checkout -b feature/NuevaCaracteristica`).
3. Haz Commit de tus Cambios (`git commit -m 'Add: Nueva Caracteristica'`).
4. Haz Push a la Rama (`git push origin feature/NuevaCaracteristica`).
5. Abre un **Pull Request**.

---

<div align="center">

Desarrollado con ❤️ por [JoseAng54X](https://github.com/JoseAng54X)

⭐ **¿Te sirvió el proyecto? ¡No olvides darle una estrella en GitHub!** ⭐

</div>
