# Aplicación de Gestión de Tareas con Dashboard y Estadísticas en Tiempo Real

## Descripción del proyecto

Esta aplicación web fue desarrollada como una solución para la gestión y seguimiento de tareas mediante una interfaz moderna e interactiva. El sistema permite a los usuarios crear, editar, eliminar y consultar tareas de manera eficiente, además de visualizar métricas y estadísticas en tiempo real a través de un panel de control (dashboard).

El objetivo principal del proyecto es demostrar la implementación de tecnologías modernas para el desarrollo de aplicaciones web, integrando un frontend construido con React y Vite, junto con un backend basado en Supabase, el cual gestiona la autenticación de usuarios, la base de datos y la comunicación en tiempo real.

La aplicación también se encuentra desplegada en la nube mediante Azure App Service, lo que permite que el sistema sea accesible de forma remota y funcione como una aplicación web completa.

---

## Funcionalidades principales

La aplicación cuenta con múltiples funcionalidades orientadas a la gestión eficiente de tareas y al análisis de la información generada por los usuarios.

### Gestión de tareas

Los usuarios pueden administrar sus tareas mediante operaciones básicas conocidas como CRUD:

* Crear nuevas tareas
* Editar tareas existentes
* Eliminar tareas
* Marcar tareas como completadas

Cada tarea puede ser modificada en cualquier momento, permitiendo mantener un seguimiento actualizado de las actividades pendientes o finalizadas.

### Búsqueda de tareas

El sistema incorpora una funcionalidad de búsqueda que permite localizar tareas de forma rápida dentro del listado disponible. Esto facilita la organización y el acceso a información específica cuando el número de tareas registradas es elevado.

### Actualización en tiempo real

Una de las características más importantes del sistema es la actualización en tiempo real. Gracias a la integración con Supabase, cualquier cambio realizado en las tareas se refleja inmediatamente en la interfaz de usuario sin necesidad de recargar la página.

Esto permite que los datos se mantengan sincronizados y actualizados constantemente, mejorando la experiencia del usuario.

### Dashboard con indicadores (KPIs)

La aplicación cuenta con un panel de control o dashboard que presenta estadísticas relevantes sobre las tareas registradas en el sistema.

Entre los indicadores disponibles se encuentran:

* Cantidad total de tareas registradas
* Número de tareas completadas
* Número de tareas pendientes
* Comparación entre tareas finalizadas y tareas no realizadas

Estos indicadores permiten visualizar de manera clara el progreso de las actividades y analizar el estado general de las tareas.

Además, los gráficos y estadísticas se actualizan en tiempo real conforme se realizan cambios en las tareas, lo que permite observar el impacto inmediato de las acciones realizadas dentro de la aplicación.

### Sistema de autenticación de usuarios

La aplicación incorpora un sistema completo de autenticación que permite gestionar el acceso de los usuarios al sistema.

Las funcionalidades incluidas son:

* Registro de nuevos usuarios
* Inicio de sesión
* Recuperación de contraseña
* Restablecimiento de contraseña

Este sistema garantiza que cada usuario tenga acceso seguro a su información y a sus tareas personales dentro de la plataforma.

---

## Tecnologías utilizadas

Para el desarrollo de esta aplicación se utilizaron diversas tecnologías modernas orientadas al desarrollo de aplicaciones web escalables.

### Frontend

* React
* Vite
* TypeScript
* CSS
* Recharts (para la visualización de gráficos en el dashboard)

### Backend

* Supabase
* Base de datos PostgreSQL
* Autenticación de usuarios
* Realtime subscriptions

### Despliegue

* Azure App Service

---

## Arquitectura de la aplicación

El sistema sigue una arquitectura basada en frontend y backend desacoplados.

El frontend desarrollado con React se encarga de la interfaz de usuario, la interacción con el usuario y la visualización de los datos. Por otro lado, Supabase actúa como backend proporcionando:

* almacenamiento de datos
* autenticación de usuarios
* actualizaciones en tiempo real
* API para comunicación con el frontend

Finalmente, la aplicación se encuentra desplegada en Azure App Service, lo que permite que el sistema funcione como una aplicación web accesible desde internet.

---

## Despliegue

La aplicación se encuentra desplegada en la nube mediante Azure App Service, lo que permite que el sistema esté disponible de forma pública y pueda ser utilizado desde cualquier navegador.

El despliegue se realiza utilizando GitHub Actions, que automatiza el proceso de construcción y publicación de la aplicación cada vez que se realizan cambios en el repositorio.

---

## Objetivo del proyecto

El objetivo de este proyecto es demostrar la integración de tecnologías modernas para el desarrollo de aplicaciones web completas, incluyendo funcionalidades de autenticación, manipulación de datos, visualización de estadísticas y despliegue en la nube.

Además, busca mostrar el uso de herramientas actuales para el desarrollo frontend y backend, así como buenas prácticas en el uso de repositorios y despliegues automáticos.

---

## Autor

Samuel Stiven Sierra
