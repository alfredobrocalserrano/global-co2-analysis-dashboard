# Análisis Global de Emisiones de CO2 (1900-2021) 🌍

Este proyecto presenta un análisis integral de las emisiones de dióxido de carbono a nivel mundial, utilizando un flujo de datos completo que abarca desde la limpieza de datos hasta la creación de un dashboard interactivo.

## 🚀 Flujo de Trabajo

### 1. Limpieza de Datos (Python/Colab)
He utilizado **Python** y la librería **Pandas** para procesar el dataset original (*Emissions by Country*).
- Filtrado de registros históricos (desde 1900).
- Tratamiento de valores nulos y limpieza de columnas.
- Exportación del dataset optimizado para análisis SQL.

### 2. Análisis de Datos (SQL/DBeaver)
Utilizando **DBeaver**, he realizado consultas SQL complejas para extraer tres insights clave:
- **Evolución por Fuente:** Análisis de cómo el carbón, petróleo y gas han impulsado las emisiones.
- **Responsabilidad Histórica:** Ranking Top 10 de países con mayores emisiones acumuladas.
- **Tendencias de Descarbonización:** Identificación de los países con mayor reducción porcentual entre 2011 y 2021.

### 3. Visualización (Google Sheets Dashboard)
He integrado los resultados en un **Dashboard interactivo** que incluye:
- Gráficos de áreas apiladas para el mix energético mundial.
- Gráficos de barras para el ranking histórico.
- KPIs dinámicos que muestran récords de reducción (ej. el caso de Venezuela con un -54.68%).

## 📊 Visualización del Proyecto

![Dashboard Preview](dashboard/tu_captura_del_dashboard.png)
*(Sustituye esta imagen con una captura real de tu trabajo)*

## 🛠️ Herramientas Utilizadas
- **Python** (Pandas)
- **SQL** (DBeaver)
- **Google Sheets** (Visualización y Dashboards)
- **Dataset:** Global Carbon Budget 2022.

## 📈 Conclusiones Clave
1. El **carbón** sigue siendo la fuente dominante, aunque el gas ha crecido exponencialmente desde 1950.
2. El Top 10 histórico refleja **industrialización temprana**, no población: India y China, los países más poblados, quedan por 
detrás de Alemania o Reino Unido.
3. Europa lidera la **descarbonización** reciente, con UK (-26%), Italia (-22%) y España (-18%) entre 2011 y 2021.
4. Venezuela presenta una reducción atípica del -54,68% fruto del colapso económico, no de política climática.





