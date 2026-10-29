# Falso 9 Landing Page 🚀

Landing page oficial del juego Falso 9.

[![Next.js](https://img.shields.io/badge/Next-JS-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-js-61DAFB?style=for-the-badge&logo=react)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2FE?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)

---

## Tabla de Contenido 📄

- [Descripción](#descripci%C3%B3n)
- [Características Principales](#caracter%C3%ADsticas-principales-%EF%B8%8F)
- [Tecnologías Utilizadas](#tecnolog%C3%ADas-utilizadas-%F0%9F%A7%AE)
- [Instalación](#instalaci%C3%B3n-%E2%9C%A8)
- [Uso](#uso-%EF%B8%8F)
- [Estructura del Proyecto](#estructura-del-proyecto-%F0%9F%97%BA%EF%B8%8F)
- [Contribución](#contribuci%C3%B3n-%E2%9C%8D%EF%B8%8F)
- [Licencia](#licencia-%F0%9F%A7%AE)
- [Enlaces Importantes](#enlaces-importantes-%F0%9F%94%97)

---

## Descripción 📝

La página de aterrizaje oficial para el juego "Falso 9". Este proyecto sirve como portal principal para presentar el juego, destacar sus características y proporcionar a los usuarios formas de interactuar con él, ya sea jugando directamente a través de una integración de `iframe` o descargando la aplicación.

---

## Características Principales 🌟

- **Experiencia Inmersiva:** Una página de inicio visualmente atractiva con imágenes de fondo de alta calidad y animaciones sutiles para captar la atención del usuario.
- **Integración de Juego:** Un `iframe` que permite a los usuarios jugar directamente desde la página web, ofreciendo una experiencia de juego instantánea.
- **Descarga de Aplicación:** Botones de descarga clara para la aplicación móvil (Android) permitiendo a los usuarios tener una experiencia dedicada.
- **Detalles del Juego:** Sección dedicada a enumerar las características clave del juego, como el número de jugadores, la variedad de futbolistas y la opción de elegir impostores.
- **Diseño Responsivo:** Construido con Tailwind CSS y Next.js, asegurando una visualización óptima en todos los dispositivos, desde móviles hasta escritorios.
- **Animaciones Suaves:** Uso de `framer-motion` para añadir transiciones y animaciones fluidas que mejoran la experiencia del usuario.

---

## Tecnologías Utilizadas 🛠️

Este proyecto está construido utilizando un conjunto moderno de tecnologías web:

- **Framework:** [Next.js](https://nextjs.org/) (con Turbopack para desarrollo rápido)
- **Frontend:** [React](https://react.dev/)
- **Estilizado:** [Tailwind CSS](https://tailwindcss.com/) para un diseño eficiente y responsivo.
- **Animaciones:** [Framer Motion](https://www.framer.com/motion/) para animaciones declarativas.
- **TypeScript:** Para un desarrollo robusto y seguro en el lado del cliente.
- **CSS:** Estilos globales y personalizaciones en `app/globals.css`.

---

## Instalación 💾

Sigue estos pasos para configurar el proyecto localmente:

1.  **Clona el Repositorio:**
    ```bash
    git clone https://github.com/PDR1004/Falso9-LandingPage.git
    cd Falso9-LandingPage
    ```

2.  **Instala las Dependencias:**
    Este proyecto utiliza npm para la gestión de paquetes. Asegúrate de tener Node.js y npm instalados.
    ```bash
    npm install
    ```

3.  **Inicia el Servidor de Desarrollo:**
    Para ejecutar el proyecto en modo de desarrollo con Turbopack:
    ```bash
    npm run dev
    ```
    Esto iniciará el servidor en `http://localhost:3000` (o el puerto que Next.js asigne).

---

## Uso 🎮

El proyecto funciona como una página de aterrizaje para el juego "Falso 9". Aquí te explicamos cómo interactuar con él:

1.  **Explorar la Página Principal:** Al visitar la página (`/`), serás recibido con una introducción al juego, el logo, un eslogan y botones de acción.
2.  **Jugar:** Haz clic en el botón "Jugar" para ser redirigido a la página `/juego`, donde encontrarás un `iframe` que carga el juego principal desde `https://falso9juego.vercel.app`.
3.  **Descargar la App:** En la sección "Descargá la App", encontrarás un enlace para descargar el archivo `falso9.apk`, permitiendo la instalación en dispositivos Android.
4.  **Ver Funcionalidades:** Explora la sección "Funcionalidades" para conocer los detalles clave del juego.

**Ejemplo de Interacción:**

-   **Para jugar directamente:** Navega a la página principal y haz clic en el botón **"Jugar"**.
-   **Para descargar la aplicación:** Desplázate hacia abajo hasta la sección "Descargá la App" y haz clic en **"Descargar"**.

---

## Estructura del Proyecto 📁

El proyecto sigue una estructura organizada, típica de una aplicación Next.js:

```
Falso9-LandingPage/
├── app/
│   ├── globals.css       # Estilos CSS globales y de Tailwind CSS
│   ├── layout.tsx        # Layout principal de la aplicación Next.js
│   ├── page.tsx          # Página de inicio (landing page)
│   └── juego/
│       └── page.tsx      # Página que contiene el iframe del juego
├── public/
│   ├── cancha.jpg        # Imagen de fondo para la cabecera
│   ├── Falso_9.logo.png  # Logo del juego
│   ├── app_Falso9.png    # Imagen de la aplicación móvil
│   └── falso9.apk        # Archivo APK para descarga
├── .eslintrc.json      # Configuración de ESLint
├── .gitignore          # Archivos y carpetas a ignorar por Git
├── next.config.ts      # Configuración de Next.js
├── package.json        # Dependencias y scripts del proyecto
├── postcss.config.mjs  # Configuración de PostCSS
├── tsconfig.json       # Configuración del compilador TypeScript
└── eslint.config.mjs   # Configuración de ESLint (formato MJS)
```

---

## Contribución 🤝

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, por favor:

1.  Haz un fork del repositorio.
2.  Crea una nueva rama (`git checkout -b feature/AmazingFeature`).
3.  Realiza tus cambios.
4.  Confirma tus cambios (`git commit -m 'Add some AmazingFeature'`).
5.  Sube la rama (`git push origin feature/AmazingFeature`).
6.  Abre un Pull Request.

Por favor, abre un Issue primero para discutir los cambios que te gustaría implementar.

---

## Licencia ⚖️

Este proyecto no tiene una licencia especificada en el repositorio. Por favor, consulta con el autor para obtener detalles sobre el uso y la distribución.

---

## Enlaces Importantes 🔗

-   **Sitio Web del Juego:** [falso9juego.vercel.app](https://falso9juego.vercel.app/) (Cargado en la página `/juego`)
-   **Repositorio:** [https://github.com/PDR1004/Falso9-LandingPage](https://github.com/PDR1004/Falso9-LandingPage)

---

## Pie de Página 👣

Este proyecto es la página de aterrizaje para "Falso 9".

-   **Repositorio:** [Falso9-LandingPage](https://github.com/PDR1004/Falso9-LandingPage)
-   **Autor:** [PDR1004](https://github.com/PDR1004)
-   **Contacto:** Si tienes alguna pregunta o sugerencia, por favor abre un [Issue](https://github.com/PDR1004/Falso9-LandingPage/issues) en el repositorio.

¡No olvides dar una estrella ⭐, hacer fork 🍴 y revisar este proyecto si te gusta!


---
**<p align="center">Generated by [ReadmeCodeGen](https://www.readmecodegen.com/)</p>**