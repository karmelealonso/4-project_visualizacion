# 4. Proyecto de visualización. 
# La diabetes y su relación con algunas variables sociodemográficas y hábitos de salud.

# 1.	INTRODUCCIÓN.

La diabetes representa un desafío significativo para la salud a nivel mundial, con una prevalencia en constante aumento en las últimas décadas. Ha emergido como una de las principales causas de mortalidad en adultos. 
En este contexto, el objetivo central de nuestro estudio es arrojar luz sobre la compleja relación entre la diabetes y variables sociodemográficas, como la edad o el género. Además, nos proponemos investigar cómo los hábitos de salud, incluyendo el ejercicio físico, la adherencia a la dieta mediterránea y el consumo de tabaco, se relacionan con la presencia de esta enfermedad.
A través de un análisis detallado de estas variables, se busca identificar posibles patrones subyacentes que contribuyan a la comprensión de esta condición y poder así desarrollar estrategias preventivas y de intervención.

# 2.	HIPÓTESIS GENERAL.

La diabetes guarda relación con variables sociodemográficas como la edad o el sexo; y con hábitos de salud como el ejercicio físico, la dieta mediterránea y el tabaquismo. También se correlaciona muy bien con el índice de masa corporal.


# 3.	OBJETIVOS CONCRETOS. 

1.	Conocer la relación que existe entre la diabetes y variables sociodemográficas y hábitos de salud.
En concreto:
    
    • Conocer la relación que existe entre la diabetes y variables sociodemográficas como la edad, o el sexo.

    • Conocer la relación que existe entre la diabetes y hábitos de salud como el ejercicio físico, la dieta mediterránea y el consumo de tabaco.

2.	Conocer si hay alguna correlación entre la diabetes y el índice de masa corporal.

# 3.	MATERIAL Y MÉTODOS.

# 3.1. POBLACIÓN A ESTUDIO.

Estudio realizado a 258931 trabajadores (103427 mujeres y 155504 hombres), de distintas regiones de nuestro país (Baleares, Andalucía, Canarias, Comunidad Valenciana, Cataluña, Madrid, Castilla La Mancha, Castilla León, País Vasco) y pertenecientes a sectores laborales muy diversos entre los que podemos destacar hostelería, construcción, comercio, sanidad, administración pública, transporte, educación, industria y limpieza.

# 3.2 MEDICIONES.

- El estudio se llevó a cabo en el periodo comprendido entre los meses de enero de 2020 y junio de 2021. 

- Los datos clínicos y personales de los trabajadores se obtuvieron de la base de datos anonimizada de trabajadores que está disponible en el repositorio de la escuela universitaria ADEMA-UIB (Universidad de las Islas Baleares).

- Se considera a una persona fumadora si había consumido al menos un cigarrillo diariamente (o su equivalente en otras modalidades de consumo) en los últimos treinta días, o si había dejado el consumo hace menos de 12 meses.

- La clase social se clasificó en tres categorías partiendo de los datos de la Clasificación Nacional de Ocupaciones 2011 (CNO-11) y aplicando los criterios establecidos por la Sociedad Española de Epidemiología: 
    -	Clase I. Personal directivo, profesionales universitarios, deportistas y artistas.
    -	Clase II. Trabajadores con cualificación en ocupaciones intermedias y autónomos.
    -	Clase III. Trabajadores no cualificados.

# 4.	ANÁLISIS Y ESTUDIO DEL PRIMER OBJETIVO.

# 4.1. PROCEDIMIENTO.

![](https://github.com/karmelealonso/4-project_visualizacion/blob/main/imagenes/Dashboard%201.png)

[Dashboard1](https://public.tableau.com/views/4-project_visualizacion/Dashboard1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link)

Se presenta aquí, en primer lugar, un análisis sobre la conexión entre ciertas variables sociodemográficas y la incidencia de la diabetes. Tanto el gráfico circular como el tree map revelan que la prevalencia de la diabetes es más notable en el sexo masculino en comparación con el femenino.

Adicionalmente, el gráfico de barras destaca que el grupo de edad más afectado, tanto para mujeres como para hombres, se sitúa entre los 30 y los 39 años.


![](https://github.com/karmelealonso/4-project_visualizacion/blob/main/imagenes/Dashboard%202.png)

[Dashboard2](https://public.tableau.com/views/4-project_visualizacion/Dashboard2?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link)

Por otro lado, en relación con los gráficos de burbujas presentados, se realiza una comparación entre la prevalencia de la diabetes y ciertos hábitos de salud. Se observa claramente que tanto el ejercicio como la adhesión a la dieta mediterránea son factores que influyen en la incidencia de la diabetes.

No obstante, no se aprecia de manera evidente, al menos a simple vista, una relación entre el consumo de tabaco y la diabetes. En este momento, no se puede confirmar ninguna asociación, pero podría ser objeto de investigaciones futuras para determinar si existe algún vínculo entre ambos factores.

# 4.2 DISCUSIÓN. 

Los resultados obtenidos en este estudio sobre la incidencia de la diabetes revelan asociaciones significativas entre diversas variables sociodemográficas y hábitos de salud. En primer lugar, como decíamos un poco más arriba, se observa una relación significativa entre el sexo masculino y el rango de edad de entre los 30 y los 39 años con valores más elevados en la incidencia de diabetes. Este hallazgo sugiere que los hombres de dicha edad pueden ser más susceptibles a desarrollar diabetes, posiblemente debido a factores biológicos o de estilo de vida específicos a esta población.
Además, se destaca la influencia de la actividad física y la adherencia a la dieta mediterránea en la incidencia de la diabetes. Los individuos sedentarios y con baja adherencia a la dieta mediterránea muestran valores más altos de incidencia de diabetes, lo que respalda la importancia de estos hábitos saludables en la prevención de la enfermedad. Curiosamente, el consumo de tabaco no parece tener una correlación significativa, indicando que, al menos en este contexto, el tabaquismo no está directamente asociado con la incidencia de diabetes.

# 4.3. CONCLUSIONES GENERALES.

1. Las diferentes variables sociodemográficas analizadas  influyen en la incidencia de la diabetes.
2. Los diferentes hábitos saludables analizados (actividad física y adherencia a la dieta mediterránea), a excepción del con sumo de tabaco, lo cual no parece que guarde mucha relación, influyen en la incidencia de la diabetes.

# 5. ANÁLISIS Y ESTUDIO DEL SEGUNDO OBJETIVO.

En este caso, a diferencia del estudio anterior, utilizaremos como variable la glucemia, la cual se refiere al nivel de glucosa (azúcar) en la sangre. La relación entre la glucemia y la diabetes es fundamental, ya que la diabetes es una enfermedad caracterizada por niveles elevados de glucosa en la sangre.

En este caso, nos es más favorable utilizar dicha variable. 

Como planteba antes, la hipótesis de la que partimos en este caso es la siguiente: El IMC y la edad están correlacionados con la diabetes. 

-	En este escenario, necesitamos averiguar si las gráficas de tendencias ambas suben o bajan a la vez. Así, las representaremos para luego hallar el coeficiente de correlación.

# 5.1 CORRELACIONES. PROCEDMIENTO.

Comencemos nuestro análisis enfocándonos en las correlaciones, un concepto fundamental para comprender la interrelación entre dos variables cuantitativas. 
Es esencial tener en claro que una correlación nos indica el grado en que dos variables cuantitativas se afectan entre sí, esta afectación puede ser tanto positiva como negativa, y el grado será fuerte o débil.

Las correlaciones positivas se dan cuando ambas variables se desplazan en la misma dirección, esto quiere decir que mientras una crece, la otra también tiende a hacerlo, y viceversa en caso de disminución. A diferencia, las correlaciones negativas se manifiestan cuando una variable crece mientras que la otra decrece.
Por otro lado, los grados de afectación indican la fuerza con la que las variables están relacionadas. 
Mientras las correlaciones fuertes muestran signos de comportamiento lineal, las correlaciones débiles sugieren comportamientos aparentemente más bien aleatorios y menos predecibles.

¿QUÉ SON EXACTAMENTE?

Es importante tener en mente que las correlaciones no son causalidad, aunque la relación entre dos variables sea positiva y fuerte, esto no quiere decir que una produzca a la otra.

En las gráficas siguientes, podemos ver como se comparan, en los tres casos, dos conjuntos de datos. 

![](https://github.com/karmelealonso/4-project_visualizacion/blob/main/imagenes/Dashboard%203.png)

[Dashboard3](https://public.tableau.com/views/4-project_visualizacion/Dashboard3?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link)

Observamos una correlación fuerte entre ambas variables en todos los casos, evidenciando que cuando una variable experimenta un aumento, la otra también lo hace. Sin embargo, como decía, es importante destacar que esta conexión no implica necesariamente causalidad. Aunque ambas variables están vinculadas en sus cambios, no podemos concluir que el cambio en una sea la causa directa del cambio en la otra; la correlación refleja una asociación, pero no establece una relación causal clara.

# 5.2 DISCUSIÓN.

A simple vista, a veces es difícil confirmar una correlación entre ambas variables, pero podemos tener un poco más de detalle mostrando la línea para a continuación poder observar también un cuadro con información acerca de la misma, buscando el valor R-cuadrado, es decir, el valor de correlación. 
Este valor indica la fuerza y dirección de la correlación, sacando primeramente lo evidente. Al ser positivo, tenemos una correlación positiva; y si fuera negativo, tendríamos una correlación negativa. 
El valor de la correlación siempre se encuentra entre 1 y -1, siendo los extremos donde la correlación es más fuerte y, mientras se acerca a 0, la correlación se va debilitando. En el caso de tener una correlación en 0, entonces podemos concluir que ambas variables son independientes entre si.

# 5.3 CONCLUSIONES.

En estos tres casos se tiene una correlación de 0,94, 0.98 y 0,94 respectivamente. Son, como bien puede deducirse, correlaciones positivas, lo que quiere decir que ambas variables crecen al mismo tiempo; y son fuertes, pues se puede decir que la correlación es fuerte cuando el valor de este se encuentra por encima de 0.3 (en el caso de correlaciones positivas) o por debajo de -0.3 (en el caso de correlaciones negativas).


# 6. ALGUNOS MATICES FINALES.

Aunque la glucemia en sangre parece ser directamente proporcional a la edad, puede variar debido a diversos factores, como los mencionados arriba: la actividad física, la dieta o también por la sensibilidad a la insulina. En general, se observa que la glucemia tiende a aumentar con la edad, pero esto no es una regla universal.
Es por esto que en el gráfico de barras anterior, en la cual se observaba una relación entre la prevalencia de la diabetes y la edad, había una mayor incidencia de diabetes en adultos de mediana edad en comparación con los ancianos, que es lo que nos podría dar a entender este último gráfico. 
En resumen, es esencial tener en cuenta que la diabetes no está determinada únicamente por la edad, sino por una combinación de factores genéticos, ambientales y de estilo de vida. 

# 7. CONTENIDO DEL REPOSITORIO. 

- notebook: contiene un archivo jupyter notebook.
    1. main.ipynb: contiene la extracción y posterior limpieza y transformación del archivo CSV. 
- data: contiene dos archivos con las tablas. 
    1. raw: contiene el archivos recién extraído, en crudo.
    2. el archivo limpio.
- imágenes: contienen las imágenes utilizadas a lo largo del proyecto.




**Para obtener información más detallada sobre el procedimiento y los pasos que se han seguido, te invito a consultar los documentos disponibles en el repositorio.**


