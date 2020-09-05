# Problema de violencia sexual en México.

## Declaración del problema.

La trata de personas atenta contra el derecho fundamental a la libertad, de esta forma no puede ser ajena a ningún ser humano. Teniendo esto en cuenta como científicos de datos queremos contribuir a la discusión sobre el tema y ayudar con herramientas para la detección oportuna de casos de alta vulnerabilidad. Uno de los principales motivos de este tipo de crímenes es aquel con fines de explotación sexual, dada la complejidad del problema de análisis de tráfico humano, se realiza un estudio específico acerca del comportamiento de la violencia sexual en México, el cuál es un país con notable presencia de este tipo de crímenes y se considera que los agresores de este tipo de delitos tienen un perfil similar o incluso se traslapan con aquellos que lidian en la trata de personas.

El problema que se tiene entonces es el de predecir y comprender los factores principales detrás de la violencia sexual en México, para poder detener este tipo de delitos y eventualmente concretar un modelo general de trata de personas con el propósito de combatir este crimen contra la humanidad, ya sea incrementando la seguridad en áreas de riesgo o informar al público de que grupos son más susceptibles a este tipo de crímenes.

## Objetivo de la solución.

La violencia sexual es uno de los delitos más complejos de rastrear, modelar y combatir; esto es cierto incluso en nuestra era moderna, nuestro propósito en el siguiente documento es identificar factores latentes que ayudarán en la creación de modelos predictivos, ayudando así en la creación futura de modelos más complejos, como un rastreador rápido y un identificador de violencia sexual.

## Descripción de la solución.

Para poder comenzar a trabajar con nuestro objetivo, dado que ninguna de nuestras bases de datos tienen una medida directa de violencia sexual en México, se crea un sistema de medición indirecto utilizando los crímenes más similares a este tales como: secuestros o violaciones, este sistema no es el ideal pero se debe realizar debido a la falta de bases de datos dedicadas a la investigación detallada de este tipo de crímenes. Este tipo de aproximación es aceptable ya que se considera que las personas que cometen este tipo de delitos tienen un perfil similar a las que están involucradas en violencia sexual.

Se usaron análisis de componentes principales y escalamiento multidimensional.

* El análisis de componentes principales (ACP) consiste en expresar un conjunto de variables en un conjunto de combinaciones lineales de factores no correlacionados entre sí, limitando al máximo la pérdida de información. Se realiza este método con la meta de poder ignorar problemas de correlación y hallar nuevas variables latentes, para identificar y rastrear a las víctimas, se considera que ACP nos permite ver nuestros datos de una manera más interpretable.

* El Escalamiento Multidimensional (MDS) es un método de análisis de una matriz de proximidad (similaridad o disimilaridad) establecida sobre un conjunto de individuos. El MDS tiene como objetivo modelizar las proximidades entre los individuos de tal modo que pueda representarlos lo más exactamente posible en un espacio de baja dimensión, la meta del análisis es la misma que el ACP pero se usa como método comparativo de resultado para dar mayor confiabilidad a nuestros resultados y cementar estas variables latentes como posibles coeficientes de un modelo futuro de predicción de tráfico humano o de susceptibilidad de las personas a este tipo de crimen.

## Lista de bases de datos y retos.

Los conjuntos de datos fueron los siguientes:
- "Encuesta Nacional de Victimización y Percepción sobre Seguridad Pública 2019", Obtenidos de [Conjunto de datos ENVIPE 2019](https://www.inegi.org.mx/contenidos/programas/envipe/2019/datosabiertos/conjunto_de_datos_envipe2019_csv.zip).

- Un reto importante es el de expandir la información de tráfico humano, dado la poca atención que se le da por las autoridades se tienen que buscar medidas indirectas de medición lo cual no es lo ideal, teniendo mejores bases de datos y realizando investigaciones más profundas sería posible construir un modelo comprensible de todos los aspectos de la trata de personas.

## Equipo

* *Benito Rodríguez Camejo*
* *Erika Tatiana Rueda Santos*
* *Javier Carrillo Martínez*
* *Stephania Sastre Muñoz*
* *Yareli Aleidali  Macias Ángeles*

