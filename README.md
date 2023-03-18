# Predicting Airbnb prices with machine learning and location data
 
Table of Contents
Installation
Project Motivation
File Descriptions
Results
Licensing, Authors, and Acknowledgements
Installation
All necesary libraries are indicated at the beggining of the notebook. The code should run with no issues using Python versions 3.*.

Project Motivation
As part of the IBM Data Science Professional Certificate, we get to have a go at our very own Data Science Capstone, where we get a taste of what is like to solve problems and answer questions like a data scientist. For my assignment, I decided to do yet another project that looks into the relationship between Airbnb prices and its determinants. However, being that I’m all about transportation research, I added a little touch of geospatial analysis by looking into locational features as possible predictors.

File Descriptions
I published a post in Towards Data Science, a more detailed report can be found here and the notebook here.

Results
After a rather long notebook and playing with a lot of variables, the best performing model was able to predict 65.56% of the variation in price with an RMSE of 0.19. Several other features are not part of our dataset or needed to be analysed more closely. It was noticeable that reviews about listing location, rather than the location features themselves, were higher in the feature importance list. Thus, perhaps Airbnb hosts should highlight this when writing their listing's description. Highlighting accessibility and location benefits of staying with them could perhaps benefit them and how much they can ask for their listing. This also shows the importance of reviews. So, image quality analysis is an interesting path to follow.

Licensing, Authors, Acknowledgements
Acknowledgements Laura Lewis's for examples on data preprocessing and Geoff Boeing for the accessibility analysis. Code to query foursquare for venues through all neighbourhoods was provided during the course. Feel free to use the code here as you would like!
