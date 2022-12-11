# ECE539FinalProject
Final Project for ECE539 - Fall 2022- Group #5


CODE FILES

  CreateJson.ipynb: This piece of code takes the large reviews.json file and extracts a specified number of lines from it to create a reviewSmall.json file of manageable size readable by the pandas library.
  
  LoadJson.ipynb: This piece of code takes the smaller .json file created by CreateJson.ipynb and uses the pandas library to read the reviewSmall.json file and extract the data for our final project to use. This file's functionality is utilized in ECE539_Project.ipynb to load data.
  
  ECE539_Project.ipynb: This code is the main functionality of our project. This processes data, creates informative tables, and trains and tests data running it through all of the classifiers.
  
  
DATA FILES

  reviews.json: This is the data file containing all of the 6.9 milion reviews. Obviously this is far too large for processing. (NOTE: This file is not present in this repo on account of it being too large for github to accept. Link to source of this file is present in final report)
  
  reviewSmall.json: This is the data file that is 10000 reviews that was used for this project after reviews.json was processed through CreateJson.ipynb
