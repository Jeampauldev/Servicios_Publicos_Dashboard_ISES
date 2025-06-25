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

- [x] Power BI
- [x] Python
- [x] O3

---

## 🔍 Dataset

El dataset contiene información simulada sobre el consumo de **servicios públicos domiciliarios** y los **reclamos asociados** a dichos servicios en la ciudad de **Barranquilla, Colombia**. Los datos provienen del **Sistema Único de Información (SUI)** de la **Superintendencia de Servicios Públicos Domiciliarios (SSPD)**, específicamente de las vistas del sistema **O3**, que consolida datos y reclamos por tipo de servicio.

- 🌐 **Portal SUI:** https://sui.superservicios.gov.co/Reportes-del-Sector/
- 💻 **Herramienta O3:** http://bi.superservicios.gov.co/o3web/jdesktop.jsp


## 📁 1. Archivos Incluidos

### 🟩 1.1 `Caracterizacion_General_Empresas.xlsx`

Contiene información descriptiva sobre las empresas prestadoras de servicios públicos.

**Variables principales:**

- **Nombre de la empresa**
- **Departamento** y **Municipio**
- **Tipo de servicio prestado**
- **Naturaleza jurídica**
- **Categoría de empresa**
- **Fecha de constitución**


### 🟦 1.2 `consumo_servicios_barranquilla_simulado.csv`  
### 🟦 1.3 `consumo_servicios_barranquilla_simulado_2.csv`

Incluyen registros simulados de consumo de servicios públicos por parte de usuarios.

**Variables principales:**

- **Estrato socioeconómico**
- **Tipo de servicio** (Acueducto, Energía, etc.)
- **Valor facturado**
- **Consumo en unidades** (m³, kWh, etc.)
- **Periodo de facturación**


### 🟥 1.4 Archivos de Reclamaciones por Servicio

- `Reclamaciones-Acueducto.csv`
- `Reclamaciones-Alcantarillado.csv`
- `Reclamaciones-Aseo.csv`
- `Reclamaciones-Energia.csv`
- `Reclamaciones-Gas Natural.csv`

Cada archivo contiene registros de reclamos clasificados por:

- **Año** y **Mes**
- **Empresa prestadora del servicio**
- **Departamento** y **Municipio**
- **Causa del reclamo**
- **Número de reclamos**
- **Estado del reclamo** (Pendiente, Resuelto, etc.)
- **Tiempo de atención** (en días)


## 🧩 2. Variables Clave Comunes

| **Categoría**                | **Variables Comunes**                                                                 |
|-----------------------------|----------------------------------------------------------------------------------------|
| **Identificación geográfica** | `Departamento`, `Municipio`                                                           |
| **Temporalidad**             | `Año`, `Mes`                                                                          |
| **Servicio**                 | `Tipo de servicio` (`Acueducto`, `Energía`, etc.)                                    |
| **Empresa**                  | `Nombre de la empresa prestadora` o `Código`                                          |
| **Consumo**                  | `Unidades de consumo`, `Valor facturado`, `Estrato`                                  |
| **Reclamaciones**            | `Tipo de reclamo`, `Causa`, `Estado del reclamo`, `Tiempo de atención (días)`        |

---


## 📈 Insight y Análisis

- **Reclamos por Servicio:** Energía y acueducto concentran la mayor cantidad de reclamos en todos los años, destacando interrupciones y errores de facturación como causas principales.

- **Causas Frecuentes:** Problemas de medición, facturación y continuidad del servicio son recurrentes en todos los servicios públicos.

- **Municipios Críticos (2024):** Soledad, Malambo y Sabanalarga presentan altos volúmenes de reclamos, lo que indica zonas prioritarias para intervención operativa.

- **Duración de Interrupciones:** Barrios como Me Quejo y Los Andes presentan los tiempos promedio más altos, revelando posibles cuellos de botella técnicos.

- **Consumo Simulado:** El consumo aumenta con el estrato; los estratos bajos registran más casos de fraude y consumo sospechoso, útil para control y monitoreo.

- **Relación Consumo-Reclamos:** Algunos barrios muestran simultáneamente altos niveles de consumo y reclamos, lo que sugiere sobrecarga operativa en zonas específicas.


## 🚀 Cómo abrir el tablero

1. Clonar el repositorio
2. Abrir el archivo del tablero con Power BI
3. Explorar los filtros, gráficas y paneles disponibles

## 🧑‍💼 Autor

**Jeam Paul Arcon Solano**  
Candidato a Data Analytics – ISES  
Junio 2025
