# Data_Wrangling_Project

## Introduction

This repository contains the first project of the ALX-T’s Data Analyst program in association with Udacity. The goal of this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations

Using Python and its libraries, I gathered data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. The wrangling efforts have been documented in a Jupyter Notebook `wrangle_act.opynb`, The notebook also showcases the analyses and visualizations using Python (and its libraries).

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. WeRateDogs has over 4 million followers and has received international media coverage.

## Project implementation Steps Overview

The analysis tasks in this project are as follows:

      Step 1: Gathering data

      Step 2: Assessing data

      Step 3: Cleaning data

      Step 4: Storing data

      Step 5: Analyzing, and visualizing data

      Step 6: Reporting
         - data wrangling efforts
         - data analyses and visualizations


## Installations
The following packages (libraries) need to be installed. You can install these packages via conda or pip. Please revisit our Anaconda tutorial earlier in the Nanodegree program for package installation instructions.
   
         -	pandas

         -	NumPy

         -	requests

         -	tweepy

         -	json


## Data
This project, includes three datasets.

__Enhanced Twitter Archive__

The WeRateDogs Twitter archive (`twitter-archive-enhanced`) contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which was used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, tweets are filtered for ratings only (there are 2356).

__Additional Data via the Twitter API__

This dataset (`tweet_df`) contains retweet count and favorite count which are two of the notable column omissions from the dataset above. Fortunately, this additional data can be gathered by from Twitter's API through data wrangling. I was able to query Twitter's API to gather this valuable data. 

__Image Predictions File__

This dataset (`image_predictions`) contain a classification of breeds of dogs*. The dataset is  a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).


The combined and cleaned dataset for the overall analysis and visualizations is: `twitter_archive_master.csv`


## Result

`wrangle_report.pdf` or `wrangle_report.ipynb` is a written report that briefly describes the wrangling efforts. 
`act_report.pdf` or `act_report.ipynb` is a written document  that communicates all the insights and displays the visualization(s) produced from the wrangled data. 

