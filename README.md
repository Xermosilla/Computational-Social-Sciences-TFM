# Computational-Social-Sciences-TFM-README
## Introduction

This repository contains two folders. In "thesis_research" you can find my complete master´s thesis and the presentation summarizing it. In the "thesis_code" folder, there are three subfolders: "datasets," "plots," and "scripts." Inside the "scripts" folder, you will find two codes necessary to replicate my thesis: one based on R (.Rmd), which serves as the primary code, and another code based on Python using Jupyter Notebook (.ipynb), which is required for the specific task of lemmatizing words.

Lemmatization was the only coding step carried out in Python because, when compared to R, this programming language offers more powerful natural language processing libraries for lemmatization.

## Download to replicate

Download and save every folder inside the "thesis_code" directory into the same folder, which will serve as the main directory. This step is crucial to maintain the correct paths for the code and to replicate it properly.

Open the script "tfm_code," load the libraries, and if any library is missing, install it using the code 'install.packages("the name of the library that is not downloaded on your device," enclosed in quotation marks').'

## IMPORTANT!

For ethical web scrapping, in chunks 3 and 4, set your personal user agent with your name and email, so that you can be easily contacted.

## Structure of the script

The full R code, named "tfm_code", is divided into four main blocks:

- **Literature review graph** A graph created using data collected from the InfoAdex Study of Advertising Investment in Spain, to visually represent my theoretical point.

- **Data gathering and processing** All necessary data were scraped from "https://info.mercadona.es/es/conocenos/sala-de-prensa/hemeroteca?idCategoriaSeleccionada=1470731303723&tipoVisualizacion=grid&numPagina=1" and cleaned.

- **Text mining techniques** In *chunk 24*, I performed lemmatization in *Pyhton*. To replicate that part of the code, you need to execute the code line that saves data, then switch to the Python code and run it, and finally, return to the R code and execute the code line that opens the lemmatized dataset.

- **Latent Dirichlet Allocation** Probabilistic model used to uncover hidden topics within a collection of documents. Using it involved an iterative process to fine-tune the model and extract meaningful insights.
