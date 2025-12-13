# Plataforma Web de Gestión Administrativa - U.E.N. "José Ángel Álamo"

## 📖 Descripción del Proyecto

Este proyecto consiste en el desarrollo de una plataforma web centralizada para la **Unidad Educativa Nacional "José Ángel Álamo"**. El propósito principal es migrar los procesos administrativos centrales (Inscripción, Asistencia y Solicitudes) de formatos manuales basados en papel a una solución digital accesible vía web.

El sistema busca solucionar la ineficiencia de los métodos manuales, permitiendo la automatización de la matrícula y el control académico.

### 🚀 Funcionalidades Principales

El sistema abarca los siguientes módulos críticos:

* **Autenticación y Roles:** Sistema de login seguro con roles diferenciados (Administrativo, Docente, Estudiante).
* **Inscripción en Línea:** Formulario digital para la carga de datos y documentos del estudiante/representante.
* **Solicitudes y Documentos:** Generación automática de documentos en PDF (ej. Constancias de Estudio).

Funciones Tentativas:
  
* **Gestión Académica:** Módulo para docentes que permite la carga de notas y asistencia.
* **Validación Administrativa:** Flujo de aprobación o rechazo de inscripciones y trazabilidad de acciones.

---

## 🛠️ Tecnologías Utilizadas

El proyecto implementa una **Arquitectura de Tres Capas (MVC)** con separación de cliente y servidor.

### Backend (API REST)
* **Lenguaje:** Python
* **Framework:** Django 
* **Base de Datos:** PostgreSQL 
* **Seguridad:** Autenticación JWT / Hash de contraseñas 

### Frontend (SPA)
* **Librería:** React.js
* **Estilos:** Tailwind CSS 
* **Cliente HTTP:** Axios/Fetch 

