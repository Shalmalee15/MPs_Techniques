# MPs_Techniques
Here I am uploading all the codes which I use for detecting the MPs in the clusters I considered. (Still in progress!). 
You will need the  files containing the information about the magnitudes and colours of the choice of your cluster. 
This code will separate your red giant branch (RGB) from the main sequence (MS), next it divides the RGB horizontally into smaller bins, and then the median value for each bin is calculated. Later on, it fits the median points and that becomes our ridge line. 
Next, it calculates the horizontal distance from this line to each star and makes a histogram plot of distance distribution. 
The next step involves overplotting the distance distribution with the Kerner Density Distribution (KDE). 
It also gives out the values of mean, standard deviation, width at 20 and 50 per cent of the distribution maxima. 
