# geramaargonzalez.github.io

Portfolio personal de **Gerardo González** — NetSuite Administrator · Developer · Data & AI, desplegado en [GitHub Pages](https://pages.github.com/).

## 🌐 Sitio en vivo

[https://geramaargonzalez.github.io](https://geramaargonzalez.github.io)

## 📋 Descripción

Este repositorio contiene el código fuente de mi sitio web personal y portfolio profesional. Está construido íntegramente con **HTML, CSS y JavaScript vanilla** (sin frameworks ni dependencias externas), lo que lo hace liviano, rápido y fácil de mantener.

El sitio presenta mi perfil profesional como especialista en NetSuite, desarrollo de integraciones y análisis de datos, con un foco especial en la formación académica en Ciencia de Datos e IA (UTEC + MIT).

## 🗂️ Estructura del proyecto

```
geramaargonzalez.github.io/
├── index.html      # Página principal con todas las secciones del portfolio
├── style.css       # Estilos completos (variables, layout, componentes, responsive)
├── script.js       # Funcionalidades JavaScript del sitio
└── assets/
    ├── profile.jpg # Foto de perfil
    └── CV.pdf      # Currículum descargable
```

## 📄 Secciones del sitio

### 1. Navbar
Barra de navegación fija con logo, enlaces a cada sección y menú hamburguesa para móvil. Se añade sombra automáticamente al hacer scroll.

### 2. Hero
Sección principal con foto de perfil, nombre, título profesional, descripción breve, ubicación (Montevideo, Uruguay) y botones de acción para navegar a proyectos, descargar CV o ir a contacto. Incluye badge de la especialización académica UTEC + MIT.

### 3. Sobre mí
Descripción ampliada del perfil profesional: experiencia en NetSuite, habilidades de desarrollo (SuiteScript, JavaScript, Python), orientación analítica y la especialización en curso en Ciencia de Datos e Inteligencia Artificial. Incluye una tarjeta destacada con la información académica.

### 4. Skills & Stack
Skills agrupadas en cuatro categorías:
- **ERP & NetSuite**: NetSuite, SuiteScript 2.x, SuiteFlow, SuiteTalk (SOAP/REST), NetSuite Administration
- **Desarrollo**: JavaScript, Node.js, Python, REST APIs, SQL, HTML/CSS
- **Data & AI**: Machine Learning, Inteligencia Artificial, Análisis de Datos, Python (Pandas, NumPy), SQL Analytics
- **Integraciones & Herramientas**: Git/GitHub, Postman, VS Code, Automation

### 5. Proyectos destacados
Grilla de tarjetas con seis proyectos profesionales/personales:
1. **NetSuite Integration Hub** — Plataforma modular de integración con APIs REST (Node.js, SuiteScript)
2. **Sales Dashboard Analytics** — Dashboard de análisis de ventas y forecasting (Python, Pandas, SQL)
3. **AutoFlow — Process Automation** — Motor de automatización de procesos en NetSuite (SuiteScript 2.x, SuiteFlow)
4. **ML Classifier — Transacciones** — Modelo de clasificación supervisada para transacciones financieras (scikit-learn)
5. **API Gateway — ERP Connector** — Microservicio gateway con OAuth 2.0 (Node.js, REST API)
6. **Data Pipeline — ETL NetSuite** — Pipeline ETL para extraer y cargar datos en un data warehouse (Python, SQL)

### 6. Experiencia
Timeline cronológico con los roles profesionales más relevantes, desde Desarrollador Junior (2017) hasta NetSuite Administrator & Developer (2022–presente).

### 7. Educación & Certificaciones
Tarjetas de formación académica, incluyendo la **Especialización en Ciencia de Datos e Inteligencia Artificial — UTEC + MIT** (2024, en curso), formación técnica en sistemas y certificaciones de NetSuite.

### 8. Contacto
Tarjetas de contacto con email, LinkedIn, GitHub y ubicación.

### Footer
Pie de página con nombre, descripción breve y año dinámico generado con JavaScript.

## ✨ Funcionalidades técnicas (`script.js`)

- **Año dinámico**: el footer muestra siempre el año actual.
- **Navbar con sombra al scroll**: se activa automáticamente al desplazarse más de 20 px.
- **Menú mobile**: botón hamburguesa que abre/cierra el menú en pantallas pequeñas, con bloqueo de scroll del body.
- **Enlace activo en navbar**: resalta la sección actualmente visible usando `IntersectionObserver`.
- **Scroll suave**: implementado como fallback para navegadores que no lo soporten de forma nativa.

## 🎨 Diseño (`style.css`)

- Variables CSS centralizadas para colores, tipografía y espaciado (fácil personalización).
- Paleta: azul oscuro (`#1e3a5f`) como acento principal y violeta suave (`#6366f1`) como acento secundario.
- Layout responsive con breakpoints para tablet y móvil.
- Componentes reutilizables: botones (`btn`), tags, tarjetas de proyecto, timeline, tarjetas de educación y contacto.

## 🚀 Ejecución local

Clona el repositorio y abre `index.html` en el navegador, o usa un servidor local:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

Luego visita `http://localhost:8000`.

## 🚢 Despliegue

El sitio se despliega automáticamente en **GitHub Pages** con cada push a la rama `main`. No requiere configuración adicional de CI/CD.

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).
