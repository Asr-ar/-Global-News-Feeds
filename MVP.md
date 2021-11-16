## Global-News-Feeds
Over 1000 observations to represent a sample of our data,
And when applying the TF_IDF we get a high dimensions  of 3752 ,
To avoid the  curse-of-dimensionality we can  use PCA to project them to a more manageable number of dimensions, say two:

<img width="458" alt="Screen Shot 1443-04-11 at 8 14 35 PM" src="https://user-images.githubusercontent.com/90555069/142037439-f5c3d851-3e49-4537-97e9-925346fe58c8.png">

**Recall what these components mean:** the full data is a 3752
-dimensional point cloud, and these points are the projection of each data point along the directions with the largest variance. Essentially, we have found the optimal stretch and rotation in 3752
-dimensional space that allows us to see the layout of the data in two dimensions, and have done this in an unsupervised manner—that is, without reference to the labels.
 
 **Next step : design Topic Model with gensim(LDA)**

