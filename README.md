<h1 align="center">Login Web Responsive: HTML, CSS Grid y Media Queries</h1>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-COMPLETADO-green?style=for-the-badge" alt="Estado">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Responsive-Media%20Queries-0560de?style=for-the-badge" alt="Responsive">
</p>

---

## 📑 Índice

- [Descripción del Proyecto](#-descripción-del-proyecto)
- [Estado del Proyecto](#-estado-del-proyecto)
- [Características](#️-características)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Diseño Responsive](#-diseño-responsive)
- [Tecnologías Utilizadas](#️-tecnologías-utilizadas)
- [Acceso y Ejecución](#-acceso-y-ejecución)
- [Desarrollador](#-desarrollador)

---

## 📖 Descripción del Proyecto

Página de inicio de sesión ("Sign In") de **AdminExpress**, desarrollada como tarea académica de **HTML, CSS y Media Queries**. El objetivo fue replicar un diseño dado utilizando únicamente HTML y CSS, con una estructura basada en **CSS Grid** que se adapta a distintos tamaños de pantalla: escritorio, tableta y móvil.

---

## 🚦 Estado del Proyecto

<h4 align="center">
  ✅ Proyecto Finalizado y Funcional ✅
</h4>

---

## ⚙️ Características

- 🧱 **Estructura con CSS Grid:** el diseño principal está dividido en dos columnas (panel azul de marca y panel del formulario), y los campos del formulario también se organizan con Grid.
- 📱 **Totalmente responsive:** el diseño cambia con tres puntos de quiebre usando Media Queries.
- 🎨 **Fiel al diseño original:** panel azul con la marca, formulario centrado, campos con iconos SVG y botón principal en azul.
- 👁️ **Mostrar u ocultar contraseña:** botón con icono de ojo que alterna la visibilidad de la clave con un poco de JavaScript.
- ♿ **Accesible:** etiquetas `label` asociadas a cada campo y foco visible al navegar con teclado.

---

## 📂 Estructura del Proyecto

```text
Login-Web-en-HTML-y-CSS/
├── index.html      # Estructura de la página y formulario
├── estilo.css      # Estilos, CSS Grid y Media Queries
└── README.md       # Documentación del proyecto
```

---

## 📐 Diseño Responsive

| Ancho de pantalla           | Comportamiento                                                                                         |
| --------------------------- | ------------------------------------------------------------------------------------------------------ |
| Más de 1024px (escritorio)  | Dos columnas iguales: panel azul "AdminExpress" y formulario.                                          |
| Hasta 1024px (tableta)      | El panel azul se hace más angosto (`2fr 3fr`).                                                         |
| Hasta 768px (móvil)         | Una sola columna: se oculta el panel azul, el botón ocupa todo el ancho y aparece el enlace "Sign Up". |
| Hasta 400px (móvil pequeño) | Se reducen los márgenes y el tamaño del título.                                                        |

---

## 🛠️ Tecnologías Utilizadas

- **Estructura:** [HTML5](https://developer.mozilla.org/es/docs/Web/HTML) (etiquetas semánticas)
- **Estilos:** [CSS3](https://developer.mozilla.org/es/docs/Web/CSS) (CSS Grid, variables y Media Queries)
- **Fuente:** [Raleway](https://fonts.google.com/specimen/Raleway) (Google Fonts)
- **Control de Versiones:** [Git](https://git-scm.com/) y [GitHub](https://github.com/)

---

## 🚀 Acceso y Ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/ArielGitHuub/Login-Web-en-HTML-y-CSS.git
cd Login-Web-en-HTML-y-CSS
```

### 2. Abrir el proyecto

No se requieren dependencias ni instalación. Puedes hacer doble clic en `index.html` para abrirlo en el navegador, o usar la extensión **Live Server** de VS Code (clic derecho en `index.html` → _Open with Live Server_).

### 3. Probar el diseño responsive

1. Abre la página en el navegador y pulsa `F12`.
2. Activa el modo dispositivo con `Ctrl + Shift + M`.
3. Cambia entre dispositivos o arrastra el borde de la página para ver cómo se adapta.

---

## 👤 Desarrollador

**Ariel Tejada**  
Estudiante de Ingeniería de Software — UDLA