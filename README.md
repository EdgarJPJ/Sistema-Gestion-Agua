# 💧 HTWO0 - Sistema IoT de Gestión y Monitoreo Hídrico

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Technology](https://img.shields.io/badge/Stack-FullStack%20IoT-blue)

> **Nota sobre el Código Fuente:** *Este proyecto fue desarrollado en colaboración académica y profesional. Debido a acuerdos de confidencialidad y propiedad intelectual, el código fuente completo no es público. Este repositorio sirve como documentación técnica, demostración de arquitectura y evidencia de funcionalidades.*

## 📖 Descripción del Proyecto
**HTWO0** es una solución integral diseñada para optimizar la administración de recursos hídricos en juntas auxiliares. El sistema resuelve la problemática del desperdicio y la gestión manual mediante la automatización del control de flujo y el monitoreo en tiempo real.

El sistema permite a los administradores visualizar el consumo, gestionar usuarios y controlar el suministro de agua de forma remota mediante dispositivos IoT.

---

## 🏗️ Arquitectura del Sistema
El proyecto sigue una arquitectura desacoplada, separando la lógica de negocio (Backend) de la interfaz de usuario (Frontend) y los dispositivos físicos (IoT).

### Flujo de Datos
1.  **Nivel Físico (IoT):** Microcontroladores **ESP32** monitorean el flujo de agua y gestionan electroválvulas.
2.  **Comunicación:** Los dispositivos envían telemetría y reciben comandos en tiempo real.
3.  **Backend (Core):** Una API RESTful en **Spring Boot** procesa la información, gestiona la seguridad y almacena los históricos.
4.  **Frontend (Cliente):** Un dashboard en **React** consume la API para mostrar gráficos y controles al usuario.

---

## 🛠️ Tech Stack (Tecnologías)

### Backend & Base de Datos
* ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) **Java (Spring Boot):** Creación de API REST robusta y gestión de lógica de negocio.
* ![MySQL](https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=mysql&logoColor=white) **MySQL:** Persistencia de datos de usuarios y registros de consumo.
* **Seguridad:** Implementación de autenticación y validación de datos.

### Frontend
* ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) **React:** Desarrollo de interfaz interactiva y dashboard administrativo.
* **CSS3/Bootstrap:** Diseño responsivo para visualización en distintos dispositivos.

### Hardware / IoT
* ![ESP32](https://img.shields.io/badge/Espressif-ESP32-red?style=for-the-badge) **ESP32:** Microcontrolador para telemetría y control de actuadores.

---

## ✨ Funcionalidades Clave

* **📡 Monitoreo en Tiempo Real:** Visualización del flujo de agua y detección de anomalías.
* **🚰 Control Remoto (IoT):** Capacidad de abrir o cerrar el suministro de agua desde el dashboard web (corte remoto).
* **👥 Gestión de Usuarios:** CRUD completo para la administración de los beneficiarios del servicio.
* **📊 Reportes Visuales:** Gráficos de consumo para la toma de decisiones.

---

## 📸 Galería del Proyecto

### 1. Dashboard Principal (React)
> Visualización de métricas y estado del sistema.
### 2. Control de Dispositivos (IoT)
> Interfaz para la gestión de flujo y electroválvulas.
### 3. Prototipo Físico
> Implementación del circuito con ESP32.
---

## 👨‍💻 Autor y Contribuciones
**Edgar Jafet Pérez Juárez** - *Full Stack & IoT Developer*

Mi rol principal en el proyecto incluyó:
* Diseño y desarrollo de la **API REST con Spring Boot**.
* Integración de la comunicación entre el hardware **ESP32** y el servidor.
* Implementación del Dashboard interactivo utilizando **React**.
* Diseño de la base de datos relacional para el registro histórico de consumos.

---
*Este proyecto fue desarrollado como parte de una iniciativa académica en el Instituto Tecnológico Superior de Teziutlán (2024).*
