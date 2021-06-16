# Prototype Day

## Proyecto:
Se realiza la continuación del análisis de los datos y aplicación de algoritmos para la empresa Olist con los métodos adquiridos durante las sesiones de la *Etapa 3: Módulo 1-4* del curso de Data Science. 
De forma primordial se busca realizar un análisis de los comentarios determinando así una métrica de qué tan satisfecho ha quedado el cliente al recibir su producto, basado en la positividad de los comentarios comentarios según las palabras clave.

## Identificación del problema
Se requiere el análisis de los comentarios escritos por los clientes de Olist con el objetivo de crear una métrica de qué tan satisfecho ha quedado el cliente al recibir el producto basado en las palabras clave de la reseña/comentario.

## Descripión del Dataset

El dataset completo cuenta con información sobre el estatus de la orden, precio, pago, transporte a la localización del cliente, características del producto y reseñas de los clientes. Es importante mencionar que las ordenes y sus comentarios fueron escritas entre los años 2016 y 2018. 
A continuación se muestra un diagrama relacional de la base de datos.

![Diagrama de Base de Datos](utils/diagrama.png)

Para obtener los datos accede al siguiente enlace: https://www.kaggle.com/olistbr/brazilian-ecommerce
Descarga los archivos CSV y guárdalos en esta carpeta.

## Antes de ejecutar el Proyecto

Antes de ejecutar el notebook "Proy-LenguajeNatural.ipynb" debe hacer los siguientes pasos:

1. Descargar todos los archivos csv de Kaggle y guardarlos en la carpeta "dataset".
2. Correr el notebook "Preprocesamiento.ipynb" por completo, este generará un nuevo archivo llamado "df_complete.csv" en la carpeta actual.

NOTA: Recuerda instalar las librerias necesarias antes de correr los notebooks.
