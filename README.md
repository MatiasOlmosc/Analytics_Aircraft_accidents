# Proyecto de Análisis de Datos sobre Accidentes Aéreos

![image](https://github.com/MatiasOlmosc/Analytics_Aircraft_accidents/assets/72405832/f6db5373-e8b8-42a1-996a-deba2ea476ee)

## Introducción

Este proyecto se enfoca en el análisis de datos sobre accidentes aéreos y la creación de un Dashboard Interactivo utilizando la herramienta Power BI.

## Contexto

El objetivo de este proyecto es analizar datos históricos de accidentes aéreos para identificar patrones, tendencias y factores que puedan contribuir a mejorar la seguridad en la aviación civil.

## Objetivos

- Sumergirse en el apasionante mundo de los accidentes aéreos ocurridos desde 1908 hasta 2021.
- Realizar un EDA para descubrir patrones, tendencias y conexiones ocultas en estos incidentes.
- Diseñar un dashboard interactivo en Power BI que no solo informe, sino que también enganche al espectador.
- Analizar dos KPI (Indicadores Clave de Rendimiento) en particular, desmenuzando y comprendiendo cada una de las métricas involucradas, y luego relacionarlas con nuestros objetivos definidos.

## Contenido

- **Investigación y Transformación de Datos (ETL)**: Este proyecto incluye un Jupyter Notebook que es el corazón de nuestras investigaciones. Aquí, con la ayuda de poderosas bibliotecas como Pandas, Numpy, Matplotlib, Seaborn y Sklearn, hemos explorado, limpiado, agregado y sacado valiosas conclusiones de cada variable en el conjunto de datos. Nuestro objetivo es preparar los datos para una representación visual efectiva.

- **Análisis en Power BI**: Luego de darle forma a nuestros datos, los importamos a Power BI para un análisis más profundo. Aquí, creamos visualizaciones interactivas que cuentan historias. Usamos filtros y segmentaciones que se aplican a todo el informe, permitiendo a los usuarios explorar y comprender mejor los datos. Nuestro objetivo es lograr una asimilación efectiva de la información a través de visualizaciones envolventes.

## Análisis Exploratorio de Datos


Con el propósito de comprender los datos presentados, llevamos a cabo una serie de análisis y estudios sobre las variables del conjunto de datos. Nuestro objetivo era descubrir relaciones entre los datos y comprender su importancia. 

![image](https://github.com/MatiasOlmosc/Analytics_Aircraft_accidents/assets/72405832/faf30afe-d317-4e7e-82a7-6f52c1ee3375)

Nuestro análisis incluyó:

Creación de nubes de palabras para identificar patrones comunes en las descripciones de los accidentes.
Análisis de distribuciones de frecuencias y estadísticas de las variables numéricas.
Identificación de valores atípicos (outliers) en las variables de interés.
Exploración de variables categóricas y sus valores únicos.
Análisis detallado de accidentes, tasas de mortalidad y la seguridad de vuelo en función de diferentes aspectos, como país, aerolínea, tipo de aeronave, marca de aeronave y categoría de vuelo.
Análisis temporal, desglosado por hora, mes y año.

## PowerBI Dashboard. 

1.

![asda](https://github.com/MatiasOlmosc/Analytics_Aircraft_accidents/assets/72405832/8e12ae70-aa14-4cd0-a95c-8d531346014f)


En esta sección, presentamos un análisis de los accidentes aéreos por país. Proporcionamos información sobre el número de pasajeros a bordo frente a las fatalidades y la tasa de mortalidad a lo largo del tiempo. A simple vista, Estados Unidos se destaca como el país con más accidentes y, por consiguiente, el mayor número de fatalidades.
Sin embargo, es importante no dejarse llevar por esta primera impresión. Al profundizar en el análisis, observamos que, en comparación con otros países, Estados Unidos muestra una tasa de mortalidad aceptable del 60%. Además, la alta cantidad de personas a bordo sugiere que es un país con un gran volumen de vuelos, lo que aumenta las posibilidades de accidentes.
Nuestro objetivo es proporcionar una vista equilibrada desde múltiples perspectivas para evitar un análisis sesgado y brindar una comprensión más completa de la situación.

2. 

![Untitled](https://github.com/MatiasOlmosc/Analytics_Aircraft_accidents/assets/72405832/b9b4f1de-2797-49ff-85af-2fed1f7db7a7)


La página "Operador" muestra la cantidad de operadores  Se presenta información sobre cantidad pasajeros a bordo, sobrevivientes y la tasa de mortalidad. Analizamos el KPI de bajar un 10% por año la tasa de mortalidad desde el período de 1998 (78% tasa de mortalidad) a 1999 superando con creces el objetivo planteado llegando a una tasa de mortalidad del 29%.
Es necesario clarificar de que per se el hecho de que una aerolínea tenga un mayor número de fatalidades no necesariamente significa que sea menos segura que otras. Puede haber varias razones detrás de esto que no necesariamente están relacionadas con la seguridad intrínseca de la aerolínea. Aquí hay algunas de las razones por las cuales una aerolínea podría tener más fatalidades sin que eso signifique necesariamente que sea menos segura:

1. **Volumen de Operaciones:** Las aerolíneas que realizan un gran número de vuelos y transportan un gran número de pasajeros tienen más oportunidades de enfrentar incidentes o accidentes simplemente debido a su volumen de operaciones. Cuantas más veces una aerolínea opere vuelos, mayor será la probabilidad de que ocurra un incidente.

2. **Tamaño de la Flota:** Las aerolíneas más grandes tienden a tener flotas más grandes, lo que también aumenta las posibilidades de estar involucradas en un accidente. Una flota más grande significa más aeronaves en el aire, lo que aumenta la exposición al riesgo.

3. **Rutas y Destinos:** Las aerolíneas que vuelan a regiones geográficas o rutas con condiciones climáticas adversas o problemas de seguridad específicos pueden enfrentar un mayor riesgo de accidentes.

4. **Antigüedad:** Las aerolíneas más antiguas pueden tener un historial de operaciones más largo, lo que significa que han estado expuestas al riesgo durante más tiempo.


Por lo tanto, es importante tener en cuenta estas consideraciones al evaluar la seguridad de una aerolínea. La seguridad se evalúa mejor considerando varios indicadores y tomando en cuenta el contexto en el que opera.

3.

![adlinwdl](https://github.com/MatiasOlmosc/Analytics_Aircraft_accidents/assets/72405832/c35e1037-1bd8-4e74-ac8d-fdfd98d0ed24)

La página "Aeronave" presenta la cantidad de aeronaves involucradas en accidentes. Se incluyen medidores de tasa de mortalidad , así como gráficos de barras con las principales aeronaves. Se destaca la importancia de mantener la seguridad en vuelos.
El gráfico tiene como objetivo mostrar las aeronaves que han estado involucradas en la mayor cantidad de accidentes aéreos con fatalidades. Proporciona una visión general de las aeronaves que han experimentado los incidentes más trágicos en términos de pérdida de vidas. Este análisis es fundamental para identificar aeronaves que puedan requerir una revisión de seguridad, retirada o actualización de equipos.

**Proceso de Análisis:**
- El análisis comienza por agrupar los datos en función del tipo de aeronave (columna 'aircraft_type') y calcular la suma total de fatalidades asociadas con cada tipo de aeronave.
- Luego, se seleccionan las 10 aeronaves con la mayor cantidad de fatalidades y se ordenan de menor a mayor en el gráfico de barras horizontal.

Este análisis es fundamental para la industria de la aviación, ya que ayuda a identificar tendencias y patrones relacionados con la seguridad de aeronaves específicas. Revela cuáles son las aeronaves que han estado involucradas en los accidentes más mortales, lo que puede llevar a investigaciones y revisiones exhaustivas de seguridad para prevenir futuros incidentes similares.

- **Identificación de Aeronaves de Alto Riesgo:** El gráfico podría identificar aeronaves que han tenido un historial problemático en términos de seguridad y que podrían requerir una atención especial en términos de mantenimiento, revisión de diseño o retirada.
  

De todas maneras, es esencial tener en cuenta que el gráfico se basa exclusivamente en la suma total de fatalidades asociadas con cada tipo de aeronave. Esto significa que no se están teniendo en cuenta otros factores clave que también influyen en la seguridad de la aviación, como el número de personas a bordo, el número total de vuelos realizados por cada tipo de aeronave, las condiciones meteorológicas, la edad de la aeronave, la experiencia de la tripulación y otros aspectos operativos.


Dicho esto no podemos concluir que una aeronave es inherentemente insegura basándonos únicamente en la cantidad de fatalidades registradas. Pueden existir numerosos factores externos e internos que contribuyan a los accidentes y fatalidades.

**Complemento con el Ratio de Fatalidades:** Para una comprensión más completa de la seguridad de una aeronave en particular, es fundamental considerar el "Ratio de Fatalidades por Persona a Bordo" que se mencionó anteriormente. Este ratio tiene en cuenta la proporción de fatalidades en relación con el número total de personas a bordo, lo que proporciona una visión más precisa de la seguridad en términos de pérdida de vidas. Por ejemplo, si tomamos solo este gráfico de cantidad de fatalidades vemos al Douglas DC-3 primero con creces, ahora bien la misma aeronave tiene uno de los ratios de fatalidades más bajos del top10, es decir que en caso de accidentes es más probable que más personas a bordo sobrevivan que en otras aeronaves que ni siquiera están presentes en este gráfico como Havilland DH 4. Asimismo, el Douglas DC-3 tiene un ratio de fatalidad altísimo pero la explicación anterior sirve para reforzar la idea de que no podemos quedarnos con un solo gráfico o métrica si no queremos hacer un análisis sesgado. 

**Conclusión:** Si bien este análisis puede resaltar aeronaves con un historial de accidentes más mortales, no es la única métrica para evaluar la seguridad de la aviación. Debe combinarse con otros datos y análisis más detallados para obtener una imagen completa y precisa de la seguridad de las aeronaves y la industria de la aviación en general.

4.

Aquí tenemos comparativa de tasa de fatalidad entre dos décadas y vemos que tenemos para 3.25 y 3.66 indicando que aproximadamente mueren cada 1000 accidentes 3000 mil tripulantes. También podemos observar en base al kpi planteado de reducir en un 10% la tasa de mortalidad entre décadas que el mismo no se ha podido cumplimentar puesto que lejos de bajar, la tasa de mortalidad aumentó. 

![awdadasdas](https://github.com/MatiasOlmosc/Analytics_Aircraft_accidents/assets/72405832/9ece6a86-1b0e-4348-a238-8942ad02f57b)

