# ArrestosNYC-EDA
Análisis exploratorio de Datos sobre arrestos en New York a lo largo de los años.

Se plantearon una serie de objetivos que se detallan a continuación:

1) Describir las Características Generales de los Arrestos: Analizar variables como el número total de arrestos, tipos de delitos, demografía de los arrestados (edad, género, raza), y localización geográfica de los incidentes.

2) Identificar Tendencias Temporales: Examinar cómo varían los arrestos a lo largo del tiempo, identificando patrones ya sean diarios, semanales, mensuales y/o anuales.

3) Analizar la Distribución Geográfica de los Arrestos: Investigar las diferencias en la tasa de arrestos entre distintos barrios y distritos de Nueva York, y determinar si existen áreas con una mayor concentración de incidentes.

4) Explorar Factores Asociados con los Arrestos: Identificar variables socioeconómicas, demográficas y ambientales que pueden estar asociadas con una mayor probabilidad de arresto, utilizando técnicas estadísticas y de visualización de datos.

De no ser posible llegar a conclusiones a partir de la información provista por el dataset, se formularán hipótesis respecto a los patrones descubiertos, fundamentalmente en cuanto a las relaciones de causalidad entre fenómenos.

En definitiva, a lo largo de este trabajo se llegaron a diversas correlaciones y patrones que se detallarán a continuación, pero las relaciones de causalidad e hipótesis que puedan surgir (y destaquemos) a partir de esta información debe ser validada mediante estudios más exhaustivos.

Algunas conclusiones que se encontraron fueron:

1) Tras al menos 10 años de baja en los niveles de crímenes, se manifiesta un incremento importante en los números desde 2021. Interesantemente, estos niveles están directamente atados a la disminución de crimenes relacionados al manejo de drogas peligrosas. Arrestos relacionados a otros crimenes se mantienen mas o menos constantes. Investigando externamente se descbrió que en 2012 se inició un movimiento de reforma para la decriminalización de posesión de marihuana, que se hizo efectivo en 2014. Hipotetizamos que estas reformas de tomar medidas laxas en respuesta a crimenes relacionados con el manejo de drogas es la explicación de la caída de los crímenes realmente. Aún así, y a pesar de todo, tras 2021 todos los crimenes crecen en conjunto. 
2) El incremento de los últimos años en crímenes no está relacionado a una normalización de los números post-pandemia. Considerando que hace años que viene bajando o manteniendose constante, esta repentina suba debe tener otra explicación. Hipotetizamos que la inestabilidad económica, específicamente la repentina suba de inflación, es la variable que determina fundamentalmente este cambio de tendencia.
3) Los niveles de crímenes y la cantidad de arrestos por jurisdicción y precinto valida la información contenida en los datasets. El trabajo muestra cuáles son los precintos con más arrestos y cuáles son las áreas que más arrestos tienen. Si se busca por otros medios la ubicación de los precintos, los mismos cuadran perfectamente con los niveles de arrestos encontrados en el dataset para esos precintos.
4) El manejo de drogas peligrosas es, por lejos, el crimen más común. Prevalece tanto en hombres como en mujeres en valores altos
5) Se muestra un mapa con información geográfica de los arrestos en números. Existen tres focos importantes: El centro de Brooklyn, el corazón de Manhattan, y la zona del Bronx. Acumulativamente son los tres focos que superan la decena de miles de arrestos.
6) Existe en general una importante preponderancia de hombres arrestados por sobre mujeres.

Como mencionamos anteriormente, se encontraron muchos patrones de correlación  con los datos estudiados. Sin embargo, deben realizarse estudios más exhaustivos para llegar a la raíz de lo planteado y establecer relaciones de causalidad. 

Acciones que se podrian tomar gracias al analisis realizado:

1) Asignación de Recursos:
   
Focalización en Áreas Clave: Los mapas y gráficos que muestran la concentración de arrestos en ciertos distritos y barrios (como los precintos 14, 44 y 77) sugieren la necesidad de asignar más recursos policiales a estas áreas. Esto podría incluir un aumento de patrullas, programas de vigilancia comunitaria y estrategias de prevención del delito específicas para cada zona.

Prioridades: Los delitos más frecuentes incluyen agresiones, hurto menor y delitos relacionados con drogas. Abordar estos tipos específicos de delitos debe ser una prioridad para las fuerzas del orden.

2) Programas de Prevención:
   
Jóvenes en Riesgo: La alta incidencia de arrestos en los grupos de edad de 18-24 y 25-44 indica la necesidad de programas de prevención del delito dirigidos a jóvenes. Estos programas podrían incluir iniciativas educativas, oportunidades de empleo y apoyo social para ayudar a los jóvenes a evitar la delincuencia.

Desigualdades Raciales: La desproporcionada representación de ciertos grupos raciales en los datos de arrestos exige una investigación más profunda sobre las posibles causas de estas disparidades. Esto podría llevar a la implementación de políticas y prácticas policiales más justas y equitativas.

Sexo: Los hombres son arrestados significativamente más a menudo que las mujeres en la mayoría de las categorías de delitos, lo que destaca las diferencias de género en el comportamiento delictivo o en las respuestas de las fuerzas del orden.

Predictive Policing: Explorar el uso de algoritmos de aprendizaje automático para predecir la probabilidad de delitos en áreas específicas y momentos del día. Esto podría ayudar a optimizar la asignación de recursos policiales y prevenir delitos antes de que ocurran.

3) Enfoque en Delitos Específicos:
   
Delitos Comunes: El análisis de los delitos más frecuentes (como asalto, hurto menor y delitos relacionados con drogas) puede ayudar a desarrollar estrategias específicas para combatir estos problemas. Esto podría incluir campañas de concientización pública, programas de rehabilitación para delincuentes y medidas para abordar las causas subyacentes de estos delitos.
