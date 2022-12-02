Twitter Sentiment Geographical Index - README
================
Angelo Marra
2022-10-23

This document will help explain how to build my final report using my
GitHub Repository and Project Directory.

Github Repository: 
<https://github.com/amarra1122/FinalProject>

Link to Docker Image Used to Build Project Container:
<https://hub.docker.com/repository/docker/amarra1122/finalproject>

## **1.:** Before running any R code - restore the R package environment by running the command "make install" in terminal. 

## **2:** You can proceed to run all four R scripts in the ‘code’ folder - or use the “Make Final_Project.html” to produce the final project.
* code/01_load_data stores the desired data frame as an R object
* code/02_make_table creates and stores a descriptive table for the final report as an R object. 
* code/03_make_graph creates and stores a descriptive graph for the final report as an R object. 
* code/04_render_report will create an html file of the final compiled report once the previous three R codes have been ran. 

All objects and data created by the preceding R scripts are stored in the 'output' folder in the project directory.

## **3:** In order to remove any objects, data, or generated report run the command 'make clean' in the terminal.

## **4:** To automate this process using Docker - the final report may be generated using a Docker container on Mac or Windows by running the following command in terminal: "make container."
