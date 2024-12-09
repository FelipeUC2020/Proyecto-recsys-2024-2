# Proyecto-recsys-2024-2

## Recursos 
* Documentación de OBP (Open Badint Pipeline) -> https://github.com/st-tech/zr-obp?tab=readme-ov-file#usage
* Paper: Open Bandit Dataset and Pipeline: Towards Realistic
and Reproducible Off-Policy Evaluation -> https://arxiv.org/pdf/2008.07146

## Overleaf
https://www.overleaf.com/7818642171knhtcgjjpkgp#177707


## Instrucciones de instalación de OBP:

1. Para poder ejecutar el proyecto se tiene que clonar el repositorio de OBP (https://github.com/st-tech/zr-obp)
2. Abrir el repositorio
3. Ejecutar el siguiente comando en la terminal: python setup.py install

## Descarga del dataset:

Debido a que pesa más de 25 mb debe ser descargado en el siguiente link: https://research.zozo.com/data.html. Una vez realizado lo anterior, se debe descomprimir dentro de la carpeta Baselines y 'código proyecto'

## Ejecución del proyecto:

* Los baselines están en la carpeta con dicho nombre. Contiene un jupyter notebook para el baseline de cada dataset (men, women y all)
* Para obtener los resultados, en la carpeta 'código proyecto' se encuentran los jupyter notebook. Al igual que los baselines, hay uno para cada dataset.
* Debido a los largos tiempos de ejecución subimos una carpeta 'Resultados' donde están los resultados de cada jupyter notebook en formato de pickle.

## Observaciones:

* Para cambiar la manera en que se hacen los clusters, se puede editar la función explorar_clusters comentando la variable 'user_features_encoded' y y descomentando 'user_features' y el 'user_features_encoded' que se encuentra comentado. Con esto se cambian las columnas seleccionadas al momento de realizar los clusters
