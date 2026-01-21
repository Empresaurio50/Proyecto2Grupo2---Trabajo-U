# Plataforma de Pasantías (Proyecto 2 (Si así se llama la materia))

## Descripción del Proyecto

Este proyecto tiene como objetivo **facilitar la conexión entre empresas públicas, privadas y ONGs con estudiantes en busca de pasantías**, permitiendo que dichas oportunidades se alineen con la carrera académica del estudiante y contribuyan al desarrollo de su experiencia laboral.

La plataforma busca resolver dos problemas principales:

* Las **empresas** tienen dificultades para encontrar pasantes adecuados a sus necesidades.
* Los **estudiantes** carecen de un medio centralizado, confiable y organizado para encontrar pasantías relacionadas con su perfil académico.

---

> [!IMPORTANT]
>Este proyecto fue desarrollado con fines académicos.

---
##  Objetivo Principal

> **Facilitar la conexión entre empresas públicas, privadas y ONGs con estudiantes en busca de pasantías que se alineen con su carrera y les permitan desarrollar experiencia laboral.**

---

##  Metodología de Desarrollo

El proyecto fue desarrollado utilizando la metodología **Scrum**, organizada en **Sprints**, cada uno enfocado en entregar funcionalidades específicas alineadas al objetivo del sistema.

Cada Sprint incluye:

* Historias de Usuario
* Criterios de Aceptación
* Incrementos funcionales del sistema

---

## Funcionalidades por Sprint
> [!WARNING]
> Muchas de las funcionalidades no estan implementadas por que se dejo de usar el Github en el proyecto por decisión de grupo

###  Sprint 1 – Funcionalidades Base

* Inicio de sesión (para estudiantes y empresas)
* Registro de usuario (estudiante)
* Registro de empresa (flujo diferente al estudiante)
* Listado de ofertas de pasantías
* Visualización de ofertas de pasantías

---

###  Sprint 2 – Gestión de Perfil y Seguridad

* Edición de información de empresa
* Creación y actualización de perfil de empresa
* Visualización de perfil (empresa y estudiante)
* Recuperación de contraseña mediante correo electrónico

---

###  Sprint 3 – Interacción y Perfil del Estudiante

* Carga de CV en formato PDF
* Agregar actitudes/habilidades del estudiante
* Sistema de recomendaciones:

  * Me gusta y disgusta a las ofertas de pasantías

---

###  Sprint 4 – Gestión Avanzada y Comunicación

* Visualización de aplicantes por oferta (vista empresa)
* Filtro de ofertas de pasantías
* Edición de ofertas
* Sistema de notificaciones
* Notificaciones relacionadas con mensajes

---

###  Sprint 5 – Comunicación, Seguimiento y Administración

* Sistema de mensajería entre empresas y estudiantes
* Chat iniciado únicamente por la empresa con el postulante
* Sistema de seguimiento de empresas:

  * El estudiante puede seguir empresas
  * Notificación cuando una empresa publica una nueva oferta
* Sistema de administración:

  * Visualizar estudiantes, empresas y ofertas en tablas
  * Editar o eliminar ofertas inapropiadas o irrelevantes

---

## Arquitectura y Tecnologías Utilizadas

### Tecnologías actuales

* **Java**
* **Maven**
* **XHTML**
* **PrimeFaces**
* Arquitectura en capas (Presentación, Controller, Entidades y Acceso Datos)
* MYSQL

---

## Evolución del Proyecto (Trabajo Futuro)

El proyecto se encuentra en proceso de **rearquitectura**, con los siguientes cambios planificados:

### Backend

* Migración a **Spring Boot**
* Exposición de servicios mediante **API REST**
* Uso de los mismos casos de uso actuales
* Implementación de protocolos HTTP (GET, POST, PUT, DELETE)

### Frontend

* Separación completa del frontend
* Nuevo repositorio independiente
* Desarrollo del frontend con **Angular**
* Consumo de la API REST desarrollada en Spring Boot

---

## Organización del Proyecto

Este repositorio contendrá **únicamente el Backend**, mientras que el frontend será desarrollado y mantenido en un repositorio separado.

---

## Roles del Sistema

* **Estudiante**

  * Buscar pasantías
  * Aplicar a ofertas
  * Subir CV
  * Comunicarse con empresas
  * Seguir empresas

* **Empresa**

  * Publicar ofertas
  * Ver postulantes
  * Iniciar conversaciones
  * Gestionar su perfil

* **Administrador**

  * Gestionar ofertas, empresas y estudiantes
  * Moderar contenido del sistema

---

## Estado del Proyecto

En desarrollo Funcionalidades base implementadas
En proceso de migración a arquitectura Backend + Frontend desacoplados

---

> [!IMPORTANT]
> Este proyecto fue desarrollado con fines académicos.
