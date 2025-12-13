# Plataforma Web de Gestión Administrativa - U.E.N. "José Ángel Álamo"

## 📖 Descripción del Proyecto

Este proyecto consiste en el desarrollo de una plataforma web centralizada para la **Unidad Educativa Nacional "José Ángel Álamo"**. [cite_start]El propósito principal es migrar los procesos administrativos centrales (Inscripción, Asistencia y Solicitudes) de formatos manuales basados en papel a una solución digital accesible vía web[cite: 16, 18].

[cite_start]El sistema busca solucionar la ineficiencia de los métodos manuales, permitiendo la automatización de la matrícula y el control académico[cite: 325].

### 🚀 Funcionalidades Principales

[cite_start]El sistema abarca los siguientes módulos críticos[cite: 19, 72, 76]:

* **Autenticación y Roles:** Sistema de login seguro con roles diferenciados (Administrativo, Docente, Estudiante).
* **Inscripción en Línea:** Formulario digital para la carga de datos y documentos del estudiante/representante.
* **Solicitudes y Documentos:** Generación automática de documentos en PDF (ej. Constancias de Estudio).

Funciones Tentativas:
  
* **Gestión Académica:** Módulo para docentes que permite la carga de notas y asistencia.
* **Validación Administrativa:** Flujo de aprobación o rechazo de inscripciones y trazabilidad de acciones.

---

## 🛠️ Tecnologías Utilizadas

[cite_start]El proyecto implementa una **Arquitectura de Tres Capas (MVC)** con separación de cliente y servidor[cite: 21, 134].

### Backend (API REST)
* **Lenguaje:** Python
* [cite_start]**Framework:** Django [cite: 21]
* [cite_start]**Base de Datos:** PostgreSQL [cite: 153]
* [cite_start]**Seguridad:** Autenticación JWT / Hash de contraseñas [cite: 207]

### Frontend (SPA)
* [cite_start]**Librería:** React.js [cite: 21]
* [cite_start]**Estilos:** Tailwind CSS [cite: 136]
* [cite_start]**Cliente HTTP:** Axios/Fetch [cite: 138]

