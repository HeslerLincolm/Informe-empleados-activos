# Informe de empleados activos – Recursos Humanos 

Este proyecto consiste en un análisis descriptivo de la fuerza laboral de una organización, utilizando **Microsoft Excel**. El reporte permite visualizar la estructura organizacional, la distribución salarial y la composición demográfica del personal para facilitar la gestión del talento humano.

## 📑 Contenido del análisis
El análisis se centra en las siguientes métricas extraídas de la base de datos de personal:

- **Métricas generales:**
  - **Headcount:** Conteo total de empleados activos (Cuenta de Código).
  - **Masa Salarial:** Cálculo de la inversión total en sueldos (Suma de Sueldo).
  - **Salario Promedio:** Análisis del sueldo medio por área y posición.

- **Dimensiones de análisis:**
  - **Por Departamento:** Desglose del personal y costos en áreas como Administración, I+D, Ventas y Recursos Humanos.
  - **Por Cargo:** Visualización jerárquica desde Directores y Gerentes hasta Técnicos y Representantes de Ventas.
  - **Perfil Demográfico:** Segmentación por Estado Civil (Casado, Divorciado, Soltero, Viudo) y género.

## 📂 Archivos
- `📊 Informe_Recursos_Humanos.xlsx` — Archivo original con la base de datos cruda y el procesamiento en tablas dinámicas.

## 🎯 Objetivo del proyecto y habilidades técnicas
Este proyecto demuestra la capacidad para gestionar y resumir datos operativos utilizando las funcionalidades analíticas de Excel:

### 1. Gestión de base de datos
- Manejo de una tabla de hechos ("BD") con información detallada de empleados (Fechas de contrato, Datos personales, Métricas de desempeño como *JobSatisfaction*).
- Normalización y limpieza de datos tabulares.

### 2. Tablas dinámicas (Pivot Tables)
- Creación de tablas dinámicas para agrupar y resumir datos ("TD" y "TD_DASH").
- Uso de diferentes funciones de resumen:
  - **Recuento (Count):** Para obtener el número de empleados por departamento.
  - **Suma (Sum):** Para calcular el presupuesto total de nómina.
  - **Promedio (Average):** Para identificar brechas salariales entre cargos.

### 3. Interactividad y reporting
- Implementación de **segmentación de datos (Slicers)** para filtrar el reporte dinámicamente por Departamento, Cargo o Estado Civil.
- Diseño de un layout tipo Dashboard dentro de una hoja de cálculo para una lectura ejecutiva rápida.

---
