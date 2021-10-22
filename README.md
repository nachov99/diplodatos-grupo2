# Diplodatos - mentoria

## Setup de notebooks
1) Crear un entorno virtual:
```
virtualenv env
```
2) Inicializar entorno virtual:
```
linux & macos: source env/bin/activate
windows: .\env\Scripts\activate
```
3) Instalar paquetes necesarios:
```
pip install -r requirements.txt
```
4) Si creaste un entorno virtual:
```
python3 -m ipykernel install --user --name=python3
```
5) Correr Jupyter Lab:
```
jupyter-lab
```

## Descripción
El dataset se basa en una campaña de marketing de un banco de Portugal. Consiste en llamadas telefónicas a clientes para que adquieran un depósito de plazo fijo. \

El objetivo consiste en predecir si el cliente va a adquirir el producto o no (clasificación binaria). Este es un problema muy interesante ya que la mayoría de las empresas hacen campañas de marketing directo y necesitan saber cuáles son los clientes más propensos a adquirir los productos que ofrece. \

## Este tema es interesante porque...
El tema es interesante porque podremos ver cómo podemos usar Data Science para poder resolver un problema real de negocios. Parecería que es un problema simple de clasificación, sin embargo, existen muchas sutilezas que van a hacer que resolvamos el problema de forma adecuada o no. \

Otra razón interesante es que partiremos de un dataset crudo y veremos de punta a punta cómo abordar este problema, tanto desde el punto de vista de ciencia de datos como del punto de vista de negocios: veremos cómo obtener las mejores métricas posibles y también evaluaremos cómo presentar los resultados a nuestro potencial cliente. \

## Trataremos de responder algunas de las siguientes preguntas
¿Cómo impactan las variables demográficas en la adquisición de los plazo fijo?

¿Hay desbalance de clases? ¿Cómo puede solucionarse?

¿Qué métricas podemos utilizar? ¿Qué métricas podemos mostrar al banco de modo que comprenda el resultado obtenido?

¿Logramos encontrar algún insight que pueda serle útil al banco?

¿Cuáles son las features que más impactan en la obtención de un plazo fijo?

## Los datos
Si querés inspeccionar el conjunto de datos, lo encontrarás en el repositorio UCI:

https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

Utilizaremos el archivo más completo: bank-additional-full.csv, consiste en alrededor de 40.000 llamadas realizadas a clientes del banco (algunas llamadas son hacia el mismo cliente pero en otro momento).
