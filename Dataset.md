# Título: Calidad del vino en base a caraterísticas físico químicas

## Característricas:

* Se ha tomado como modelo de estudios la minería de datos de vinos, ya que los resultados pueden ser aplicados a cualquier ámbito, lugar o momento.
* Se ha modelado las características del vino a través de la minería de datos estudiando sus propiedades fisico químicas.
* Se han creado dos datasets usando pruebas de vino tinto y vino blanco.
* Los objetivos de los tests incluyen por ejemplo valores del PH y datos sensoriales realizados por expertos en vinos.
* Cada experto ha calificado la calidad del vino entre 0 (muy mala calidad) y 10 (excelente calidad). 
* Los dos conjuntos de datos se relacionan, en este caso el vino tinto y vino blanco de los vinos Vino Verde.
* Con fines de privacidad y logística, solo se han tomado en cuenta datos físico químicos y variables sensoriales. No se ha tomado en cuenta datos a cerca del tipo de uva, categoria de vino, precio, etc.
* Número de ejemplares: Vino Tinto- 1599; Vino Blanco - 4898. 

## Atributos:

1. fixed acidity            - Acidez fija    (Acidez es una propiedad fundamental del vino,impartiendo aspereza y resistencia a la infección microbial)
2. volatile acidity         - Acidez volátil
3. citric acid              - Acido cítrico
4. residual sugar           - Azúcar residual
5. chlorides                - cloruros
6. free sulfur dioxide      - dióxido libre de azufre
7. total sulfur dioxide     - total de dióxido de azufre
8. density                  - densidad
9. pH                       - pH (potencial hidrogenado.- Es una medida de acidez o alcalinidad de una disolución.)
10. sulphates               - sulfato
11. alcohol                 - alcohol
    Output variable (based on sensory data): 
12. quality (score between 0 and 10)   - calidad entre 0 y 10


## Descripción:
La *acidez* presente en los vinos constituyen un componente muy importante tanto en la fabricación de los vinos como en la obtención del producto final; teniendo directa influencia en el color, balance y el sabor del vino; tanto como el crecimiento y la vitalidad de la levadura durante la fermentación y para proteger el vino de las bacterias. La medición de la cantidad de acidez en el vino se refiere al total de todos los ácidos presentes, mientras que la fuerza de la acidez es medida de acuerdo al *pH*, donde la mayoría de los vinos tinen un pH entre 2.9 y 3.9. Generalmente mientras más bajo es el pH de los vinos es mayor la acidez de estos. En todo caso no hay una conexión directa entre el total de acidez y el pH, ya que es posible encontrar vinos de otras marcas con un alto nivel de pH con un alto nivel de acidez. En la degustación de vinos el término acidez se refiere a la frescura, agrio y aspereza del vino, los cuales son evaluados en relación de que tan bien la acidez balancea la dulcura y componentes amargos del vino. 

## Objetivos:
* Se propone un acercamineto de minería de datos para predecir las preferencias de gustos en vinos de los humanos, basados en pruebas analíticas. Se ha tomado en cuenta un conjunto de datos grande,  con ejemplares de vino tinto y vino blanco llamado "Vino Verde" de Portugal. 
* Este modelo es muy útil para realizar evaluaciones de gustos en vinos, para de esta manera impulsar la producción de vinos. También esta técnica puede ayudar en realizar el marketing modelando los gustos de los consumidores desde nichos de mercados.




