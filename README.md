# Customer Data Cleaning - E-commerce

> Limpieza y preparación de datos de clientes para un programa de fidelización en comercio electrónico

##  Descripción

Proyecto de análisis de datos para **Store 1**, una empresa de e-commerce que necesita lanzar un Programa de Fidelización de Clientes. El objetivo es limpiar, estandarizar y preparar los datos de clientes para permitir segmentación efectiva y campañas de marketing personalizadas.

### Contexto de negocio
La empresa requiere segmentar clientes según:
- Edad
- Historial de compras
- Categorías de productos preferidas
- Gasto total por categoría

##  Objetivos del proyecto

1. **Limpiar perfiles de clientes** - Eliminar datos inconsistentes
2. **Estandarizar información** - Normalizar nombres y edades
3. **Calcular métricas clave** - Gasto total por cliente
4. **Validar consistencia** - Detectar y corregir errores
5. **Preparar datos para KPIs** - Formato listo para análisis de negocio

##  Estructura de datos

El dataset contiene las siguientes columnas:

| Campo | Descripción |
|-------|-------------|
| `usuario_id` | Identificador único del cliente |
| `usuario_nombre` | Nombre del cliente |
| `usuario_edad` | Edad del cliente |
| `categorias_fav_low` | Categorías favoritas (ELECTRÓNICA, DEPORTE, LIBROS, etc.) |
| `gasto_por_categoria` | Lista de gastos por cada categoría |

##  Tecnologías utilizadas

- **Python 3.x** - Lenguaje base
- **Listas y diccionarios** - Estructuras de datos
- **Manipulación de strings** - Estandarización de texto
- **Jupyter Notebook** - Ambiente de desarrollo

##  Proceso de limpieza

### 1. Estandarización de nombres
- Conversión a formato título (Primera Letra Mayúscula)
- Eliminación de espacios extras
- Corrección de caracteres especiales

### 2. Validación de edades
- Detección de valores fuera de rango
- Corrección de tipos de datos
- Manejo de valores nulos

### 3. Cálculo de métricas
- Suma de gasto total por cliente
- Identificación de categorías principales
- Preparación para segmentación

##  Resultados

-  Dataset limpio y estandarizado
-  Datos listos para análisis de segmentación
-  Base preparada para cálculo de KPIs
-  Validación de integridad completada


## Aprendizajes clave

- Limpieza de datos con Python básico
- Manipulación de listas y estructuras anidadas
- Validación de integridad de datos
- Preparación de datos para análisis de negocio




---

**Proyecto:** Bootcamp Data Analysis  
**Autor:** Marcos - [@NachtD69](https://github.com/NachtD69)  
**Fecha:** 2026
