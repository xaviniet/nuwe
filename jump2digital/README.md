## Datasets

### Variables del dataset:

**order_id**: Número de identificación del pedido.

**local_time**: Hora local a la que se realiza el pedido.

**country_code**: Código del pais en el que se realiza el pedido.

**store_address**: Número de tienda en a la que se realiza el pedido.

**payment_status**: Estado del pedido.

**n_of_products**: Número de productos que se han comprado en ese pedido.

**products_total**: Cantidad en Euros que el usuario ha comprado en la app.

**final_status**: Estado final del pedido (este será la variable 'target' a predecir) que indicara si el pedido será finalmente entregado o cancelado. Hay dos tipos de estado:

```  
    - CanceledStatus: La entrega se ha cancelado  
    - DeliveredStatus: La entrega se ha realizado correctamente`
```

### Archivos:

**train.csv**: Este dataset contiene tanto las variables predictoras como el estado del pedido (TARGET).
**test_X.csv**: Este dataset contiene las variables predictoras con las que se tendrá que predecir el estado de un pedido.
ejemplo_predicciones.csv: Este dataset es un ejemplo de como se debera entregar las predicciones del objetivo número 6 de las tareas a relizar.
Para descargar el dataset de 'train.csv' haz click aquí.

Para descargar el dataset de 'test_X.csv' haz click aquí.

Para descargar el dataset de 'ejemplo_predicciones.csv' haz click aquí.

## Objetivos

Para las preguntas 1,2,3 y 4 emplea el dataset train.csv Para la pregunta 5 deberás emplear el dataset 'train.csv' y 'test_X.csv'.

1. ¿Cuáles son los 3 paises en los que más pedidos se realizan?
2. ¿Cuáles son las horas en las que se realizan más pedidos en España?
3. ¿Cuál es el precio medio por pedido en la tienda con ID 12513?
4. Teniendo en cuenta los picos de demanda en España, si los repartidores trabajan en turnos de 8horas.
- Turno 1 (00:00-08:00)
- Turno 2 (08:00-16:00)
- Turno 3 (16:00-00:00)
Qué porcentaje de repartidores pondrías por cada turno para que sean capaces de hacer frente a los picos de demanda. (ej: Turno 1 el 30%, Turno 2 el 10% y Turno 3 el 60%).

5. Realiza un modelo predictivo de machine learning a partir del dataset 'train.csv' en el cual a partir de las variables predictoras que se entregan en el dataset 'test_X' se pueda predecir si el pedido se cancelará o no (columna 'final_status').
Siendo:

Para simplificar, podeis asignar los valores 'CanceledStatus' a 0 y los valores 'DeliveredStatus' a 1.

0 = CanceledStatus
1 = DeliveredStatus

Entrega las predicciones en un csv a parte. Tal y como puede verse en el ejemplo de 'ejemplo_predicciones'. La calidad de la predicción se medira a partir del f1-score(macro).

Regístrate en la plataforma de NUWE para realizar el reto el próximo 22 de noviembre.
