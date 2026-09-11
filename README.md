# TS-League

Sistema de gestión y automatización de ligas competitivas de **Brawl Stars en Discord**.

Desarrollado con **Node.js, Discord.js y MongoDB**, cuenta con una arquitectura modular para gestionar equipos, partidos, rondas, divisiones, rankings y distintos procesos de la liga.

## ✨ Características

### ⚙️ Automatización

* Generación y gestión de jornadas y partidos.
* Programación de rondas, deadlines y avisos.
* Creación y gestión automática de canales y roles.
* Gestión de ascensos, descensos y eliminaciones.
* Limpieza automática de equipos y canales.

### 🎮 Gestión de la liga

* Gestión de equipos, jugadores y staff.
* Divisiones y rankings competitivos.
* Sistema de partidos y rondas.
* Control de resultados y clasificación.
* Gestión de permisos y roles específicos.

### 🎨 Sistema visual

* Paneles interactivos para gestionar diferentes partes de la liga.
* Botones, menús y modals de Discord.
* Generación de imágenes personalizadas para partidos y resultados.
* Assets gráficos adaptados al proyecto.

### 🔗 Integración con Brawl Stars

* Consulta de jugadores y equipos mediante la API oficial.
* Verificación de datos y elegibilidad.
* Sincronización de estadísticas.
* Gestión de ascensos y descensos basada en el rendimiento.

### 🗄️ Base de datos

MongoDB mediante Mongoose para almacenar y gestionar información relacionada con:

* Temporadas
* Divisiones
* Equipos
* Partidos
* Usuarios

## 🛠️ Tecnologías

* Node.js
* Discord.js
* MongoDB
* Mongoose
* Canvas
* Axios
* Luxon
* Sharp
* Dotenv

## 📁 Estructura

```text
src/
├── config/
├── discord/
├── services/
├── models/
├── utils/
├── handlers/
├── events/
└── assets/
```

La arquitectura separa la lógica de negocio, configuración, componentes de Discord, servicios y recursos gráficos para facilitar el mantenimiento y la ampliación del sistema.

## 🌐 Comunidad

El sistema fue desarrollado específicamente para el servidor de Discord TS Community Brawl, donde se gestiona la liga y se ofrece soporte a sus participantes.
