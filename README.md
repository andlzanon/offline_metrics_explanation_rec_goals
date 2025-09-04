# Can Offline Metrics Measure Explanation Goals?

This repository contains code of the paper "Can Offline Metrics Measure Explanation Goals? A Comparative Survey Analysis of Offline Explanation Metrics in Recommender Systems"

There are three main analyses on this repository:

- Literature Review files 
- Knowledge Graphs files
- Online User study files 

For the offline experiments, please check [this repository](https://github.com/andlzanon/lod-personalized-recommender).

## :card_file_box: Organization

This repository has three main folders, one for each analysis that is reported on the paper:

:file_folder: KnowledgeGraph

- :page_facing_up: [kg_exploration.ipynb](./KnowledgeGraph/kg_exploration.ipynb) notebook containing all plots from the paper

:file_folder: Literature_Review

- :page_facing_up: [lit_result_analysis.ipynb](./Literature_Review/lit_result_analysis.ipynb) notebook containing the literature review analysis of the papers

- :page_facing_up: [lit_review_analysis.ipynb](./Literature_Review/lit_review_analysis.ipynb) overall analysis with number of papers, venues, etc 

:file_folder: Online User Study

- :file_folder: docs: Files containing users' response from the online trial
- :page_facing_up: [Online Analysis.ipynb](./Online%20User%20Study/Online%20Analysis.ipynb.ipynb): Contains the analysis of the paper on the user responses

## :package: Reproduction

For the three analyses we used the following libraries:

- numpy
- pandas
- scipy
- matplotlib
- seaborn
- unicodedata

We used [Anaconda](https://www.anaconda.com/) to run the experiments. The version of Python used was the [3.12.3](https://www.python.org/downloads/release/python-3123/).

To reproduce the environment then:

1. Create your env: 

    ```conda create --name <env_name> python=3.12.3```

2. Activate env:
    
    ```conda activate <env_name>```

3. Install the libraries:
    
    ```conda install <lib>```


## :speech_balloon: Citation

Paper submited to ACM Transactions on Recommender Systems