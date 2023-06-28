# The Vancover Crime Predictor

The purpose of this project is to setup a crime prediction model for Vancouver using its crime data from 2003 to 2017.

Link to dataset: https://www.kaggle.com/datasets/wosaku/crime-in-vancouver?select=crime.csv

The model used to make these predictions is from an algorithm called KNN (K-Nearest Neigbors). A description of the algorithm can be found here: https://www.geeksforgeeks.org/k-nearest-neighbours/. The reason I use this algorithm is because it's the one that make sense the most for the dataset with how it can use supervised learning for pattern recognition.
I've also made a file called crime-shortener to make the dataset smaller for easier testing.

In short, the accuracy of my model is around 30-45%. And even though it's better than random, the accuracy is not high enough to be considered reliable. I intend to use different algorithms to see if there are other ways to improve model accuracy. 

To run the program, just run Crime_Pred.ipnyb as a Python file and it will run on the crime_shortened.csv file by default to run quickly. You can change the link to file on crime.csv to run with the full dataset. 
