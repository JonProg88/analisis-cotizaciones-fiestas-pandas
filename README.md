# Análisis de Cotizaciones de Fiestas con Python y Pandas

## Descripción

Proyecto de análisis de datos desarrollado con Python y Pandas, usando un dataset ficticio de cotizaciones de fiestas, paquetes, sucursales, medios de contacto y estatus comercial.

El proyecto simula un escenario de análisis comercial para identificar paquetes más solicitados, ventas estimadas, comportamiento por sucursal, tasa de conversión y comportamiento mensual de cotizaciones.

> Nota: El dataset utilizado es ficticio y fue creado únicamente con fines educativos y de portafolio. No contiene información real de clientes, empresas o sistemas productivos.

## Objetivo del proyecto

Analizar información de cotizaciones de fiestas para responder preguntas como:

- ¿Qué paquetes son más solicitados?
- ¿Qué sucursales generan mayor monto estimado vendido?
- ¿Cuál es la tasa de conversión de cotización a venta?
- ¿Qué medios de contacto generan más cotizaciones?
- ¿Cómo se comportan las cotizaciones por mes?

## Tecnologías utilizadas

- Python
- Pandas
- Jupyter Notebook
- Matplotlib
- CSV

## Estructura del proyecto

```text
analisis-cotizaciones-fiestas-pandas/
│
├── data/
│   └── cotizaciones_fiestas.csv
│
├── notebooks/
│   └── analisis_cotizaciones_fiestas.ipynb
│
├── README.md
│
└── requirements.txt


Proceso realizado
Carga del dataset desde archivo CSV.
Exploración inicial con head() e info().
Conversión de la columna fecha con pd.to_datetime().
Creación de columna de mes para análisis temporal.
Identificación de paquetes más solicitados.
Filtrado de cotizaciones vendidas.
Cálculo del monto total vendido.
Agrupación de ventas por sucursal.
Cálculo de tasa de conversión.
Análisis de cotizaciones por mes.
Visualización básica de paquetes más solicitados.
Generación de conclusiones comerciales.


Análisis realizados
Paquetes más solicitados

Se identifica la frecuencia de cada paquete dentro del dataset.

Monto total vendido

Se calcula el monto total considerando únicamente cotizaciones con estatus Vendida.

Ventas por sucursal

Se agrupan ventas por sucursal para identificar mayor rendimiento comercial.

Tasa de conversión

Se calcula el porcentaje de cotizaciones que terminaron en venta.

Cotizaciones por mes

Se analiza el comportamiento mensual de solicitudes.

Principales hallazgos
Se identificaron los paquetes de fiestas más solicitados.
Se calculó la tasa de conversión de cotizaciones a ventas.
Se analizaron ventas estimadas por sucursal.
Se observó el comportamiento mensual de cotizaciones.
El análisis permite detectar oportunidades comerciales y mejorar el seguimiento de prospectos.



Cómo ejecutar el proyecto
1. Clonar el repositorio
git clone https://github.com/TU_USUARIO/analisis-cotizaciones-fiestas-pandas.git
2. Entrar a la carpeta del proyecto
cd analisis-cotizaciones-fiestas-pandas
3. Instalar dependencias
pip install -r requirements.txt

4. Abrir Jupyter Notebook
jupyter notebook

Después abre el archivo:

notebooks/analisis_cotizaciones_fiestas.ipynb
Autor

Jonathan Alanis Rojas

Desarrollador .NET con experiencia en SQL Server, APIs REST, sistemas empresariales y actualmente en transición hacia análisis de datos con Python, Pandas y herramientas de Data Science.



