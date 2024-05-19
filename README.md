# Coding Environment Setup for the Field Lab 2024 (20 minutes)

This document details installations that you should do to set up a minimal environment for performing effective coding and visualization. This document is most relevant for the AI/ML and data visualization working groups.

The most relevant sessions are on Monday (May 20, 2024) and Tuesday (May 21, 2024), so please follow the steps prior to that.

## Tools

We will be working with four tools:
1. Github. This is a code management and version control software which is especially helpful when working within teams.
2. QGIS: This is an open-source GIS (Geographic Information Systems) platform, useful for viewing spatial data.
3. R: This is a handy coding language, useful for quick, small-scale coding related to statistics and machine learning.
4. Python (optional): This is an extensive coding language, fantastic for large-scale efficient coding.

## Steps

Please follow the steps prior to coming to the Entrance Cafe, so that we do not run into wifi overload.

1. This step matters only if you are interested in **contributing** to coding projects. If you just want to play with code and learn, you are welcome to skip this step.
    1. Please [register for a Github account](https://github.com/) if you do not have one already. 
    2. Provide your github id (or username) to Neel on Slack with the word ‘github’ in the message, so that he can add you to the Field Lab Github organization.’
    3. Download [Github Desktop](https://desktop.github.com/), and log in with your Github.
2. Download [QGIS](https://www.qgis.org/en/site/forusers/download.html). If you have ArcMap already, then you do not need this. Note that QGIS is a heavy software and takes up a lot of space.
3. Set up R:
    1. Download [R](https://cran.r-project.org/). This is the core program compiler and interpreter.
    2. Download [R-studio](https://posit.co/download/rstudio-desktop/). This is a nice platform to work with R.
4. Set up Python (optional). This will create a basic conda environment with useful packages:
    1. Download and install [miniforge](https://github.com/conda-forge/miniforge?tab=readme-ov-file). Go to the link, scroll down to download, and choose the one that matches your operating system. Miniforge is a light-weighted system for downloading packages relevant to Python.
    2. If Windows, open Miniforge prompt. If Mac, open terminal.
    3. Download the environment builder [fieldlab.yml](https://github.com/UR-Field-Labs/system-setup/blob/main/fieldlab.yml) file (there should be a download button in a dropdown menu for one of the buttons on the right. _fieldlab.yml_ is a simple environment file to provide you the necessary python modules.
    4. Navigate via Miniforge prompt (or terminal if Mac) to the folder which contains the _fieldlab.yml_ file that you downloaded. 
    5. Run the command: ```conda env create -f fieldlab.yml``` you downloaded
    6. To enter the environment, run the command: ```conda activate fieldlab```


If you have any questions/issues, please reach out to Neel on Slack.
