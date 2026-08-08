

# ¿Pueden las métricas offline medir los objetivos de explicación?

Este repositorio contiene el código del artículo "Can Offline Metrics Measure Explanation Goals? A Comparative Survey Analysis of Offline Explanation Metrics in Recommender Systems"

En este repositorio se encuentran tres análisis principales:

- Archivos de revisión bibliográfica 
- Archivos de grafos de conocimiento
- Archivos de estudio de usuarios en línea 

Para los experimentos offline, consulte [este repositorio](https://github.com/andlzanon/lod-personalized-recommender).

## :card_file_box: Organización

Este repositorio tiene tres carpetas principales, una para cada análisis que se informa en el artículo:

:file_folder: KnowledgeGraph

- :page_facing_up: [kg_exploration.ipynb](./KnowledgeGraph/kg_exploration.ipynb) cuaderno que contiene todos los gráficos del artículo

:file_folder: Literature_Review

- :page_facing_up: [lit_result_analysis.ipynb](./Literature_Review/lit_result_analysis.ipynb) cuaderno que contiene el análisis de la revisión bibliográfica de los artículos

- :page_facing_up: [lit_review_analysis.ipynb](./Literature_Review/lit_review_analysis.ipynb) análisis general con el número de artículos, eventos, etc. 

:file_folder: Online User Study

- :file_folder: docs: Archivos que contienen las respuestas de los usuarios del ensayo en línea
- :page_facing_up: [Online Analysis.ipynb](./Online%20User%20Study/Online%20Analysis.ipynb.ipynb): Contiene el análisis del artículo sobre las respuestas de los usuarios

## :package: Reproducción

Para los tres análisis utilizamos las siguientes bibliotecas:

- numpy
- pandas
- scipy
- matplotlib
- seaborn
- unicodedata

Utilizamos [Anaconda](https://www.anaconda.com/) para ejecutar los experimentos. La versión de Python utilizada fue la [3.12.3](https://www.python.org/downloads/release/python-3123/).

Para reproducir el entorno:

1. Cree su entorno: 

    ```conda create --name <env_name> python=3.12.3```

2. Active el entorno:
    
    ```conda activate <env_name>```

3. Instale las bibliotecas:
    
    ```conda install <lib>```


## :speech_balloon: Cita

Artículo enviado a ACM Transactions on Recommender Systems
