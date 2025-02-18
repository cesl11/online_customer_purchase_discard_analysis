# online_customer_behavior_analysis

### Resumen:
Este proyecto estudia un conjunto de datos públicos recopilados para el artículo _"Shopper intent predictionfrom clickstream e‑commerce datawith minimal browsing information"_, disponibles bajo acuerdo de atribución en el repositorio de GitHub _"Awesome Public Datasets"_: (https://github.com/awesomedata/awesome-public-datasets). El _dataset_, que contiene casi 5.5 millones de puntos de datos, ofrece información sobre las acciones de los visitantes de una tienda de calzado _online_: día y hora  de la sesión, acciones concretas de clicks (agregar artículos, comprar, ver detalles, etc.) y el SKU de los productos con los que se interactúa. Se busca encontrar información relevante que ayude a determinar **qué factores contribuyen a que un cliente abandone un carrito de compra**, y a partir de ella proponer soluciones y/o medidas de acción empresariales que neutralicen este comportamiento y disminuyan la tasa de abandono.

La **tasa de abandono** se calculó en **6.16441 %**. El Análisis exploratorio de datos (EDA) arrojó ciertas ideas relevantes, como los días con mayor número de abandonos (lunes y martes). El período de tiempo comprendido entre las 12PM y las 2PM, así como el de 8PM - 9PM concentraron la mayor parte de estos eventos. Se descubrieron patrones recurrentes de comportamiento entre los usuarios: la mayoría de las sesiones aue terminaron en un abandono de la compra muy probablemente sin que esta hubiera siquiera comenzado, lo que se infiere dado que el patrón 'visualización de página' → 'evento' fue el más común en las sesiones que terminaron sin compras.  

Se aplicó un modelo de Bosque Aleatorio (Random Forest) y otro de Regresión Logística (Logistic Regression) para clasificar las sesiones que terminaban o no en compra, y descubrir qué factores predecían mejor cómo terminaría cada sesión. A partir del análisis, se proponen estrategias de marketing e inteligencia empresarial para abordar los _insights_ (información relevante) y aumentar la cantidad de sesiones que terminan en compra.

(Consultar el informe final de investigación en este repositorio para el análisis en profundidad)

---------------------------------------------------

* **Origen de los datos:** https://www.nature.com/articles/s41598-020-73622-y.epdf?sharing_token=tydJezcxTZvP8cNEDsAKn9RgN0jAjWel9jnR3ZoTv0NoB1nwg3Wgf_mP0ktAdV_HGxUxXaNdBCErP1Zck0ibhFGwRrt0xq-Uy2wNz5DkwbFN44Mxzwb3WdN593RbqBFNucB9hEgd3EFvTZaqO9reUDDlh-mybSw5d1-G04RfdBQ%3D
* **Créditos y atribuciones:** Requena, B., Cassani, G., Tagliabue, J., Greco, C., & Lacasa, L. (2020). _Shopper intent prediction from clickstream e-commerce data with minimal browsing information_. Scientific Reports, 10(1). https://doi.org/10.1038/s41598-020-73622-y
