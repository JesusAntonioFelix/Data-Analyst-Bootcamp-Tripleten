# Proyecto: Analisis marketing

## Objetivo del proyecto

Se analiza en una gran tienda en línea. Junto con el departamento de marketing se ha recopilado una lista de hipótesis que pueden ayudar a aumentar los ingresos. 

Es asi que se tendra priorizar estas hipótesis, lanzar un test A/B y analizar los resultados.

## Descripción de datos

Datos utilizados en la primera parte del proyecto

/datasets/hypotheses_us.csv Descarga el dataset

- Hypotheses: breves descripciones de las hipótesis
- Reach: alcance del usuario, en una escala del uno a diez
- Impact: impacto en los usuarios, en una escala del uno al diez
- Confidence: confianza en la hipótesis, en una escala del uno al diez
- Effort: los recursos necesarios para probar una hipótesis, en una escala del uno al diez. Cuanto mayor sea el valor Effort, más recursos requiere la prueba.
- Datos utilizados en la segunda parte del proyecto

 /datasets/orders_us.csv Descarga el dataset

- transactionId: identificador de pedido
- visitorId: identificador del usuario que realizó el pedido
- date: fecha del pedido
- revenue: ingresos del pedido
- group: el grupo del test A/B al que pertenece el usuario
/datasets/visits_us.csv Descarga el dataset

- date: la fecha
- group: grupo del test A/B
- visits: el número de visitas en la fecha especificada para el grupo de test A/B especificado
