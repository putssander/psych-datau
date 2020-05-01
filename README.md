# PSYCH-DATAU #

Data Utilities for PRE/POST-processing psychology-data and analysis of results.

- Link subject PRE and POST responses [link](notebooks/link_subject_pre_post_responses.ipynb)
- Classify objective binges [link](notebooks/filter_objective_binges.ipynb)

## Dependencies ##

REQUIRED:
- docker [https://hub.docker.com/](https://hub.docker.com/) 

RECOMMENDED:
- git [https://git-scm.com/downloads](https://git-scm.com/downloads) 



## Install ##

1. Clone or download (button) this repository

        git clone https://github.com/putssander/psych-datau.git

## Run ##
1. Navigate to the cloned or downloaded project using the terminal or cmd
    
2. Start docker-compose

        docker-compose up
    
3. Find the Jupyter link in the log file and copy the link in the browser. 

        jupyter-psych-datau             | [I 12:06:45.669 NotebookApp]  or http://127.0.0.1:8888/?token=0c01e853a34a4bb0db3a542ca15c3af036cab7a11fd64bb2

6. Navigate to the desired notebook in the browser (directory notebooks)

7. Data can be copied to the resources/data_ignored folder (needs to be created and is ignored)
