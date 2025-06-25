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

Este repositorio contiene información simulada sobre el consumo de servicios públicos domiciliarios y los reclamos asociados a dichos servicios en la ciudad de Barranquilla, Colombia. Los datos provienen del Sistema Único de Información (SUI) de la Superintendencia de Servicios Públicos Domiciliarios (SSPD), específicamente de las vistas del sistema O3, que consolida datos y reclamos por tipo de servicio.

🌐 Portal SUI: https://sui.superservicios.gov.co/Reportes-del-Sector/

💻 Herramienta O3: http://bi.superservicios.gov.co/o3web/jdesktop.jsp

📁 Archivos Incluidos
1. Caracterizacion_General_Empresas.xlsx
Contiene información descriptiva sobre las empresas prestadoras de servicios públicos.

Variables principales:

Nombre de la empresa

Departamento y Municipio

Tipo de servicio prestado

Naturaleza jurídica

Categoría de empresa

Fecha de constitución

2. consumo_servicios_barranquilla_simulado.csv
3. consumo_servicios_barranquilla_simulado_2.csv
Incluyen registros simulados de consumo de servicios públicos por parte de usuarios.

Variables principales:

Estrato socioeconómico

Tipo de servicio (Acueducto, Energía, etc.)

Valor facturado

Consumo en unidades (m³, kWh, etc.)

Periodo de facturación

4. Archivos de Reclamaciones por Servicio
Reclamaciones-Acueducto.xlsx

Reclamaciones-Alcantarillado.xlsx

Reclamaciones-Aseo.xlsx

Reclamaciones-Energia.xlsx

Reclamaciones-Gas Natural.xlsx

Cada archivo contiene registros de reclamos clasificados por:

Año y Mes

Empresa prestadora del servicio

Departamento y Municipio

Causa del reclamo

Número de reclamos

Estado del reclamo (Pendiente, Resuelto, etc.)

Tiempo de atención (en días)

🧩 Variables Clave Comunes
Categoría	Variables Comunes
Identificación geográfica	Departamento, Municipio
Temporalidad	Año, Mes
Servicio	Tipo de servicio (Acueducto, Energía, etc.)
Empresa	Nombre de la empresa prestadora o Código
Consumo	Unidades de consumo, Valor facturado, Estrato
Reclamaciones	Tipo de reclamo, Causa, Estado del reclamo, Tiempo de atención (días)




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
