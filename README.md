# Telecomunicaciones_P02
# <h1 align="center">**`Telecomunicaciones PI02 `**</h1>

<p align="center">
<img src="Telecomunicaciones.pgn"  height=300>
</p>

## **Descripción del problema y contexto**

Las telecomunicaciones juegan un papel crucial en la sociedad moderna, facilitando la transmisión de información de largas distancias a través de diversas tecnologías como el internet, la telefonía móvil y fija. En Argentina, el sector de las telecomunicaciones está experimentando un crecimiento significativo, con desafíos y oportunidades únicas en términos de penetración de internet, tecnologías utilizadas y correlaciones con los ingresos económicos.

## **Rol y objetivos del Proyecto**

Este proyecto tiene como objetivo realizar un análisis del sector de las telecomunicaciones en Argentina. Se busca entender el comportamiento del mercado para orientar estrategias que mejoren la calidad de los servicios y aprovechen oportunidades de crecimiento. El enfoque principal es analizar la penetración de internet por provincia, correlacionarla con los ingresos económicos y proponer KPIs para medir el crecimiento y calidad del servicio.

## **Metodología y Herramientas Utilizadas**
### El proyecto se desarrolló utilizando las siguientes herramientas y metodologías:

- **Python** (pandas, matplotlib, seaborn): Utilizado para el análisis exploratorio de datos (EDA).
- **Power BI:** Utilizado para el diseño y desarrollo del dashboard interactivo.

#### Análisis Exploratorio de Datos (EDA): :mag: :eyes: :memo:

Basandome en la principal actividad de la empresa que es el acceso a internet y teniendo en cuenta el Kpi propuesto, hice una seleccion de hojas a utilizar para tener una vision mas enfocada del mercado de internet en Argentina y que nuestro analisis este alineado. Se realizó un EDA exhaustivo utilizando Python en un Jupyter Notebook, donde se limpiaron, exploraron y visualizaron los datos para identificar patrones y tendencias clave.

1) **Importación y limpieza de datos:**
- Importación de los datos desde un archivo excel.
- Revisión y limpieza de los datos mediante un análisis preliminar.

2) **Análisis descriptivo:**
- Cálculo de estadísticas descriptivas para comprender mejor la distribución de los datos.
- Creación de visualizaciones iniciales para identificar patrones y tendencias generales.

3) **Visualización de datos:**
- Uso de bibliotecas como matplotlib y seaborn para crear gráficos que permitan visualizar las relaciones y tendencias en los datos.
- Gráficos de barras, histogramas y mapas de calor para identificar correlaciones.
- Visualización de los datos segmentados por diferentes variables como tipo de accesos de internet por provincia, velocidades de internet, ingresos y tipos de tecnoglogias.

4) **Identificación de KPIs:**

- Definición de indicadores clave de rendimiento **(KPIs)** relevantes para el análisis, como el aumento de los accesos de internet por provincia y el aumento de acessos de internet por fibra optica.

## **KPIs Propuestos**

- Incremento en Acceso a Internet por 100 Hogares: KPI para aumentar en un 2% el acceso al servicio de internet por cada 100 hogares en cada provincia para el proximo trimestre.

- Incremento en Acceso a Internet por Fibra Óptica: KPI para incrementar en un 2% el acceso al servicio de internet por fibra óptica para el próximo trimestre.

- Incremento en los ingresos por usuario: KPI para Aumentar en un 5% los ingresos por usuario(ARPU) para el próximo trimestre.

#### Dashboard:

- Importación de los datos limpios y procesados desde Python a Power BI.
- Creacion de medidas y transformaciones.
- Creación de visualizaciones.
- Configuración de filtros.
- Interactividad y navegabilidad: Configuración de interacciones entre gráficos para mejorar la navegabilidad y facilitar la interpretación de los datos.

### Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

Datasets/: Carpeta que contiene los datos/archivos utilizados en el análisis.
EDA: Notebooks de Python utilizado para el EDA y análisis de datos.
Telecomunicaciones/: Archivo de Power BI con el dashboard interactivo.
README.md: Este archivo, que proporciona una descripción detallada del proyecto, metodología aplicada, y análisis de los resultados obtenidos.

### Conclusiones

El análisis de los datos relacionados con el acceso a internet mostró un incremento notable en los ingresos desde 2020, posiblemente impulsado por el aumento en la demanda de servicios durante la pandemia. No obstante, la elevada inflación que afecta a nuestro país reduce el poder adquisitivo de los consumidores, lo que también impacta la contratación de servicios de internet. Esto convierte al acceso a internet en un tema sensible que requiere monitoreo constante. Por ello, resulta crucial tomar medidas para sostener el crecimiento en la penetración de internet y minimizar los efectos de la situación económica actual. Fomentar la expansión de la infraestructura de fibra óptica y desarrollar estrategias enfocadas en provincias con menor acceso pueden no solo incrementar la penetración de internet y los ingresos, sino también mejorar la calidad y competitividad de los servicios en el mercado de telecomunicaciones en Argentina.
