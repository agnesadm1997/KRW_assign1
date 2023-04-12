<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="KRW_assign1" />

  &#xa0;

  <!-- <a href="https://krw_assign1.netlify.app">Demo</a> -->
</div>

<h1 align="center">KRW_assign1</h1>

<p align="center">
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  KRW_assign1 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

This repository contains several jupyter notebooks for a project that explores the relationships between medication, patient characteristics, and patient outcomes. The project includes data cleaning, ontology building, and machine learning models for clustering and link prediction.

## :sparkles: Features ##

The project includes the following files: \
:heavy_check_mark: Feature 1; data_cleaning.ipynb: cleans the opiods_data_original_xlxs and also adds another dataset to it (sider_ouput.xlxl) and merges them to one file \
:heavy_check_mark: Feature 2; ontology_medsur.ipynb: builds an ontology from the dataet and exports it all the generated triples as a csv ttl and rdf file \
:heavy_check_mark: Feature 3; clustering_chars.ipynb: performs clustering machine learning on the data set medsur.csv based on patient characteristics using the ampligraph model \
:heavy_check_mark: Feature 4; clustering_symps.ipynb: performs clustering machine learning on the data set medsur.csv based on patient symptoms using the ampligraph model \
:heavy_check_mark: Feature 5; link_prediction.ipynb: performs 4 link predictions: \
outcome recovery for different weight groups of patients \
outcome recovery for different age groups of patients \
symptoms for different types of prescribed drugs \
side-effect occurrence for different types of prescribed drugs \
For each prediction, a CSV file is exported containing the prediction scores and probabilities for each group or drug type.

## :rocket: Tools ##

The following tools were used in this project

- Python 3.7 or higher
- Jupyter Notebook
- PyKEEN
- AmpliGraph
- Scipy
- Tensorflow
- RDFLib
- NetworkX
- Owlready

Please make sure you have installed all above packages before getting started.

## :checkered_flag: Starting ##

To run the code, follow these steps:

Clone the repository: git clone https://github.com/agnesadm1997/KRW_assign1.git
Install the required packages: pip install -r requirements.txt
Open Jupyter Notebook and navigate to the cloned repository.
Open the desired notebook file and run the cells.

&#xa0;

<a href="#top">Back to top</a>
