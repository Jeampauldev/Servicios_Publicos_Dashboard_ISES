# Reporte Ingesta y Limpieza de Datos

Esta fase se enfocó en la recolección, exploración estructural y limpieza de los datos necesarios para el análisis de los servicios públicos domiciliarios en Barranquilla y municipios del Atlántico.

---

## Archivos procesados

Los archivos cargados originalmente se encontraban en formatos `.csv` y `.xlsx`, con datos provenientes del SUI y de una fuente simulada. Incluyeron:

- Reclamaciones por servicio (`.csv`)
- Caracterización de empresas prestadoras (`.xlsx`)
- Consumo de servicios simulado por barrio (`.csv`)

---

##  Proceso de limpieza aplicado

###  Estandarización:
- Se normalizaron nombres de columnas (`upper()`, `strip()`, `replace()`).
- Se unificaron datasets por servicio y año.

###  Transformación de fechas:
- Se creó la columna `Fecha` a partir del campo `Año` (`yyyy-01-01`) para facilitar análisis temporal.

###  Datos numéricos:
- Se corrigieron campos con comas como separador de miles (`'1,234'` → `1234`).
- Todos los campos clave (`Número de Reclamos`, `Consumo`, etc.) se transformaron a `int` o `float`.

### Reclamos:
- Se aplicó `melt` para transformar la tabla de formato ancho a largo.
- Se eliminaron duplicados y filas vacías.

### Consumo simulado:
- Se limpió y estandarizó la columna de barrios (`BARRIO_LIMPIO`).
- Se eliminaron registros duplicados y se corrigieron caracteres especiales y tildes.
- Se detectaron y manejaron valores nulos en campos como `consumo_energia_kwh`, `estado_medidor`, y `tecnico_asignado`.

---

## Archivos exportados

Los datos limpios se almacenaron en la carpeta `01_data_clean/`, listos para análisis y visualización:

- `reclamaciones_aseo_limpio.csv`
- `reclamaciones_energia_limpio.csv`
- `reclamaciones_acueducto_limpio.csv`
- `reclamaciones_alcantarillado_limpio.csv`
- `reclamaciones_gas_limpio.csv`
- `caracterizacion_empresas_limpio.csv`
- `consumo_simulado_limpio.csv`

---

## Resultado

Esta fase dejó disponibles datasets limpios, confiables y estructurados que permiten:
- Realizar análisis exploratorios robustos (FASE 2).
- Cargar los datos de forma directa en Power BI.
- Detectar correlaciones, tendencias y generar KPIs estratégicos.

