# Universityhack2018
Donkeys - Universityhack 2018

## Objetivo

Te retamos a que encuentres el mejor modelo de regresión mediante el desarrollo de un modelo predictivo que defina con precisión el poder adquisitivo del cliente.
Para ello puedes utilizar las distintas técnicas de Machine Learning disponibles para este tipo de problemas.

## Dataset

Se proporciona un dataset con datos históricos de un grupo clientes, particulares y autónomos, del con 88 variables de productos incluyendo atributos socio demográficos. El desafío consiste en estimar el poder adquisitivo del cliente en base a la información suministrada.

## Registros
El número total de registros es de 363.834 con 89 variables por registro. Con el fichero de Train deberás construir un modelo predictivo que permita estimar el poder adquisitivo del cliente, para ello dispones de este fichero con las distintas variables explicativas a nivel de cliente y una variable Poder_Adquisitivo a predecir.

## Variables

* ID_Customer: Identificador de cliente.
* Socio_Demo_01-05: Variables sociodemográficas relacionadas con el cliente.
* Imp_Cons_01-17: Importe de consumos habituales del cliente en base a sus operaciones con tarjetas y domiciliaciones más comunes.
* Imp_Sal_01-21: Importe de los saldos de los distintos productos financieros.
* Ind_Prod_01-24: Tenencia de los distintos productos financieros.
* Num_Oper_01-20: Número de operaciones a través de los distintos productos financieros.
* Poder_Adquisitivo: Variable objetivo, variable numérica que define el poder adquisitivo del cliente.

Las siguientes variables son numéricas:
* Desde Imp_Cons_01 hasta Imp_Cons_17.
* Desde Imp_Sal_01 hasta Imp_Sal_21.
* Desde Num_Oper_01 hasta Num_Oper_20.
* Socio_Demo_03 hasta Socio_Demo_05.
* Poder_Adquisitivo.

Las siguientes variables son categóricas:
* Desde Ind_Prod_01 hasta Ind_Prod_24
* Socio_Demo_01 y Socio_Demo_02
