# ProyectoBBDD_DAVID
# Proyecto Diseño de Base de Datos para Cliente - Extremcar

## Descripción
Este repositorio contiene el proyecto completo de diseño e implementación de una base de datos relacional para una empresa de alquiler de vehículos llamada **Extremcar**. El proyecto sigue todas las fases del desarrollo, desde el análisis de requisitos hasta la prueba y validación en **MySQL 8**.  
El objetivo es construir una base de datos **robusta, normalizada y eficiente**, capaz de gestionar información sobre clientes, reservas, pagos, facturas, vehículos, empleados, mantenimiento y más.

---

## Tabla de Contenidos

- [Requisitos](#-requisitos)  
- [Fases del Proyecto](#-fases-del-proyecto)  
  - [1. Recolección de Requisitos](#1-recolección-de-requisitos)  
  - [2. Diseño Conceptual](#2-diseño-conceptual)  
  - [3. Diseño Lógico](#3-diseño-lógico)  
  - [4. Diseño Físico](#4-diseño-físico)  
  - [5. Implementación en MySQL](#5-implementación-en-mysql)  
  - [6. Pruebas y Validación](#6-pruebas-y-validación)  
- [Estructura del Repositorio](#-estructura-del-repositorio)  
- [Instalación y Uso](#-instalación-y-uso)  
- [Contribuciones](#-contribuciones)  
- [Licencia](#-licencia)

---

##  Requisitos

- **MySQL Server 8.0 o superior**
- **MySQL Workbench** (opcional para diseño y administración)
- **Git**
- **Editor de texto/código** (VS Code, Sublime Text, etc.)
- **Sistema operativo compatible**: Windows, Linux o macOS

---

## Fases del Proyecto

### 1. Recolección de Requisitos
- Simulación de entrevistas con el cliente
- Identificación de entidades clave: clientes, vehículos, empleados, reservas, pagos, facturas, mantenimiento, etc.
- Análisis de las reglas de negocio

**Entregables**: `docs/requisitos.md`

---

### 2. Diseño Conceptual
- Diagrama Entidad–Relación (ER) usando notación Crow’s Foot
- Definición de entidades, atributos y relaciones
- Validación semántica con los requisitos

**Entregables**: `docs/ER_diagram.png` o `docs/ER_diagram.drawio`

---

### 3. Diseño Lógico
- Conversión del modelo ER al modelo relacional
- Normalización hasta Tercera Forma Normal (3FN)
- Asignación de claves primarias y foráneas

**Entregables**: `sql/01_logical_schema.sql`

---

### 4. Diseño Físico
- Tipos de datos adaptados a MySQL
- Creación de índices, claves, restricciones y vistas (si aplica)
- Uso de AUTO_INCREMENT y restricciones `ON DELETE`

**Entregables**: `sql/02_physical_schema.sql`

---

### 5. Implementación en MySQL
- Creación y ejecución de scripts
- Inserción de datos de prueba
- Creación de funciones, procedimientos y triggers

**Entregables**:  
- `sql/03_create_database.sql`  
- `sql/04_insert_data.sql`  
- `sql/05_procedures_functions_triggers.sql`

---

### 6. Pruebas y Validación
- Verificación de la integridad referencial
- Ejecución de consultas SELECT, JOIN, GROUP BY, etc.
- Casos de prueba y resultados esperados
- Informe con capturas de las pruebas realizadas


---
