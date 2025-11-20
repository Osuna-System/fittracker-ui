# FitTracker - Workout Management 🏋️‍♂️

## 📋 Descripción del Proyecto

**Actividad:** GA1-220501096-03-AA1-EV09 – Implementación de interfaz gráfica – Maquetación web con HTML y CSS según prototipo FitTracker

Maquetación web profesional del sistema FitTracker - Workout Management, desarrollada con HTML5 semántico y CSS3 utilizando Flexbox y Grid Layout.

## 🎯 Objetivos Cumplidos

- ✅ **Maquetación fiel** al diseño del prototipo
- ✅ **HTML semántico** con etiquetas adecuadas
- ✅ **CSS organizado** y mantenible
- ✅ **Diseño responsive** (mobile-first)
- ✅ **Accesibilidad** y usabilidad
- ✅ **Estructura de carpetas** organizada

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos y diseño
- **Flexbox** - Layout components
- **CSS Grid** - Sistema de calendario
- **Metodología BEM** - Organización de CSS
- **Design System** - Variables CSS consistentes

## Captura del Proyecto

![alt text](<Captura de pantalla 2025-11-20 035423.png>)

## 📁 Estructura del Proyecto

fittracker-ui/
├── index.html # Página principal
├── styles/
│ ├── main.css # Estilos principales y variables
│ ├── components.css # Componentes específicos
│ └── responsive.css # Media queries y responsive
├── assets/
│ ├── fonts/ # Fuentes personalizadas
│ ├── icons/ # Iconos del sistema
│ ├── images/ # Imágenes y gráficos
│ └── videos/ # Videos demostrativos
└── templates/ # Otras páginas (futuras)

## 🚀 Características Implementadas

### 📅 **Calendar System**

- Vista mensual del calendario de entrenamientos
- Días de la semana con headers semánticos
- Slots de workouts con colores diferenciados
- Día actual destacado visualmente
- Navegación entre vistas (Week/Day)

### 🏋️ **Workout Management**

- Tarjetas de workouts próximos
- Información de fecha y hora
- Categorías de entrenamiento:
  - **Upper Body** (Cuerpo superior)
  - **Grade** (Calificaciones)
  - **IMT** (Entrenamiento específico)
  - **Log Day** (Día de registro)

### 🎨 **Design System**

:root {
--primary-color: #007bff;
--secondary-color: #6c757d;
--success-color: #28a745;
--warning-color: #ffc107;
--danger-color: #dc3545;
--light-color: #f8f9fa;
--dark-color: #343a40;
}
💻 Cómo Ejecutar el Proyecto
Opción 1: Servidor Local
bash

# Navegar al directorio del proyecto

cd fittracker-ui

# Abrir en el navegador (si tienes Python)

python -m http.server 8000

# O simplemente abrir index.html en el navegador

open index.html
Opción 2: Live Server (VS Code)
Instalar extensión "Live Server"

Click derecho en index.html

Seleccionar "Open with Live Server"

Opción 3: Servidor HTTP Simple
bash

# Con Node.js (si tienes http-server instalado)

npx http-server

# Con PHP

php -S localhost:8000
📱 Responsive Design
El proyecto está optimizado para:

📱 Mobile (320px - 768px)

💻 Tablet (768px - 1024px)

🖥️ Desktop (1024px+)

🎨 Componentes Desarrollados
Header
Título principal "Workout Schedule"

Subtítulo descriptivo

Diseño centrado y limpio

Calendar Grid
Grid de 7 columnas (días de la semana)

4 semanas visibles

Días numerados con slots de workout

Estilos diferenciados por tipo de entrenamiento

Sidebar
Upcoming Workouts: Próximos entrenamientos

Schedule Workout: Botón de acción principal

Start View: Opciones de vista inicial

Workout Cards
Información clara y concisa

Horarios destacados

Efectos hover suaves

```

```
