# Tablero de análisis de servicios públicos - ISES

Este repositorio contiene el desarrollo de una prueba técnica para el cargo de **Data Analytics** en ISES, cuyo objetivo es construir un tablero interactivo para facilitar el análisis y la toma de decisiones operativas en el contexto de los servicios públicos de Barranquilla.

## 📌 Objetivo

Crear un tablero interactivo a partir de un set de datos abierto relacionado con los servicios públicos (energía, agua, gas), que permita detectar patrones, identificar tendencias y facilitar decisiones estratégicas.

## 📂 Estructura del proyecto

/data/ 

/notebooks/ 

/dashboard/ 

README.md 


## 📊 Herramienta utilizada

- [ ] Power BI
- [ ] Python


## 🔍 Dataset

CARACTERIZACIÓN DE LA BASE DE DATOS GENERAL
Origen
La información proviene del Sistema Único de Información (SUI) de la Superintendencia de Servicios Públicos Domiciliarios de Colombia. Específicamente, los datos están organizados a partir de vistas del sistema O3, las cuales agrupan información consolidada y reclamos de los usuarios por servicio público domiciliario.

Portal del SUI: https://sui.superservicios.gov.co/Reportes-del-Sector/

Herramienta O3: http://bi.superservicios.gov.co/o3web/jdesktop.jsp

Descripción General
La base de datos está compuesta por información simulada sobre consumo de servicios públicos domiciliarios en Barranquilla y reclamos asociados a los servicios de:

Acueducto

Alcantarillado

Aseo

Energía

Gas Natural

Además, se incluye una caracterización general de las empresas prestadoras de servicios públicos.

📂 Archivos Proporcionados y su Contenido
Caracterizacion_General_Empresas.xlsx

Contiene variables descriptivas de las empresas prestadoras.

Variables principales:

Nombre de la empresa

Departamento y municipio

Tipo de servicio prestado

Naturaleza jurídica

Categoría de empresa

Fecha de constitución

consumo_servicios_barranquilla_simulado.csv y consumo_servicios_barranquilla_simulado_2.csv

Información simulada de consumo de servicios por parte de los usuarios.

Variables típicas esperadas:

Estrato socioeconómico

Tipo de servicio

Valor facturado

Consumo en unidades (m³, kWh, etc.)

Periodo de facturación

Archivos de Reclamaciones por Servicio (Excel)

Reclamaciones-Acueducto.xlsx

Reclamaciones-Alcantarillado.xlsx

Reclamaciones-Aseo.xlsx

Reclamaciones-Energia.xlsx

Reclamaciones-Gas Natural.xlsx

Cada archivo contiene reclamos clasificados por:

Año y mes

Empresa responsable

Departamento y municipio

Causa del reclamo

Número de reclamos

Estado del reclamo (pendiente, resuelto, etc.)

Tiempo de atención (en días)

🧩 Variables Principales Comunes
Categoría	Variables Comunes
Identificación Geográfica	Departamento, Municipio
Temporalidad	Año, Mes
Servicio	Tipo de servicio (Acueducto, Energía, etc.)
Empresa	Nombre o código de la empresa prestadora
Consumo	Unidades de consumo, valor facturado, estrato
Reclamaciones	Tipo de reclamo, causa, estado del reclamo, tiempo de atención




## 📈 Insight y análisis

(Resumen de hallazgos clave que explican las visualizaciones)

## 🚀 Cómo abrir el tablero

1. Clonar el repositorio
2. Abrir el archivo del tablero con Power BI
3. Explorar los filtros, gráficas y paneles disponibles

## 🧑‍💼 Autor

**Jeam Paul Arcon Solano**  
Candidato a Data Analytics – ISES  
Junio 2025
