# 🖥 RETO

## Background

Nuwefruit es una startup que busca revolucionar los hábitos de la población fomentando el cosumo de fruta a diario. Por este motivo, la empresa está especializada en la venta de fruta a domicilio, que gracias a su algoritmo de optimización de la última milla le permite tener unos costes logisticos muy bajos. Esto permite que Nuwefruit pueda vender fruta a un precio inferior al de su competencia. Su catálogo se basa en la venta de más de 20 tipos de frutas, que son las que presentan las mejores propiedades nutritivas.

## Overview: the dataset and challenge

Se emplearan dos datasets: el primero contiene datos de los clientes de Nuwefruit y el otro contiene los datos de los pedidos realizados por estos.

El dataset de clientes 'CLIENT TABLE' contiene las siguientes variables:

**CLIENT ID**: Identificador único del cliente
**CLIENT_SEGMENT**: Segmento de clientes  
**AVG CONSO**: Consumo medio mensual del cliente calculado a finales de 2020 (en piezas de fruta)  
**AVG BASKET SIZE**: Tamaño medio de la cesta del cliente calculado a finales de 2020 (en piezas de fruta)  
**RECEIVED_COMMUNICATION**: 1 = Recibió promoción de sus productos / 0 = no la recibió
Haz click aquí para descargar 'CLIENT TABLE' dataset.

El dataset de clientes 'ORDERS TABLE' contiene las siguientes variables:

**CLIENT ID**: Identificador único del cliente  
**NB PRODS**: Número de 'prods' de la variedad de fruta en el pedido (1 prod = 10 piezas de fruta)  
**ORDER ID**: Identificador único del pedido  
**FRUIT_PRODUCT**: Variedad de fruta  
Haz click aquí para descargar 'ORDERS TABLE' dataset.

## Objetivos

- Haz un analisis exploratorio de los datos que permita:
    - Analizar las ventas y la actividad de los clientes
    - Evaluar el impacto de la promoción
- Realiza un modelo predictivo que permita conocer el tipo de segmento al que pertenece cada cliente en función de las siguientes variables predictoras: Descargar test_x. (Se ha de predecir la variable (CLIENT_SEGMENT)).

900 puntos -> Objetivos. Los objetivos se evaluarán en función del EDA realizado y del f1-score(macro) obtenido al comparar las predicciones de tu algoritmo cuando se les mete como input las variables del dataset 'test_x'.
200 puntos -> Cálidad del código
100 puntos -> Documentación