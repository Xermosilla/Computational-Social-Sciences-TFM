# Computational-Social-Sciences-TFM
## Introduction

This repository has two folders. In "thesis_research" you can find my complete master´s thesis and the presentation that sums it up, and in "thesis_code", you can find three folders "datasets", "plots" and "scripts". Inside "scripts" there are two codes needed to replicate my thesis. One based on R which is the main code, and other code based on Python, needed for the specific task of lemmatizing words. 

Lemmatization was the only coding step done on Python, because when compared to R, this programming language offers more powerful natural language processsing libraries for lemmatization.

## Download to replicate

Download and save every folder inside "thesis_code" in the same folder, which will be the main directory. This step is very important to mantain the paths of the coding and to replicate the code properly. 

Open the script "tfm_code", load the libraries and, if any library is missing, install it with the code 'install.packages("the name of the library that is not downloaded in your device, inside quoatation marks")'

## IMPORTANT!

For ethical web scrapping, in chunks 3 and 4, set your personal user agent, with your name and email, so you are easier to contact.

## Structure of the script

The full R code named "tfm_code", is divided in four main blocks:

- **Literature review graph** A graph done with data collected from InfoAdex Study of Advertising Investment in Spain, to visualize easily my theoretical point

- **Data gathering and processing** All data needed was scrapped from "https://info.mercadona.es/es/conocenos/sala-de-prensa/hemeroteca?idCategoriaSeleccionada=1470731303723&tipoVisualizacion=grid&numPagina=1" and cleaned 

- **Text mining techniques** In chunk 24 I have performed lemmatization in Pyhton, therefore to replicate that part of the code you need to run the code line that saves data, then move to the Pyhton code and run it, and finally go back to the R code and open the lemmatized dataset.

- **Latent Dirichlet Allocation** Probabilistic model used to uncover hidden topics within a collection of documents. Using it was an iterative process to fine-tune the model and extract meaningful insights.
