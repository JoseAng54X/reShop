<div align="center">

# 🎮 reShop Store

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

<table border="0">
  <tr>
    <td width="60%">
      <p><b>reShop</b> We dont Wanted Ads on an Not That Legal WebPage, we can't earn money distributing copies of you know</p>
      <p>¿Why Torrent?<i>We Prefered Torrent</i> Because its more </p>
      <ul>
        <li>⚡ <b>Carga instantánea:</b> Los primeros 200 items están listos en milisegundos.</li>
        <li>🌐 <b>Traducción al vuelo:</b> Motor online para metadatos en múltiples idiomas.</li>
        <li>📱 <b>Multi-plataforma:</b> Diseñado responsivamente para móviles, consolas y escritorio.</li>
      </ul>
    </td>
    <td width="40%" align="center">
      <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbm9oM2p1YTF5a3ZzZ2J0dmxveGZzcXpyaXp6eXp6eXp6eXp6eXp6JnB2PWN2MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/26tn33aiTi1jkl6H6/giphy.gif" width="100%" style="border-radius:12px;" alt="Fast Loading GIF">
    </td>
  </tr>
</table>

---

## 🔥 Características Destacadas

> [!TIP]
> Puedes conectar **reShop** con tu propio catálogo alojando un archivo `manifest.json` y carpetas de *chunks* en cualquier CDN o servicio de alojamiento estático como GitHub Pages.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                             RESHOP ARCHITECTURE                             │
├─────────────────────────────────────────────────────────────────────────────┤
│  [ Manifest JSON ]  ──►  [ Chunk 001.json ] ──► ( Render Inmediato UI )    │
│                     ──►  [ Chunk 002.json ] ──► ( Carga en Segundo Plano )  │
│                     ──►  [ Chunk 003.json ] ──► ( Paginación Dinámica )     │
└─────────────────────────────────────────────────────────────────────────────┘
```

- 🧩 **Smart Ports & Homebrew Categorizer:** Algoritmo de filtrado automático que identifica formatos `.nro` y etiquetas homebrew para separarlos en su propia pestaña dedicada.
- 🌍 **Soporte Multilingüe Dinámico (i18n):** Cambio de idioma instantáneo entre Español e Inglés sin recargar la página.
- 🤖 **Traducción Automática MyMemory:** Los títulos, descripciones y metadatos en ruso u otros idiomas son traducidos en tiempo real al abrir la ficha técnica.
- 📊 **Tracker de Descargas Local:** Contador de clics e interacciones con enlaces Magnet integrado de forma persistente mediante `localStorage`.
- 📦 **Gestor de Catálogo Local y Exportación:** Añade títulos personalizados y exporta el catálogo completo listo para respaldar o distribuir.

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
