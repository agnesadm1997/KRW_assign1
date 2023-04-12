<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="KRW_assign1" />

  &#xa0;

  <!-- <a href="https://krw_assign1.netlify.app">Demo</a> -->
</div>

<h1 align="center">KRW_assign1</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/{{YOUR_GITHUB_USERNAME}}/krw_assign1?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/{{YOUR_GITHUB_USERNAME}}/krw_assign1?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/{{YOUR_GITHUB_USERNAME}}/krw_assign1?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/{{YOUR_GITHUB_USERNAME}}/krw_assign1?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/{{YOUR_GITHUB_USERNAME}}/krw_assign1?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/{{YOUR_GITHUB_USERNAME}}/krw_assign1?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/{{YOUR_GITHUB_USERNAME}}/krw_assign1?color=56BEB8" /> -->
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
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

This repository contains several jupyter notebooks for a project that explores the relationships between medication, patient characteristics, and patient outcomes. The project includes data cleaning, ontology building, and machine learning models for clustering and link prediction.

## :sparkles: Features ##

The project includes the following files:
:heavy_check_mark: Feature 1; data_cleaning.ipynb: cleans the opiods_data_original_xlxs and also adds another dataset to it (sider_ouput.xlxl) and merges them to one file
:heavy_check_mark: Feature 2; ontology_medsur.ipynb: builds an ontology from the dataet and exports it all the generated triples as a csv ttl and rdf file
:heavy_check_mark: Feature 3; clustering_chars.ipynb: performs clustering machine learning on the data set medsur.csv based on patient characteristics using the ampligraph model
:heavy_check_mark: Feature 4; clustering_symps.ipynb: performs clustering machine learning on the data set medsur.csv based on patient symptoms using the ampligraph model
:heavy_check_mark: Feature 5; link_prediction.ipynb: performs 4 link predictions:
outcome recovery for different weight groups of patients
outcome recovery for different age groups of patients
symptoms for different types of prescribed drugs
side-effect occurrence for different types of prescribed drugs
For each prediction, a CSV file is exported containing the prediction scores and probabilities for each group or drug type.

## :rocket: Technologies ##

The following tools were used in this project:

- [Expo](https://expo.io/)
- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/{{YOUR_GITHUB_USERNAME}}/krw_assign1

# Access
$ cd krw_assign1

# Install dependencies
$ yarn

# Run the project
$ yarn start

# The server will initialize in the <http://localhost:3000>
```

&#xa0;

<a href="#top">Back to top</a>
