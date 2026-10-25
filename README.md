# Analisis-de-los-Censos-Portugueses-2011-IV
Tercer análisis estadístico y demográfico sobre los edificios y los residentes mayores de las freguesias de São José y Benfica (Censo 2011, Portugal) usando R.

Este proyecto consiste en un análisis estadístico y demográfico de los datos del Censo de Portugal del año 2011 con respecto a las **freguesias de São José y Benfica**. El objetivo principal es identificar patrones en la **población mayor** de estas freguesias — relacionados con los **grupos de edad, el género y el estado civil** — a través de herramientas de ciencia de datos.

## 🚀 Tecnologías y Herramientas
* **Lenguaje:** R (v4.3.0)
* **Entorno:** RStudio / R Markdown
* **Paquetes principales:** `ggplot2`, `ca`, `FactoMineR`

## 📁 Estructura del Repositorio
* `analisis.Rmd`: Código fuente con las transformaciones y anotaciones en R Markdown.
* `analisis.md`: Versión renderizada para visualización directa en GitHub.

## 📊 Origen de los Datos y Metodología
Los datos utilizados provienen del **INE (Instituto Nacional de Estatística de Portugal)**, correspondientes al Censo de Población y Vivienda de 2011 (**BGRI** - *Base Geográfica de Referencia de Información*). 

La segmentación de la población mayor residente en la **Freguesia de São José** y la **Freguesia de Benfica** se efectúa mediante las siguientes variables:
*   **Grupo etario:** 65-69 años, 70-74 años, y 75 o más años.
*   **Género:** Mujer y hombre.
*   **Estado civil:** Soltería, matrimonio, viudez y divorcio.

El objetivo metodológico de esta publicación es presentar y discutir los resultados de dos **Análisis de Correspondencias Múltiples (ACM)**: uno realizado mediante el paquete `ca` y otro a través del paquete `FactoMineR`. Además, estas presentaciones y discusiones se complementan con análisis descriptivos breves y la aplicación de **pruebas de chi-cuadrado**.

## 🎯 Pregunta de Investigación Contextual
*   *¿Existen diferencias importantes entre ambas freguesias en lo que respecta a la distribución de grupos de edad, géneros y estados civiles?*

## 📜 Contexto Histórico y Etnográfico
Es fundamental evidenciar que el Censo de 2011 constituye la **última información censal disponible sobre la Freguesia de São José**, dado que, posteriormente, ocurrió la reorganización administrativa de la ciudad de Lisboa (2012).

En el contexto de estos datos, se encuentran similitudes con las realidades del *Bairro de São José*, pero estas concordancias deben ser tomadas en consideración con las debidas cautelas:
1. El *Bairro de São José*, como cualquier otro barrio, es una **realidad aproximada** que pertenece exclusivamente al dominio de la tradición oral.
2. Sus residentes consideraban que la fracción de la *Avenida da Liberdade*, integrada administrativamente en la **Freguesia de São José**, no pertenecía conceptualmente al barrio.
3. En lo relativo a la población anciana residente, a diferencia de lo que ocurre en el *Bairro de São José*, es posible que la *Avenida da Liberdade* presente una ocupación residencial concentrada, sobre todo, en los subtramos de menor edad de dicha población.

Estas cuestiones metodológicas y cualitativas fueron identificadas mediante **etnografías y entrevistas semiestructuradas**, y se presentan de manera detallada en mi **Tesis Doctoral en Sociología**.

## Documentación relacionada con este proyecto:
Puede consultar el trabajo desarrollado a través de los siguientes enlaces:
* **Versión en Markdown:** [Leer documento complementario en el repositorio](Análisis_CensosIV.md)
* **Publicación Oficial:** [Acceder a la publicación en línea de mi Tesis Doctoral en Sociología](http://hdl.handle.net/10071/19979)
