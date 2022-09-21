# WeRateDog_analysis 


## Introduction
This project investigates the data wrangling process using python and its library. It involves gathering of real- world data from different sources and formats after which the data are access for quality and tidiness issues to be cleaned. The dataset are merged and stored as a tidy master dataset after cleaning for further analysis and visualizytion. All process invloved were carefully documented using a Jupyter notebook. The python libraries used are: Numpy, Pandas, Request, Json, io, itertools, matplotlib and seaborn.

### Data Description
The goal of this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

The project worked with three dataset which are as explained below:

### Enhanced Twitter Archive
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which was used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets,only tweets with ratings were filtered to get a total of 2356 data.

### Image Predictions File
The images from the WeRateDogs twitter archive was run through a neural network which is designed to classify dogs breed. The result was atable of top three images predictions, the twitter Id, image url and the image number that corresponded to the most coefficient.

### Tweet JSON
This was extracted programmatically using twitter API tweepy.