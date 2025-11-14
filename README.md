CV Modular en React – Actividad SENA

Proyecto desarrollado para la actividad GA1-220501096-03-AA1-EV05: Construcción de un CV modular en React, aplicando el enfoque de componentes funcionales anidados y el control de versiones con Git y GitHub.

📌 Descripción del Proyecto

Este proyecto consiste en la creación de una hoja de vida digital completamente modularizada con React + Vite.
Cada sección del CV se construyó como un componente independiente, permitiendo reutilización, orden y mantenimiento eficiente del código.

Estructura general del proyecto:

CabeceraCV → Información personal y título principal.

Perfil → Descripción del perfil profesional.

Experiencia → Historial laboral o experiencia previa.

Educacion → Formación académica y cursos complementarios.

Todos los componentes están organizados dentro de la carpeta:

src/components/

🛠 Tecnologías Utilizadas

React (Componentes funcionales)

Vite

JSX

CSS

Node.js (para entorno de desarrollo)

Git y GitHub (control de versiones)

📂 Estructura del Proyecto
src/
 ├── components/
 │    ├── CabeceraCV.jsx
 │    ├── Perfil.jsx
 │    ├── Experiencia.jsx
 │    └── Educacion.jsx
 │
 ├── App.jsx
 ├── main.jsx
 ├── App.css
 └── index.css

▶️ Ejecución del Proyecto

Para ejecutar este proyecto en local:

npm install
npm run dev


Abrir en el navegador la URL generada por Vite (generalmente http://localhost:5173
).

📝 Commits Realizados

Se realizaron commits organizados por componente, siguiendo buenas prácticas de versionado:

feat: componente CabeceraCV con datos personales

feat: componente Perfil con descripción profesional

feat: componente Experiencia con historial laboral

feat: componente Educacion con formación académica

feat: estructura principal App.jsx con componentes anidados

docs: agregar README actualizado

docs: agregar captura de pantalla del proyecto

📸 Captura del Resultado Final

A continuación se incluye la captura del CV completo ejecutándose en el navegador:

![Vista previa](<CAPTURAS/CV EN REACT.png>)

Asegúrate de colocar tu propia captura en la raíz del proyecto como screenshot.png.

✔️ Estado del Proyecto

Proyecto completado y funcional según los requerimientos de la actividad.
La estructura está modularizada, el control de versiones se realizó correctamente y el despliegue local se ejecuta sin errores.